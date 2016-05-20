---
layout: post
title:  "Using the EXPLAIN PLAN"
date:   2016-05-12 22:01:43 +0530
categories: jekyll update
---
The EXPLAIN PLAN statement displays execution plans chosen by the Oracle optimizer for SELECT, UPDATE, INSERT, and DELETE statements. A statement's execution plan is the sequence of operations Oracle performs to execute the statement.

{% highlight sql %}
explain plan for 
--place the sql query here
{% endhighlight %}

If successful the Script Output will display:
{% highlight sql %}
Plan FOR succeeded.
{% endhighlight %}


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
