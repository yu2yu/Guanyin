## Markdown



### 基本用法

#### 1. 字体

```markdown
# 一级标题
<h1>一级标题</h1>

*斜体*

**加粗**
```



#### 2. 列表

```markdown
* 列表一
* 列表二

1. 列表一
2. 列表二
```



#### 3. 表格

```markdown
| header1 | header2 | header3 |
|:-------:|:-------:|:-------:|
| content1|content2 | content3|

分割线中的`:`代表的是左对齐还是右对齐还是居中

任务列表
- [x] todo 1
- [ ] todo 2 
```



#### 4. 图片

```markdown
![图片描述](https://xxxx.com)
<img src="https://xxx.com" />
```



#### 5. 代码

```markdown
​```javascript
function DisplayWindowSize(){

  var w=window.innerWidth
  || document.documentElement.clientWidth
  || document.body.clientWidth;
}
​```
```





### 高阶用法



#### 折叠

```markdown
<details>
	<summary>description</summary>
	
	```shell
	echo 'hello'
	```
</details>
```





#### 标签

##### label

```markdown
![License](https://img.shields.io/badge/license-MIT-yellow) #静态badge图标
```

<img src="https://img.shields.io/badge/license-MIT-yellow" align=left />



##### emoji

emoji的表情在`https://emojipedia.org/`

```mark
:heart:
```

:heart:





---



### 附录

私心推荐一款***markdown***工具：<u>[typro](https://typora.io/)</u>



推荐几个**github**上写的比较好的**markdown**文章，可以**copy下来模仿一下**，还是觉得说如果你维护一个开源项目并且想开源**一份好的文档是非常重要的**



#### 项目型

***mall：https://github.com/macrozheng/mall*** 

基本上包含了一个项目基本上的所有点，项目文档、项目地址、项目技术、项目架构



#### 工具型

***hutool ：https://github.com/dromara/hutool***

**A set of tools that keep Java sweet.**

