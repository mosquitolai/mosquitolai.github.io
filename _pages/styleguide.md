---
layout: page
title: 製備過的物質
permalink: /styleguide/
image: 019.png
---

<center>"從2021年至今，我已經進行了許多實驗，包括無機、有機實驗以及滴定分析。這些實驗讓我有了實際的操作經驗，從中學習了許多化學反應的機制。"</center>

***

### Headings by default:

# This is the default title
## This is the default title
### This is the default title
#### This is the default title
##### This is the default title
###### This is the default title

{% highlight markdown %}
## Heading first level
### Heading second level
#### Heading third level
{% endhighlight %}

***

### Lists

#### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

***

#### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

{% highlight markdown %}
1. Order list item 1
2. Order list item 1

* Unordered list item 1
* Unordered list item 2
{% endhighlight %}

***

### Quotes

> Coming together is a beginning; keeping together is progress; working together is success. — Edward Everett Hale

***

### Syntax Highlighter

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

***

### Videos

<iframe src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe>

***

### Images

![]({{site.baseurl}}/images/09.jpg)
*Backyard*

***