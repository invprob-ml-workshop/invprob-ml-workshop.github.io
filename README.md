Welcome to the website of the one-day workshop "[Regularisation for Inverse Problems and Machine Learning](https://invprob-ml-workshop.github.io/)", which will be held at the [Campus Jussieu](https://goo.gl/maps/AgoULSsBeL2beaZo7) (room 16-26-209) in Paris on November 19th 2019.

---------------------------
*Please notice that attendance to the workshop (including lunch) is free of charge, but registration is **mandatory** (you can register [here](#registration)).*

---------------------------

## What is this workshop about

The purpose of the workshop is to gather together people working on problems arising in different fields such as imaging, machine learning and inverse problems theory in order to underline similarities and differences of the regularisation approaches used  (Tikhonov, early stopping, implicit regularization...).


## Program

All the talks will be held in the room 16-26-209. Coffee breaks and lunch will be organized in the room 15-25-202

- 09h45-10h15 Welcome Coffee :coffee::cookie:
- 10h15-11h00 Talk by [Martin Benning](https://www.qmul.ac.uk/maths/profiles/benningmartin.html) *(Queen Mary University of London)*<br/>
  **Title**: Deep learning as optimal control problems<br/>
  <details>
  <summary><b>Abstract:</b> <i>(click to unroll)</i></summary>
  <p>
  We consider recent works where deep neural networks have been interpreted as discretisations of an optimal control problem subject to an ordinary differential equation constraint. We review the first order conditions for optimality, and the conditions ensuring optimality after discretisation. This leads to a class of algorithms for solving the discrete optimal control problem which guarantee that the corresponding discrete necessary conditions for optimality are fulfilled. The differential equation setting lends itself to learning additional parameters such as the time discretisation. We explore this extension alongside natural constraints (e.g. time steps lying in a simplex) and compare these deep learning algorithms numerically in terms of induced flow and generalisation ability. We conclude by addressing the interpretation of this extension as iterative regularisation methods for inverse problems.This is joint work with Elena Celledoni, Matthias J. Ehrhardt, Brynjulf Owren and Carola-Bibiane Schönlieb.
  </p>
  </details>
- 11h00-11h45 Talk by Silvia Villa *(Universitá di Genova)*
  **Title**: Stability and regularization properties of diagonal proximal gradient methods
  <details>
  <summary><b>Abstract:</b> <i>(click to unroll)</i></summary>
  <p>
  Many applied problems in science and engineering can be modeled as noisy inverse problems. Tackling these problems requires to dealwith their possible ill-posedness and to devise efficient numerical procedures to quickly and accurately compute a solution.In this context, Tikhonov regularization is a classical approach. A solution is defined by the minimization of an objective function beingthe sum of two terms: a data-fit term and a regularizer ensuring stability. However, in practice, finding the best Tikhonov regularized solutionrequires specifying a regularization parameter determining the trade-off between data-fit and stability.   From a numerical perspective,this can dramatically increase  the computational costs to find a good solution.In this talk, I will present an alternative approach based on iterative regularization techniques. The latter are classical regularization methods basedon the observation that stopping an iterative procedure corresponding to the minimization of an empirical objective has a self-regularizing property.Crucially, the number of iterations becomes the regularization parameter, and hence controls at the same time the accuracy of the solution aswell as the computational complexity of the method, making parameter tuning numerically efficient and iterative regularization an alternative toTikhonov regularization. I will present  general iterative regularization methods allowing to consider large classes of data-fit terms and regularizers,based on proximal and gradient descent steps. The proposed analysis establishes convergence as well as stability results.
  </p>
  </details>
- 12h30-14h00 Lunch (Buffet) :fork_and_knife::hamburger:
- 14h00-14h45 Talk by Lorenzo Rosasco *(LCSL, Universitá di Genova, MIT, IIT)*<br/>
  **Title**: TBA 
- 14h45-15h30 Talk by Marie-Caroline Corbineau *(CentraleSupélec, Université Paris-Saclay)*<br/>
  **Title**: TBA 
- 15h30-16h00 Coffee break :coffee:
- 16h00-16h45 Talk by Gilles Blanchard *(Université Paris-Sud, Université Paris-Saclay)*<br/>
  **Title**: TBA 

## Location

The workshop will be held at the Campus Jussieu in Paris.

Finding Jussieu in Paris  |  Finding the workshop in Jussieu
:---------------------------:|:-------------------------:
[<img src="/assets/images/plan-paris.png">](https://goo.gl/maps/AgoULSsBeL2beaZo7) |  ![](assets/images/plan-jussieu.png)

<br/>

- [Jussieu](https://goo.gl/maps/AgoULSsBeL2beaZo7) can be accessed via the Metro lines 7 and 10. Line 7 connects to the RER B (Gare du Nord, Airport Charles de Gaulle) at Châtelet.
- In Jussieu, get to the 2nd floor by taking the stairs/elevator through the (numbered) towers. Talks will be in the room 209 (between towers 16-26), coffee and lunch will be served in room 202 (15-25).


## Registration

Please use the form below to register. If you encounter any issues, you can instead use this [link](https://docs.google.com/forms/d/e/1FAIpQLScLQ1fnfXiqSfhNNlLi9YM4WdvArePn_cu-IC-Qb0kvvJhD8A/viewform?usp=sf_link).

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScLQ1fnfXiqSfhNNlLi9YM4WdvArePn_cu-IC-Qb0kvvJhD8A/viewform?embedded=true" width="640" height="982" frameborder="0" marginheight="0" marginwidth="0">Chargement…</iframe>

## Organization

- [Luca Calatroni](https://sites.google.com/view/lucacalatroni/home) (calatroni 'at' i3s.unice.fr)
- [Guillaume Garrigos](http://www.guillaume-garrigos.com/) (guillaume.garrigos 'at' lpsm.paris)

This workshop is supported by the CNRS through the INSMI PEPS JCJC "Efficient iterative regularization for inverse problems and machine learning" (EFIR).
