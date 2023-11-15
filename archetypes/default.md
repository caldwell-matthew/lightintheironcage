+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
layout = 'single'
tags = ['Quotes', 'Tags']
author = ["Matthew Caldwell"]

[cover]
image = "img/space.jpg"
alt = "<alt text>"
caption = "<text>"
relative = false
+++

> Stuff

---

Thoughts.  
-- Matthew

<script>
var refTagger = {
  settings: {
    bibleVersion: 'ESV',
			tooltipStyle: 'dark'
  }
}; 

(function(d, t) {
  var n=d.querySelector('[nonce]');
  refTagger.settings.nonce = n &amp;&amp; (n.nonce||n.getAttribute('nonce'));
  var g = d.createElement(t), s = d.getElementsByTagName(t)[0];
  g.src = 'https://api.reftagger.com/v2/RefTagger.js';
  g.nonce = refTagger.settings.nonce;
  s.parentNode.insertBefore(g, s);
}(document, 'script'));
</script>