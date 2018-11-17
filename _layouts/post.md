---
layout: default
comments: true

---
<article class="post h-entry" itemscope itemtype="http://schema.org/BlogPosting">

  <header class="post-header">
    <h1 class="post-title p-name" itemprop="name headline">{{ page.title | escape }}</h1>
    <p class="post-meta">
      <time class="dt-published" datetime="{{ page.date | date_to_xmlschema }}" itemprop="datePublished">
        {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
        {{ page.date | date: date_format }}
      </time>
      {%- if page.author -%}
        • <span itemprop="author" itemscope itemtype="http://schema.org/Person"><span class="p-author h-card" itemprop="name">{{ page.author | escape }}</span></span>
      {%- endif -%}</p>
  </header>

  <div class="post-content e-content" itemprop="articleBody">
    {{ content }}
 
</article>
  </div>

  
 
  <div id="disqus_thread"></div>
<script>

var disqus_config = function () {
this.page.url =' https://reslow.disqus.com/embed.js';  
this.page.identifier = Comment; 
};

(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://reslow.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>

<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

  <a class="u-url" href="{{ page.url | relative_url }}" hidden></a>
  
  <script id="dsq-count-scr" src="//reslow.disqus.com/count.js" async></script>
         

 