https://www.shopify.ca/partners/shopify-cheat-sheet

# Code Snippets

I think this loops through all the pages' front matter by level. This is how the cards show on the course home pages by semester.

	{% for topic in site[page.level] %}
		{{topic.whatever}}	
	{% endfor %}

YAML Front Matter

---
### Liquid Loop

deliverables:
  - first
  - second
  - third

<ul>
	{% for deliverable in page.deliverables %}
		<li>{{deliverable}}</li>
	{% endfor %}
</ul>

---

{% if page.something == sometag %}
	<p>Put some text here</p>
{% elsif page.something == someothertag %}
	<p>Put different text here.</p>
{% endif %}

### CSS

- Select ALL direct Decendants
  - .selector >* { attributes:something; }

- Set a container to 100% height of the browser
  - height:100vh;

### Grid

- To make columns responsive
  - grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));

### Emmet

- To make repeating div contents
  - div.item*30.item$*30{$}*30
