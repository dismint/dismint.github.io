---
layout: minimal
title: Reliability
parent: 61800
---

# Reliability

For example, suppose we have the code as follows
```python
def reliable(var):
  var += 10
  return var
```
In this case it is abundantly clear that this is not the case

This is very impotant
{: .warning }

Honestly I hope this text comes out relatively nice

def reliable(var):
  var += 10
  return var

{% capture some_var %}
{% highlight python linenos %}
def reliable(var):
  var += 10
  return var
{% endhighlight %}
{% endcapture %}
{% include fix_linenos.html code=some_var %}
