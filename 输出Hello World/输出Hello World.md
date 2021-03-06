# 输出Hello World

`PS：请忽视<p></p>的行的内容`

先看一眼效果：

![终端](.\终端.png)

怎么样？

## 一.书写基本框架

首先头文件：

```c++
#include <iostream>
```

C++库（方便编辑）： 

```C++
using namespace std;
```
基本框架：

```c++
int main()
{
}
```
结束：

```return 0;```
然后就基本完成了：

```c++
#include <iostream>
using namespace std;
int main()
{
    return 0;
}
```

这样的话什么都不会输出

## 二.输出内容

```c++
cout<<"你要说的话";
```
然后：

```c++
#include <iostream>
using namespace std;
int main()
{
	cout<<"你要说的话";
    return 0;
}
```
然后就可以输出了：

图片

你学会了么？

例题1：输出：Hello World
```c++
#include <iostream>
using namespace std;
int main()
{
	cout<<"Hello World";
    return 0;
}
```
例题2：输出：a
```c++
#include <iostream>
using namespace std;
int main()
{
	cout<<"a";
	return 0;
}
```
## 三.换行的方式

假设你想书写一段话：你可能尝试这么写：


```c++
#include <iostream>
using namespace std;
int main()
{
    cout<<"Hello World";
	cout<<"我要换行！";
	return 0;
}
```
但是可能运行后：

![未换行输出](.\未换行输出.png)

### 法一：加<<endl;
在文本双引号后输入`<<endl;`
如下：

```c++
#include <iostream>
using namespace std;
int main()
{
    cout<<"Hello World"<<endl;
	cout<<"我要换行！";
	return 0;
}
```
这样：![换行输出](.\换行输出.png)

### 法2:加\n
在**文本内输入**`\n`
```c++
#include <iostream>
using namespace std;
int main()
{
    cout<<"Hello World\n";
	cout<<"我要换行！";
	return 0;
}
```
效果相同，但是你可以这样：

![You can also](.\You can also.png)

例题3：输出图形
```c++
#include <iostream>
using namespace std;
int main()
{
cout<<" ##     ##    ##"<<endl;
cout<<"  ############"<<endl;
cout<<"    ########"<<endl;
cout<<"     ######"<<endl;
cout<<"       # "<<endl;
    return 0;
}
```
例题四：输出长方形
```c++
#include <iostream>
using namespace std;
int main()
{

cout<<"####################"<<endl;
cout<<"#                  #";
cout<<"#                  #";
cout<<"#                  #";
cout<<"#                  #";
cout<<"####################";
    return 0;
}
```
> 