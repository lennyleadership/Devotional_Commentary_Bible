+++
title = "Bible Verse Tooltip Demo"
description = ""
tags = [

]
date = "2022-08-13"
categories = [
]
menu = "main"
+++


## Option #1 refTagger
```
<script>
	var refTagger = {
		settings: {
			bibleVersion: "hlybblsmpshndtn" /*'KJV'*/
		}
	}; 

	(function(d, t) {
		var n=d.querySelector('[nonce]');
		refTagger.settings.nonce = n && (n.nonce||n.getAttribute('nonce'));
		var g = d.createElement(t), s = d.getElementsByTagName(t)[0];
		g.src = 'https://api.reftagger.com/v2/RefTagger.js';
		g.nonce = refTagger.settings.nonce;
		s.parentNode.insertBefore(g, s);
	}(document, 'script'));
</script>

<cite class="bibleref" title="" ></cite> 


Example #1：Obadiah 1:3

Example #2：<cite class="bibleref" title="Psalms 48:1-14" >诗四十八</cite>

```
<script>
	var refTagger = {
		settings: {
			bibleVersion: "hlybblsmpshndtn" /*'KJV'*/
		}
	}; 

	(function(d, t) {
		var n=d.querySelector('[nonce]');
		refTagger.settings.nonce = n && (n.nonce||n.getAttribute('nonce'));
		var g = d.createElement(t), s = d.getElementsByTagName(t)[0];
		g.src = 'https://api.reftagger.com/v2/RefTagger.js';
		g.nonce = refTagger.settings.nonce;
		s.parentNode.insertBefore(g, s);
	}(document, 'script'));
</script>

Example #1：Obadiah 1:3

Example #2：<cite class="bibleref" title="Psalms 48:1-14" >诗四十八</cite>



## Option #2 bible-link

```
<script async defer src="https://bible-link.globalrize.org/plugin.js" data-translation="kjv"></script>

<span class="bible-link" data-translation="kjv">Romans 8:38-39</span>
```

Example #3: <span class="bible-link" data-translation="kjv">Romans 8:38-39</span>

<script async defer src="https://bible-link.globalrize.org/plugin.js" data-translation="kjv"></script>