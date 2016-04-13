---
layout: relation
title: 'amod'
shortdef: 'adjectival modifier'
---

An adjectival modifier of a noun is any adjectival phrase that serves to modify the meaning of the noun.

Exception: if the modifying adjectival word is pronominal (i.e. tagged [ru-pos/DET]()), the relation is [det]() instead of `amod`.

~~~ sdparse
Василий ест куриную лапшу . \n Vasily eats chicken noodles .
amod(лапшу, куриную)
amod(noodles, chicken)
~~~

~~~ sdparse
Первое впечатление было хорошим . \n First impression was positive .
amod(впечатление, Первое)
amod(impression, First)
nsubj(хорошим, впечатление)
nsubj(positive, impression)
~~~