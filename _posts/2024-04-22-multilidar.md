---
layout: post
title: Multi-LiDAR Fusion with Translation and Rotation
subtitle: with Python, ROS-Noetic, Ubuntu
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/multi_lidar_fusion_post/thumb.jpg
share-img: /assets/img/path.jpg
gh-repo: shoxa-mir/MultiLiDAR_Transform_Fusion
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Shokhrukh Miraliev
---

### LiDAR Hardware Setup
<table style="max-width: 100%;">
    <tr>
        <th>Top view</th>
        <th>Side view</th>
    </tr>
    <tr>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig1/truck_w_lidar_top.svg" style="width: 100%;"></td>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig1/truck_w_lidar_side.svg" style="width: 100%;"></td>
    </tr>
</table>


### LiDAR Range and FOV (Top)
<table style="max-width: 100%;">
    <tr>
        <th>Top view</th>
    </tr>
    <tr>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig2/truck_w_range_top.svg" style="width: 100%;"></td>
    </tr>
</table>

### LiDAR Range and FOV (Side)
<table style="max-width: 100%;">
    <tr>
        <th>Side view</th>
    </tr>
    <tr>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig2/truck_w_range_side.svg" style="width: 100%;"></td>
    </tr>
</table>

{: .box-success}
This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/tables/etc.<br/>I also encourage you to look at the [code that created this post](https://raw.githubusercontent.com/daattali/beautiful-jekyll/master/_posts/2020-02-28-sample-markdown.md) to learn some more advanced tips about using markdown in Beautiful Jekyll.

**Here is some bold text**

## Here is a secondary heading

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

You can use [MathJax](https://www.mathjax.org/) to write LaTeX expressions. For example:
When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
