---
layout: post
title: "video-post"
excerpt: "Custom written post descriptions are the way to go... if you're not lazy."
categories: articles
tags: [sample-post, video]
comments: true
share: true
---
<br>
<br>
<div class="apester-media" data-media-id="5a0c5532f530ab0001475e94" height="350"></div><script async src="https://static3.apester.com"></script>
<br>
<br>
Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

{% highlight html %}

{% endhighlight %}

And here's a Vimeo embed for testing purposes.


