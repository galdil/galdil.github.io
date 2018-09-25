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
<div class="apester-media" data-media-id="5ba3add7a7215877b9344d0c" data-player="true" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### quiz new player
<br>
<div class="apester-media" data-media-id="5baa2c53d7a74ce6db226feb" data-player="true" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
### story new player
<br>
<div class="apester-media" data-media-id="5ba3aecea7215861de344d14" data-player="true" height="512"></div><script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
<br>
<figure>

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
