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
<div class="apester-media" data-media-id="5a12a34f442ae0000140cdf3" height="512"></div><script async src="//static.apester.com/js/sdk/v2.0/apester-javascript-sdk.min.js"></script>
<br>


Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

{% highlight html %}

{% endhighlight %}

And here's a Vimeo embed for testing purposes.


