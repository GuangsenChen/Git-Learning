
# 一级标题
## 二级标题
### 三级标题
#### 四级标题

#### 无序列表
- 列表 1
    - 列表 1.1
    - 列表 1.2
- 列表 2
- 列表 3

#### 有序列表
1. 列表 1
    1. 列表 1.1
    2. 列表 1.2
2. 列表 2
3. 列表3

#### 引用
> 记录，成为更好的自己。 --有道云笔记

*这是斜体*

**这是粗体**

#### 注意：符号与文本之间无须空格

#### 插入链接
[有道云笔记官网](http://note.youdao.com/)

#### 插入图片
![有道云笔记](http://note.youdao.com/favicon.ico)

#### 分割线

这是第一段的内容
***
这是第二段的内容

#### 表格
header 1 | header 2
--- | ---
row 1 col1 | row 1 col 2
row 2 col1 | row 2 col 2

| Item      |   value |  Qty |
| :---------| -------:| :--: |
|Computer   | 1600 USD|   5  |
|Phone      |   12 USD|  12  |
|Pipe       |    1 USD|  234 |

#### To-do List
- [x] 已完成项目1
    - [x] 已完成事项1
    - [x] 已完成事项2
- [ ] 未完成事项 1
- [ ] 未完成事项 2

### 流程图
TB - top bottom(自上而下)

Bt - bottom top(自下而上)

RL - right left(自右到左)

LR - left right(自左到右)
#### 自上而下的顺序
```
graph TD
A-->B
```

#### 自左到右
```
graph LR
A-->B
```

#### 流程框图具体案例
```
graph TD
    A[Christmas] --> B(Go shopping)
    B --> C{Let me think}
    C --> |One| D[Laptop]
    C --> |two| E[Iphone]
    C --> |Three| F[car]
```

#### 对框线形状的调整
```
graph LR
    A[这是直角四边形]
    B((这是圆形))
    C{这是菱形}
```
#### 对箭头的调整
```
graph LR
A[A] --- B[B]
C[C] --> D[D]
E[E] -->|插入文本| F[F]
```

