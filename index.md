---
title       : 
subtitle    : 
author      : 
job         : 
framework   : RevealJS       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
revealjs:
  theme:  Sky
github:
  user: wussrs
  repo: selfmade1
---

##  [QM指标研究阶段性报告](http://www.questmobile.com.cn/)

邬贤达

---

<img src="表格.png" width="60%">

数据：21个行业的前20个APP（6月—7月）

---

## __研究内容__

* 指标相关性检验：对指标进行筛选

* 指标之间体现的市场规律

* 分析ios和Android两个市场差异

* 构建评价APP价值的指标：体现App真实价值、增长潜力

---

## 指标相关性检验

* 1、指标简单分类：按照含义相似的指标归为一类
* 2、计算指标之间的相关系数
* 3、相关系数高的指标进行筛选

---

### 活跃指标

.fragment 问题：日均活跃用户数、月活跃用户数哪个更有代表性？

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1-1.png)

---

### 移动互联网特点

* 1、数据很难进行造假

* 2、相比PC互联网更加透明

* 3、流量互导骗钱的做法很难复制

* 4、产品更易老化，所以更考验创新

---

### 留存指标

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png)

留存N日后 = 每日新安装用户数/第N日启动应用的用户数

---

### 次数指标

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3-1.png)

保留日均使用次数、人均使用次数指标

---

###	时长指标

![plot of chunk unnamed-chunk-4](figure/unnamed-chunk-4-1.png)

保留日均使用时长、人均单次使用时长、人均使用时长指标

---

###	市场规律性研究

* 1、APP下载情况(卸载、留存、下载、新安装)

* 2、用户使用情况(DAU、日均使用次数、日均使用时长)

* 3、人均使用情况(人均使用次数、人均使用时长)

![plot of chunk unnamed-chunk-5](figure/unnamed-chunk-5-1.png)

--- .class #id 

###	APP下载情况

<iframe src="下载用户数与卸载用户数.html" width=960 height=600 allowtransparency="true"> </iframe>



--- .class #id

## APP下载情况

* 1、下载量高，卸载量必定会高。这是无法避免的

* 2、APP价值的关注点转向__留存用户数__

> - (留存用户数≈下载用户数-卸载用户数)

--- .class #id 

### 用户使用次数

<iframe src="DAU与日均使用次数.html" width=960 height=600 allowtransparency="true"> </iframe>

--- .class #id 

### 用户使用时长

<iframe src="DAU与日均使用时长.html" width=960 height=600 allowtransparency="true"> </iframe>

--- .class #id 

## talking data 观测数据

![](talkingdata.png) 

--- .class #id 

#### DAU = 24 + 0.19*日均使用次数 - 0.006*日均使用时长

<iframe src="DAU与日均使用次数线性关系.html" width=960 height=600 allowtransparency="true"> </iframe>

.fragment 问题：__时长、次数的体现__：日均使用时长、日均使用次数？


--- .class #id 

### 用户行为习惯的体现：次数

<iframe src="人均使用次数top10.html" width=960 height=600 allowtransparency="true"> </iframe>

--- .class #id 

###  用户行为习惯的体现：时长

<iframe src="人均使用时长top10.html" width=960 height=600 allowtransparency="true"> </iframe>



--- .class #id 

## 

人均使用次数和人均使用时长无线性关系

<iframe src="人均使用次数与人均使用时长.html" width=960 height=600 allowtransparency="true"> </iframe>


--- .class #id 

## APP使用情况

* 日均使用时长、次数与DAU关联性强，不能作为时长、次数的衡量指标

* 时长，次数实际上体现在__人均使用次数__，__人均使用时长上__


--- .class #id 

##  IOS和Andriod端的差异性

(__比较6月—7月指标增长率变化__)

* <big>APP总体价值：DAU</big>
* <big>用户行为习惯的指标：人均使用次数、人均使用时长</big>

--- .class #id 

## DAU的趋势变化


* KS检验：DAU增长率变化不相同
* Andriod端DAU的波动性要远大于IOS端


<iframe src="DAU趋势变化.html" width=800 height=500 allowtransparency="true"> </iframe>



--- .class #id 

## 用户行为习惯的指标

* KS检验：增长率变化相同
* 两个市场用户行为习惯相同

![](增长率.jpeg) 


--- .class #id 

## IOS和Andriod端的市场差异

* IOS端的DAU增长更加__稳定__
* 两个市场的用户的行为习惯__一致__的


--- .class #id 

##  评价APP价值的指标

*  DAU（总体价值）

*  留存用户数、留存转化率（用户粘性）

* 人均使用次数、人均使用时长（用户行为习惯）

* MAU环比增长率（新秀APP）

* N日新安装留存率（萌芽期、上升期、稳定期、衰退期）




