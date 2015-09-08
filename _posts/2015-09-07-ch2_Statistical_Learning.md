---
layout: post
title:  "2장 Statistical Learning"
date:   2015-09-07 20:00:00
---


Statistical Learning에 대한 기본 개념 설명

#### 2.1 What Is Statistical Learning?
* TV, radio, and newspaper 로 어떤 제품을 광고한다고 할 때 어떻게 해야 판매량을 가장 많이 증가할 수 있을까?
* advertising and sales의 관계를 알면 적적하게 광고 예산을 편성할 수 있고, 간접적으로 판매량을 증가시킬 수 있다.
    * In other words, our goal is to develop an accurate model that can be used to predict sales on the basis of the three media budgets.
* inputs 은 여러 다른 이름을 가지고 있는데 predictors, independent variables, features, or sometimes just variables 등으로 불린다.

![TV, RADIO, NEWSPAPER 판매량]({{ site.baseurl }}/images/intro/f2.1.png "TV, RADIO, NEWSPAPER 판매량")


* 용어 설명
  * 광고 예산 = input variable
  * 판매량 = output variable
  * input variable은 일반적으로 X로 표현, $X\_1$은 TV budget, $X\_2$ the radio budget, and $X\_3$ the newspaper budget 
  * inputs 은 여러 다른 이름을 가지고 있는데 predictors, independent variables, features, or sometimes just variables 등으로 불린다.
  * output variable(이 경우 판매량)은 response or dependent variable로 불리고 Y로 표현한다.
  * 이 책에서는 이 용어를 사용할 것 이다.

quantitative response $Y$와 $p$ different predictors, $X\_1, X\_2, . . . , X\_p$사이에는 아래 함수와 같은 관계가 있다고 가정한다.  
$$Y = f(X) + \epsilon$$
f는 $X\_1, X\_2, . . . , X\_p$의 알려지지 않은 함수이고 $\epsilon$는 *error term*이다.
f는 input variable 에서 output variable 을 연결하는 알려지지 않은 함수, 실제 세계에서 입력변수와 출력변수의 관계는 알 수 없음.(대략 추정할 뿐이지 수학적으로 완벽히 모른다는 의미)
이런 상황에서 f는 관찰되는 것에 의해 추정한다.

`In essence, statistical learning refers to a set of approaches for estimating f.` In this chapter we outline some of the key theoretical concepts that arise in estimating f, as well as tools for evaluating the estimates obtained.

* `statistical learning은 f를 추정하기위한 접근의 집합을 말한다.`

##### 2.1.1 Why Estimate $f$   ?
$f$를 추정하려고하는 2가지 주요한 이유가 *prediction* and *inference* 이다.






##### 2.1.2 How Do We Estimate $f$   ?
그럼 이제 어떻게 $f$를 추정하는지에 대해 설명한다.







##### 2.1.3 The Trade-Off Between Prediction Accuracy and Model Interpretability


##### 2.1.4 Supervised Versus Unsupervised Learning


##### 2.1.5 Regression Versus Classification Problems


#### 2.2 Assessing Model Accuracy

##### 2.2.1 Measuring the Quality of Fit

##### 2.2.2 The Bias-Variance Trade-Off

##### 2.2.3 The Classification Setting

####2.3 Lab: Introduction to R

##### 2.3.1 Basic Commands

##### 2.3.2 Graphics

##### 2.3.3 Indexing Data

##### 2.3.4 Loading Data

##### 2.3.5 Additional Graphical and Numerical Summaries








