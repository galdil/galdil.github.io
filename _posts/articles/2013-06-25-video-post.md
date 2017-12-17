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
<div class="apester-media" data-media-id="5a36388e89ec5a00017ea1f1" height="373"></div><script async src="//static.apester.com/js/sdk/v2.0/apester-javascript-sdk.min.js"></script>
<br>
<div class="apester-media" data-media-id="5a36394e2918dd00018c6935" height="600"></div><script async src="//static.apester.com/js/sdk/v2.0/apester-javascript-sdk.min.js"></script>
<br>
<div class="apester-media" data-media-id="5a3639b2da30dd0001e04cd3" height="512"></div><script async src="//static.apester.com/js/sdk/v2.0/apester-javascript-sdk.min.js"></script>
<br>
<div class="apester-media" data-media-id="5a3644b889ec5a00017ea209" height="373"></div><script async src="//static.apester.com/js/sdk/v2.0/apester-javascript-sdk.min.js"></script>
<br>
<div class="apester-media" data-media-id="5a3645212918dd00018c6943" height="352"></div><script async src="//static.apester.com/js/sdk/v2.0/apester-javascript-sdk.min.js"></script>
<br>
Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

{% highlight html %}

{% endhighlight %}

And here's a Vimeo embed for testing purposes.


