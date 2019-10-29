| Name | Affiliation | 
|------|-------------|{% for member in site.data.participants %}
| {{ member.Name }} | {{ member.Affiliation }} |{% endfor %}
