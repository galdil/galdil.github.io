---
layout: post
title: "sample-post-images"
excerpt: "Examples and code for displaying images"
categories: articles
tags: [sample-post, images, test]
comments: true
share: true
---
## Figures (for images or video)

### Poll new player
<br>
<div class="apester-media" data-media-id="5bb9cc4af185fdc839c87cb4" data-player="true" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### small size Poll new player
<br>
<div class="apester-media" data-media-id="5bb9d2bbf185fdb70ac87cdd" data-player="true" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### quiz new player
<br>
<div class="apester-media" data-media-id="5bb9cc99f185fd0399c87cbb" data-player="true" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### story new player
<br>
<div class="apester-media" data-media-id="5bb9cdfbf185fd7d9dc87cbe" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### personality old player
<div class="apester-media" data-media-id="5bdb24c70a28a10dc9d4b444" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### article old player
<div class="apester-media" data-media-id="5be81b74d9d1eac348077451" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### countdown old player
<div class="apester-media" data-media-id="5be81c98d9d1eaaebe077458" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg"><img src="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg" alt="image"></a>
	<figcaption><a href="http://www.flickr.com/photos/80901381@N04/7758832526/" title="Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr">Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr</a>.</figcaption>
</figure>

### Two Up



Apply the `half` class like so to display two images side by side that share the same caption.

{% highlight html %}
<figure class="half">
	<img src="/images/image-filename-1.jpg" alt="image">
	<img src="/images/image-filename-2.jpg" alt="image">
	<figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<img src="http://placehold.it/600x300.jpg" alt="image">
	<img src="http://placehold.it/600x300.jpg" alt="image">
	<figcaption>Two images.</figcaption>
</figure>

### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

{% highlight html %}
<figure class="third">
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<figcaption>Caption describing these three images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="third">
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<a href="http://placehold.it/1200x600.jpg"><img src="http://placehold.it/600x300.jpg" alt="image"></a>
	<figcaption>Three images.</figcaption>
</figure>
