# svg

## svg打开方式

> * 浏览器直接打开
> * 插入到HTML代码中
> * 可以放在img标签
> * 可以用于background-image: url(demo.svg)

## 基本图形和属性

### 基本图形
rect、circle、ellipse、line、polyline、polygon

* path是高级图形

### 基本属性
fill、stroke、stroke-width、transform

## 矩形（rect）

![rect](img/rect.png)

rx、ry如果只给某一个值，那么rx=ry（默认）

## 圆（circle）

![circle](img/circle.png)

cx、cy是根据圆心为标准

## 直线（line）

![line](img/line.png)

## 折线（polyline）

![polyline](img/polyline.png)

## 多边形（polygon）

![polygon](img/polygon.png)

## 填充、描边和变换

![other](img/other.png)

# 基本操作API

## 创建图形

document.createElementNS(ns, tagName)

## 添加图形

document.appendChild(childElement)

## 设置/获取属性

element.setAttribute(name, value)

element.getAttribute(name)









