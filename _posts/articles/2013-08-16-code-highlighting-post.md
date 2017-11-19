---
layout: post
title: "code-highlighting-post"
excerpt: "Demo post displaying the various ways of highlighting code in Markdown."
categories: articles
tags: [sample-post, code, highlighting]
image:
  feature: so-simple-sample-image-5.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
comments: true
share: true
---

some text

'''some more text'''

### Node 8 Migration
<br>
<iframe height="650" width="100%" style="display: block !important; height: 650px !important; width: 100% !important; " scrolling="0" frameBorder="0" src="https://renderer.pe.apester.com/interaction/5a0d7760b3ca81000193b6b3"></iframe>
<br>
<iframe height="350" width="100%" style="display: block !important; height: 350px !important; width: 100% !important; " scrolling="0" frameBorder="0" src="https://renderer.pe.apester.com/interaction/5a115a54b3ca81000193b6d1"></iframe>
<br>
<iframe height="512" width="100%" style="display: block !important; height: 512px !important; width: 100% !important; " scrolling="0" frameBorder="0" src="https://renderer.pe.apester.com/interaction/59fae2037b9cb300014d11df"></iframe>
<br>
<iframe height="534" width="100%" style="display: block !important; height: 534px !important; width: 100% !important; " scrolling="0" frameBorder="0" src="https://renderer.pe.apester.com/interaction/5a115c5ab3ca81000193b6df"></iframe>
<br>
<iframe height="600" width="100%" style="display: block !important; height: 600px !important; width: 100% !important; " scrolling="0" frameBorder="0" src="https://renderer.pe.apester.com/interaction/5a115e25b3ca81000193b6e8"></iframe>
<br>
<iframe height="388" width="100%" style="display: block !important; height: 388px !important; width: 100% !important; " scrolling="0" frameBorder="0" src="https://renderer.pe.apester.com/interaction/5a115cb2b3ca81000193b6e4"></iframe>
<br>
### Pygments Code Blocks

To modify styling and highlight colors edit `/_sass/_pygments.scss`.

{% highlight css %}
#container {
    float: left;
    margin: 0 -240px 0 0;
    width: 100%;
}
{% endhighlight %}

{% highlight html %}
{% raw %}
<nav class="pagination" role="navigation">
    {% if page.previous %}
        <a href="{{ site.url }}{{ page.previous.url }}" class="btn" title="{{ page.previous.title }}">Previous article</a>
    {% endif %}
    {% if page.next %}
        <a href="{{ site.url }}{{ page.next.url }}" class="btn" title="{{ page.next.title }}">Next article</a>
    {% endif %}
</nav><!-- /.pagination -->
{% endraw %}
{% endhighlight %}

{% highlight ruby %}
module Jekyll
  class TagIndex < Page
    def initialize(site, base, dir, tag)
      @site = site
      @base = base
      @dir = dir
      @name = 'index.html'
      self.process(@name)
      self.read_yaml(File.join(base, '_layouts'), 'tag_index.html')
      self.data['tag'] = tag
      tag_title_prefix = site.config['tag_title_prefix'] || 'Tagged: '
      tag_title_suffix = site.config['tag_title_suffix'] || '&#8211;'
      self.data['title'] = "#{tag_title_prefix}#{tag}"
      self.data['description'] = "An archive of posts tagged #{tag}."
    end
  end
end
{% endhighlight %}


### Standard Code Block

    {% raw %}
    <nav class="pagination" role="navigation">
        {% if page.previous %}
            <a href="{{ site.url }}{{ page.previous.url }}" class="btn" title="{{ page.previous.title }}">Previous article</a>
        {% endif %}
        {% if page.next %}
            <a href="{{ site.url }}{{ page.next.url }}" class="btn" title="{{ page.next.title }}">Next article</a>
        {% endif %}
    </nav><!-- /.pagination -->
    {% endraw %}


### Fenced Code Blocks

To modify styling and highlight colors edit `/_sass/_coderay.scss`. Line numbers and a few other things can be modified in `_config.yml`. Consult [Jekyll's documentation](http://jekyllrb.com/docs/configuration/) for more information.

~~~ css
#container {
    float: left;
    margin: 0 -240px 0 0;
    width: 100%;
}
~~~

~~~ html
{% raw %}<nav class="pagination" role="navigation">
    {% if page.previous %}
        <a href="{{ site.url }}{{ page.previous.url }}" class="btn" title="{{ page.previous.title }}">Previous article</a>
    {% endif %}
    {% if page.next %}
        <a href="{{ site.url }}{{ page.next.url }}" class="btn" title="{{ page.next.title }}">Next article</a>
    {% endif %}
</nav><!-- /.pagination -->{% endraw %}
~~~

~~~ ruby
module Jekyll
  class TagIndex < Page
    def initialize(site, base, dir, tag)
      @site = site
      @base = base
      @dir = dir
      @name = 'index.html'
      self.process(@name)
      self.read_yaml(File.join(base, '_layouts'), 'tag_index.html')
      self.data['tag'] = tag
      tag_title_prefix = site.config['tag_title_prefix'] || 'Tagged: '
      tag_title_suffix = site.config['tag_title_suffix'] || '&#8211;'
      self.data['title'] = "#{tag_title_prefix}#{tag}"
      self.data['description'] = "An archive of posts tagged #{tag}."
    end
  end
end
~~~
