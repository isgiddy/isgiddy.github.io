---
layout: post
title:  "How waves modify TKE in surface boundary layers"
date:   2025-03-25 
categories: 
        - research
---

Wind stress at the ocean surface transfers momentum into the ocean surface boundary layer. It also forces the creation of waves. Waves themselves break and transfer momentum into the ocean. An interesting interaction between the wind driven current and the wave driven current, known as Stokes drift, results in the formation of Langmuir cells and Langmuir turbulence. Langmuir cells are counter-rotating vortices in the near surface ocean that are aligned with the direction of the wind. Their presence is often seen in the ocean as parallel convergence lines of foam or seaweed.{% sidenote 'one' '[Langmuir, 1938](http://www.doi.org/10.1126/science.87.2250.119)'%}, 

So, Langmuir cells modify the organisation of flow in the upper ocean. But also the distribution of turbulence kinetic energy. 

In this work, we use observations of the turbulence dissipation rate of TKE and realistically forced simulations of the surface boudnary layer in the Southern Ocean to start to unpack how wind-wave interactions modify TKE. 

## The formation of Langmuir Cells

The schematic below gives an idea of how Langmuir Cells are formed when vertical vorticity is tilted to the horizontal due to Stokes drift.{% sidenote 'two' '[Craik & Leibovich, 1976](http://www.doi.org/10.1017/S0022112076001420)'%} <br>
<br>

{% maincolumn 'assets/img/waves/formation_of_langmuir_cells.png' '“Schematic depicting the interaction between winds and waves and the formation of Langmuir cells and Langmuir turbulence, Isabelle Giddy”'%}

