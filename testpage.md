This is supposed to be a hidden page for tests

# Program

- 09h45-10h15 Welcome Coffee :coffee::cookie:
- 10h15-11h00 Talk by [Martin Benning](https://www.qmul.ac.uk/maths/profiles/benningmartin.html) *(Queen Mary University of London)*<br/>
  **Title**: Deep learning as optimal control problems<br/>
  <details>
  <summary><b>Abstract:</b> <i>(click to unroll)</i></summary>
  <p>
  We consider recent works where deep neural networks have been interpreted as discretisations of an optimal control problem subject to an ordinary differential equation constraint. We review the first order conditions for optimality, and the conditions ensuring optimality after discretisation. This leads to a class of algorithms for solving the discrete optimal control problem which guarantee that the corresponding discrete necessary conditions for optimality are fulfilled. The differential equation setting lends itself to learning additional parameters such as the time discretisation. We explore this extension alongside natural constraints (e.g. time steps lying in a simplex) and compare these deep learning algorithms numerically in terms of induced flow and generalisation ability. We conclude by addressing the interpretation of this extension as iterative regularisation methods for inverse problems. This is joint work with Elena Celledoni, Matthias J. Ehrhardt, Brynjulf Owren and Carola-Bibiane Schönlieb.
  </p>
  </details>
  
  
# test

<!-- Here we do a loop over the data registered in _data/program.yml by using Liquid for Jekyll -->
{% for event in site.data.program %}
{% if event.type == "talk" %}
- {{ event.time }} Talk by [{{ event.name }}]({{ event.web }}) *({{ event.affiliation }})*<br/>
  **Title**: {{ event.title }}<br/>
  <details>
  <summary><b>Abstract:</b> <i>(click to unroll)</i></summary>
  <p>{{ event.abstract }}</p>
  </details>
{% else %}
- {{ event.time }} {{ event.type }}
{% endif %}
{% endfor %}
