<!-- Here we do a loop over the data registered in _data/program.yml by using Liquid for Jekyll -->
{% for event in site.data.program %}{% if event.type == "talk" %}
- {{ event.time }} Talk by [{{ event.name }}]({{ event.web }}) *({{ event.affiliation }})*<br/>
  **Title**: {{ event.title }}<br/>
  <details>
  <summary><b>Abstract:</b> <i>(click to unroll)</i></summary>
  <p>{{ event.abstract }}</p>
  </details>
{% else %}
- {{ event.time }} {{ event.type }}<br/>
{%- endif -%}{% endfor %}