The presence of Langmuir turbulence tends to enhance turbulence in the ocean 
{% sidenote 'three' '[Mcwilliams et al, 1997](https://doi.org/10.1017/S0022112096004375), [DAsaro et al., 2014](https://doi.org/10.1002/2013GL058193)'%} when winds and waves are aligned, thus being an important component of the energetic balance in the surface boundary layer. However, this enhanced turbulence is not always observed. A number of studies show that predictions of turbulence dissipation based on a shear production model that only takes into account wind stress well-represents observations, with wave adjusted models at times explaining less of the variability {% sidenote 'four' '[Esters et al., 2018](https://doi.org/ 648
10.1002/2017JC013525), [Ferris et al., 2022](https://doi.org/10.1175/JPO-D-21-0015.1), [Miller et al., 2023](https://doi.org/10.1029/2022JC018901)'%}. 

## The TKE budget under wave forcing compared to wind forcing
<br><br>

{% maincolumn 'assets/img/waves/tke_budget.png' '“Nondimensional TKE budget at 0.1h (upper 10% of the boundary layer) plotted against the stability parameter, $$\zeta$$ a) No wave forcing and b) wave forcing", *Giddy et al., 2025, under review*'%}

Under pure wind conditions, vertical shear accounts for the local dissipation of TKE. However, when waves are also included, the Eulerian vertical shear component is reduced and replaced with a Stokes shear component. We also see that the transport of TKE becomes non-negligible.

## How this compares to observations

When we compare a wind-driven shear only model for dissipation with a wind-wave model for dissipation we find similar fits (with a slight improvement when using the wind-wave model). This finding suggests that due to compensating effects and non-local dissipation (as seen in the TKE budget), observations may indeed agree with a wind-driven shear only model (e.g. the Law of the wall), but this model does not represent the underlying physics. <br><br>

{% maincolumn 'assets/img/waves/obs_models.png' '“Observed dissipation compared to two models. Left, the Law of the Wall and right, a modified Law of the Wall including: a linear decay of momentum stress, the interaction between stokes drift and the wind-driven Eulerian current and a turbulent transport term", *Giddy et al., 2025, under review*'%}


*This paper is currently under review with the Journal of Physical Oceanography*


<!-- 
Some edge cases and cautionary examples on using Markdown for writing content using this theme. In particular, list syntax can really knot things up. -->


<!-- 
### Mathjax improperly parsing greater and less than and ampersands inside blocks

The mathjax HTML ```<head>``` scripts have been modified to properly render block style mathjax expressions inside a ```$$ ... $$``` set of character pairs,
using the standard Kramdown parser. Some examples sent to me by Quxiaofeng are now parsing correctly, I believe.

This code:

```latex
$$
  D = \left(\begin{matrix}
  1 & -1 & & & & \\
  &    & \cdots &   & \\
  &    &        & 1 & -1
 \end{matrix}
 \right)
$$
```
yields this:

$$
D = \left(\begin{matrix}
  1 & -1 & & & & \\
  &    & \cdots &   & \\
  &    &        & 1 & -1
\end{matrix}
\right)
$$

Other examples from the [wikia Tex reference](http://latex.wikia.com/wiki/Matrix_environments):

$$
\begin{matrix}
\alpha& \beta^{*}\\
\gamma^{*}& \delta
\end{matrix}
$$


$$
\begin{bmatrix}
\alpha& \beta^{*}\\
\gamma^{*}& \delta
\end{bmatrix}
$$

$$
\begin{Bmatrix}
\alpha& \beta^{*}\\
\gamma^{*}& \delta
\end{Bmatrix}
$$

$$
\begin{vmatrix}
\alpha& \beta^{*}\\
\gamma^{*}& \delta
\end{vmatrix}
$$

$$
\begin{Vmatrix}
\alpha& \beta^{*}\\
\gamma^{*}& \delta
\end{Vmatrix}
$$

$$
\begin{Vmatrix}
\alpha& \beta^{*}\\
\gamma^{*}& \delta
\end{Vmatrix}
$$

However, a problem still exists for inline matrix notation, from an example [here](https://en.wikibooks.org/wiki/LaTeX/Mathematics#Matrices_in_running_text):

A matrix in text must be set smaller: $$ \bigl(\begin{smallmatrix}a & b \\ c & d\end{smallmatrix} \bigr) $$ to not increase leading in a portion of text. The way this inline matrix is written is: ```$$ \bigl(\begin{smallmatrix}a & b \\ c & d\end{smallmatrix} \bigr) $$```

## Edge Case 1 from Quxiaofeng:

### No blank lines between Markdown list items

The issue arises when sidenotes and marginnotes are put into list items.  As mentioned in the main documentation page, lists can be problematic not only for semantic clarity, but also because they can creating formatting issues. For example:

### Related algorithms

+ Split Bregman iteration {% sidenote 1 'Goldstein, T. and Osher, S. (2009). The split Bregman method for l1-regularized problems. SIAM J. Img. Sci., 2:323-343.' %}
+ Dykstra's alternating projection algorithm {% sidenote 2 'Dykstra, R. L. (1983). An algorithm for restricted least squares regression. J. Amer. Statist. Assoc., 78(384):837-842.' %}
+ Proximal point algorithm applied to the dual
+ Numerous applications in statistics and machine learning: lasso, gen. lasso, graphical lasso, (overlapping) group lasso, ...
+ Embraces distributed computing for big data {% sidenote 3 'Boyd, S., Parikh, N., Chu, E., Peleato, B., and Eckstein, J. (2011). Distributed optimization and statistical learning via the alternating direction method of multipliers. Found. Trends Mach. learn., 3(1):1-122.' %}

### Why this matters

Notice how the sidenotes display properly, but the fact that sidenotes have more display 'volume' than the list items themselves causes a horizontal mismatch between the sidenote item's number and its corresponding list item.

Please note that there must be *no blank lines between your list items*. This is due to a really strange thing about the Jekyll Markdown engine I have never noticed before. If you have a list, and you put a blank line between the items like this:

```
  + list item 1

  + list item 2
```

It will create an html tag structure like this:

```
<ul>
   <li>
      <p>list item 1</p>
  </li>
  <li>
      <p>list item 2</p>
   </li>
</ul>
```
Which *totally* goofs up the layout CSS.

However, if your Markdown is this:

```
    + list item 1
    + list item 2
```

It will create a tag structure like this:

```
<ul>
   <li>list item 1</li>
   <li>list item 2</li>
</ul>
```

Here is the same content as above, with a blank line separating the list items. Notice how the sidenotes get squashed into the main content area:


### Remarks on ADMM version 2 - **one blank line** between Markdown list items

Related algorithms

+ Split Bregman iteration {% sidenote 1 'Goldstein, T. and Osher, S. (2009). The split Bregman method for l1-regularized problems. SIAM J. Img. Sci., 2:323-343.' %}

+ Dykstra's alternating projection algorithm {% sidenote 2 'Dykstra, R. L. (1983). An algorithm for restricted least squares regression. J. Amer. Statist. Assoc., 78(384):837-842.' %}

+ Proximal point algorithm applied to the dual

+ Numerous applications in statistics and machine learning: lasso, gen. lasso, graphical lasso, (overlapping) group lasso, ...
<br>
<br>
<br>
<br>

### Liquid tag parsing strangeness

Example of the proper way to write an url inside a *Liquid* full-width image tag.

This code: ```{{ '{% fullwidth "assets/img/rhino.png" "Tuftes pet rhino (via <a href=\"//www.edwardtufte.com/tufte/\">Edward Tufte</a>)" ' }} %}```

produces the following image with a title. Notice that I have had to escape the double quotes in the HTML with a backslash. Also, the example above leaves out the single quote in 'Tufte's" because of the topsy-turvy way that you have to escape the escapes in code sections that are used for illustrative purposes in this text. Bottom line is that there are occasionally some odd interactions between the Markdown parser, custom *Liquid* tags and HTML.
{% fullwidth "assets/img/rhino.png" "Tufte's pet rhino (via <a href=\"//www.edwardtufte.com/tufte/\">Edward Tufte</a>)" %} --> 
