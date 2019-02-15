---
layout: page
title: "Get in touch with me?"
#subheadline: "Wufoo-powered contact forms"
#teaser: "Get in touch with me?"
permalink: "/contact/"
header:
    image_fullwidth: "contact-me.jpg"
---

<div id="wufoo-q8zydad0slfdu6"> Fill out my <a href="https://krupa93.wufoo.com/forms/q8zydad0slfdu6">online form</a>. </div> <script type="text/javascript"> var q8zydad0slfdu6; (function(d, t) { var s = d.createElement(t), options = { 'userName':'krupa93', 'formHash':'q8zydad0slfdu6', 'autoResize':true, 'height':'434', 'async':true, 'host':'wufoo.com', 'header':'show', 'ssl':true }; s.src = ('https:' == d.location.protocol ?'https://':'http://') + 'secure.wufoo.com/scripts/embed/form.js'; s.onload = s.onreadystatechange = function() { var rs = this.readyState; if (rs) if (rs != 'complete') if (rs != 'loaded') return; try { q8zydad0slfdu6 = new WufooForm(); q8zydad0slfdu6.initialize(options); q8zydad0slfdu6.display(); } catch (e) { } }; var scr = d.getElementsByTagName(t)[0], par = scr.parentNode; par.insertBefore(s, scr); })(document, 'script'); </script>

___
## Social media:
<p></p>
<ul class="inline-list social-icons">
{% for social_item in site.data.socialmedia%}
  <li><a href="{{ social_item.url }}" target="_blank" class="{{ social_item.class }}" title="{{ social_item.title }}"></a></li>
{% endfor %}
</ul>
