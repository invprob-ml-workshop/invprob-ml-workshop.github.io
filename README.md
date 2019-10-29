Welcome to the website of the one-day workshop "[Regularisation for Inverse Problems and Machine Learning](https://invprob-ml-workshop.github.io/)", which will be held at the [Campus Jussieu](https://goo.gl/maps/AgoULSsBeL2beaZo7) (room 16-26-209) in Paris on November 19th 2019.

---------------------------
*Due to room limitations, **the inscriptions are now CLOSED**. If you already registered but cannot attend the event, please let us know [here](https://forms.gle/oHhtxUnshMk8uNfUA).* 

---------------------------

## What is this workshop about

The purpose of the workshop is to gather together people working on problems arising in different fields such as imaging, machine learning and inverse problems theory in order to underline similarities and differences of the regularisation approaches used  (Tikhonov, early stopping, implicit regularization...).


## Program

All the talks will be held in the room 16-26-209. Coffee breaks and lunch will be organized in the room 15-25-202.

{% include program.md %}


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

![](assets/images/guests2.png)

## Location

The workshop will be held at the Campus Jussieu in Paris.

Finding Jussieu in Paris  |  Finding the workshop in Jussieu
:---------------------------:|:-------------------------:
[<img src="/assets/images/plan-paris.png">](https://goo.gl/maps/AgoULSsBeL2beaZo7) |  ![](assets/images/plan-jussieu.png)

<br/>

- [Jussieu](https://goo.gl/maps/AgoULSsBeL2beaZo7) can be accessed via the Metro lines 7 and 10. Line 7 connects to the RER B (Gare du Nord, Airport Charles de Gaulle) at Châtelet.
- In Jussieu, get to the 2nd floor by taking the stairs/elevator through the (numbered) towers. Talks will be in the room 209 (between towers 16-26), coffee and lunch will be served in room 202 (15-25).

## Organization

- [Luca Calatroni](https://sites.google.com/view/lucacalatroni/home) (calatroni 'at' i3s.unice.fr) Chargé de Recherche (CNRS) à  l'Université Nice Sophia Antipolis.
- [Guillaume Garrigos](http://www.guillaume-garrigos.com/) (guillaume.garrigos 'at' lpsm.paris) Maître de Conférences à l'Université de Paris.

## Support

This workshop is supported by the CNRS through the INSMI PEPS JCJC project "Efficient iterative regularization for inverse problems and machine learning" (EFIR), and the [GdR Mathématiques de l'Optimisation et Applications](http://gdrmoa.math.cnrs.fr/).

![](assets/images/support_logo3.png)

## Registration

Due to room limitations, the inscriptions are now closed. 

## List of Participants

| Name | Affiliation | 
|------|-------------|{% for member in site.data.participants %}
| {{ member.Name }} | {{ member.Affiliation }} |{% endfor %}

