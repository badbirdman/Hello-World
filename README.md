README
============================


# HELLO WORLD!!
---
## HELLO WORLD!!
### HELLO WORLD!!
#### HELLO WORLD!!
##### HELLO WORLD!!
###### HELLO WORLD!!

### 锚点
其实呢，每一个标题都是一个锚点，和HTML的锚点（`#`）类似，比如我们

|语法|效果|
|---|---|
|`[回到顶部](#readme)`|[回到顶部](#readme)|

## 列表
### 无序列表
* 昵称：果冻虾仁
- 别名：隔壁老王
* 英文名：Jelly

### 多级无序列表
* 编程语言
    * 脚本语言
        * Python


### 有序列表
#### 一般效果
就是在数字后面加一个点，再加一个空格。不过看起来起来可能不够明显。    
面向对象的三个基本特征：

1. 封装
2. 继承
3. 多态

#### 多级有序列表
和无序列表一样，有序列表也有多级结构：  

1. 这是一级的有序列表，数字1还是1
   1. 这是二级的有序列表，阿拉伯数字在显示的时候变成了罗马数字
      1. 这是三级的有序列表，数字在显示的时候变成了英文字母


### 复选框列表
- [x] 需求分析
- [x] 系统设计
- [x] 详细设计
- [ ] 编码
- [ ] 测试
- [ ] 交付



### 块引用有多级结构
> 数据结构
>> 树
>>> 二叉树
>>>> 平衡二叉树
>>>>> 满二叉树

代码高亮
----------
在三个反引号后面加上编程语言的名字，另起一行开始写代码，最后一行再加上三个反引号。
```Java
public static void main(String[]args){} //Java
```
```c
int main(int argc, char *argv[]) //C
```
```Bash
echo "hello GitHub" #Bash
```
```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```
```cpp
string &operator+(const string& A,const string& B) //cpp
```


表格
--------

表头1  | 表头2|
--------- | --------|
表格单元  | 表格单元 |
表格单元  | 表格单元 |

| 表头1  | 表头2|
| ---------- | -----------|
| 表格单元   | 表格单元   |
| 表格单元   | 表格单元   |



表情
----------
Github的Markdown语法支持添加emoji表情，输入不同的符号码（两个冒号包围的字符）可以显示出不同的表情。
比如`:blush:`，可以显示:blush:。
具体每一个表情的符号码，可以查询GitHub的官方网页[http://www.emoji-cheat-sheet.com](http://www.emoji-cheat-sheet.com)。
但是这个网页每次都打开**奇慢**。。所以我整理到了本repo中，大家可以直接在此查看[emoji](./emoji.md)

diff语法
---------
版本控制的系统中都少不了diff的功能，即展示一个文件内容的增加与删除。
GFM中可以显示的展示diff效果。使用绿色表示新增，红色表示删除。

其语法与代码高亮类似，只是在三个反引号后面写diff，
并且其内容中，以 `+ `开头表示新增，`- `开头表示删除。

效果如下：

```diff
+ 鸟宿池边树，僧敲月下门
- 鸟宿池边树，僧推月下门
```

### 图片链接
|#|语法|效果|
|---|----|:---:|
|1|`[![weibo-logo]](http://weibo.com/)`|[![weibo-logo]](http://weibo.com/)|
|2|`[![](/img/zhihu.png "知乎")][zhihu]`|[![](/img/zhihu.png "知乎")][zhihu]|
|3|`[![csdn-logo]][csdn]`|[![csdn-logo]][csdn]|

资源引用
-----------------
[csdn]:http://www.csdn.net/ "CSDN"
[zhihu]:https://www.zhihu.com/ "知乎"
[baidu-logo]:http://www.baidu.com/img/bdlogo.gif "百度logo"
[weibo-logo]:/img/weibo.png "点击图片进入我的微博"
[csdn-logo]:/img/csdn.png "我的CSDN博客"


### 出处

https://github.com/guodongxiaren/README



