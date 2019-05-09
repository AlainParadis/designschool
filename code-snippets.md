https://www.shopify.ca/partners/shopify-cheat-sheet

# Code Snippets

I think this loops through all the pages' front matter by level. This is how the cards show on the course home pages by semester.

	{% for topic in site[page.level] %}
		{{topic.whatever}}	
	{% endfor %}

YAML Front Matter

---
deliverables:
  - first
  - second
  - third
---

Code on the page

<ul>
	{% for deliverable in page.deliverables %}
		<li>{{deliverable}}</li>
	{% endfor %}
</ul>

---------

## YAML Template

---
layout: default-nav
modulenumber: module1
module: Mac Setup
appsused: macos, indd, ai, psd, pdf, cc
title: 
level: cg1
course: Computer Graphics One
description: 
details: | 

img: 
deliverables:
  - 
video:
  - <a href="#" title="Video" target="_blank">Video</a>
---

{% if page.something == sometag %}
	<h4>Put some text here</h4>
{% elsif page.something == someothertag %}
	<h4>Put different text here.</h4>
{% endif %}
