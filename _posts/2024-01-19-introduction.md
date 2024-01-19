---
layout: post
title:  "My introduction"
date:   2024-01-19 16:45:00 +0100
---

This is my post.
Here you can see the today's picture:
![Image test 2]({{ 'assets/images/todaysheadlinesheader.png' | relative_url }})

Useful links:
1. [Nice Jekyll-based blog](https://tseknet.com/blog/startblogging)
2. [The source code for this blog](https://github.com/TsekNet/website/tree/master)

Example Java code:
```java
class Main {

    public static void main(String[] args) {

        int first = 10;
        int second = 20;

        // add two numbers
        int sum = first + second;
        System.out.println(first + " + " + second + " = "  + sum);
    }
}
```

Example of Python code:
{% highlight python linenos %}
def Nmaxelements(list1, N):
final_list = []

    for i in range(0, N):
        max1 = 0
 
        for j in range(len(list1)):
            if list1[j] > max1:
                max1 = list1[j]
 
        list1.remove(max1)
        final_list.append(max1)
 
    print(final_list)
{% endhighlight %}