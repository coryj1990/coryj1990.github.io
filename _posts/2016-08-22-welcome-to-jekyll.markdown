---
layout: post
title:  "Working with _posts in Jekyll"
date:   2016-08-22 09:19:35 -0500
categories: jekyll update
---
So far in working with Jekyll I haven't had to use any specific coding languages to make these pages
come to life. I may have only looked at what Jekyll does in the last few days before starting this 
example up, but I would expect to find some place in the file structure, similar to a model folder in rails,
soon. I would find it hard to believe if this product doesn't have some form of logic somewhere. A few other 
things I am impressed by are the auto regenerations of edited files will appear by refreshing that
page with no requirement to restart the server. Another feature is the _layouts. From what I have read it is 
implied that the content above and below this are stored somewhere in the file structure. Previously I worked 
with not as intuitive frameworks which did seperate the main page's materail from a heading or menu, but I look forward to investigating where and how I can adjust the page content. An example of showing ruby code is below.


{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
