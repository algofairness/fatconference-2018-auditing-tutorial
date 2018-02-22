---
layout: default
title: {{ site.name }}
---

# Auditing Black Box Models

* Where: [FAT*](https://www.fatconference.org/2018/program.html)
* When: 2018-02-23, 4-5PM EST, Vanderbilt Hall 204
* Who: [Suresh Venkatasubramanian](http://www.cs.utah.edu/~suresh), [Carlos Scheidegger](https://cscheid.net), Charlie Marx

Models learned through machine learning can be hard to interpret. A
model that takes many inputs and has many parameters might depend on
the inputs in complicated ways. This makes it hard to know if, for
example,

• the model might indirectly depend on protected attributes of the
input that users of the model might prefer it not do (for example race
via zipcode).

• the model depends heavily on input attributes that domain knowledge
might suggest should not be an important factor (for example, a system
that predicts the output of a chemical reaction but appears to be
influenced by the time the reaction is run).

This tutorial will teach the audience to use a software library
developed by the presenters of the tutorial through a sequence of
simple examples in a Jupyter notebook. The presenters will focus
on understanding current strengths and limitations of the method, and
how tutorial attendees can use this method in their own datasets.

## Materials

* Slides: TBD.
* Jupyter Notebook: TBD.
* Installation Instructions: TBD.

## Papers
<a name="papers"></a>
 
* Feldman et al., [Certifying and Removing Disparate Impact](https://dl.acm.org/citation.cfm?id=2783311), KDD 2015
* Adler et al., [Auditing Black-Box Models for Indirect Influence](https://link.springer.com/article/10.1007/s10115-017-1116-3), Knowledge and Information Systems, 54(1):95--122, 2018.
