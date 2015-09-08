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

{% highlight text %}
위의 예 참고
  광고 예산 = input variable
  판매량 = output variable

input variable은 일반적으로 X로 표현, $X_1$은 TV budget, X2 the radio budget, and X3 the newspaper budget
inputs 은 여러 다른 이름을 가지고 있는데 predictors, independent variables, features, or sometimes just variables 등으로 불린다.
output variable(이 경우 판매량)은 response or dependent variable로 불리고 Y로 표현한다.
이 책에서는 이 용어를 사용할 것 이다.
{% endhighlight %}

요게 잘 나올까? $X_{1}$ ㅎㅎ   
$Y = f(x)$ 이건 어떻게??  

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

The *Gamma function* satisfying $\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$ is via through the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$


Processed by Jekyll into https://cben.github.io/sandbox/katex

KaTeX loaded in output via Jekyll template `_layouts/katex.html`.

Delimiters [recognized by kramdown](http://kramdown.gettalong.org/syntax.html#math-blocks):

inline $$ \frac{kram}{down} \sum_0^\infty $$ text.

$$ \frac{kram}{down} \sum_0^\infty $$

The second is display math because it occurs alone in a block.



You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.
![my photo]({{ site.baseurl }}/images/intro/f2.1.png "하하")
Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com



This is a test for $\KaTeX$, $a^2 + b^2 = c^2$, if you want it in display style, try: $$\text{e} = \lim_{n\to\infty} \left(1+\frac{1}{n}\right)^n,$$ and   

$$ \pi = \lim_{k=0}^\infty \, \frac{1}{16^k} \left( \frac{4}{8k+1} - \frac{2}{8k+4} - \frac{1}{8k+5} - \frac{1}{8k+6} \right).$$


