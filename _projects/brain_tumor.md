---
layout: post
title: AI for Brain Tumor Classification
description: Benchmark de 3 CNNs vs le InceptionV3 pour la classification de tumeurs cérébrales
---

Retrouvez les notebooks de ce projet dans [ce repository Github](https://github.com/erivaninan/Brain-Tumor-Classification){:target="_blank"}.

Consultez le rapport pdf du projet [ici](https://github.com/erivaninan/Brain-Tumor-Classification/blob/main/(FR)%20Brain_Tumor_Classification_Report.pdf)

Classification de tumeurs cérébrales
============

Les `tumeurs cérébrales` représentent un enjeu majeur de santé publique, nécessitant des outils de diagnostic précis et rapides pour améliorer la prise en charge des patients. Ce projet vise à développer un réseau neuronal convolutionnel (CNN) sur mesure et à réaliser un benchmark avec des modèles pré-entraînés tels qu’ImageNet et InceptionV3 pour la classification automatisée des tumeurs cérébrales à partir d’images IRM.

Ce projet met en lumière le potentiel de l’intelligence artificielle pour assister les professionnels de santé dans la détection précoce et l’évaluation des pathologies cérébrales.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
look like:

  * this one
  * that one
  * the other one

Note that the actual text
content starts at 4-columns in.

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.


H2 Header
------------

Here's a numbered list:

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of
indenting the block, you can use delimited blocks, if you like:

~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~

(which makes copying & pasting easier). You can optionally mark the
delimited block for Pandoc to syntax highlight it by specifying the languagae after the start of a block (e.g. `~~~python`) which would look like :

~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print(i)
~~~

### An H3 header ###

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a footnote [^1].

[^1]: Some footnote text.

Tables can look like this:

| Header 1 | Header 2                   | Header 3 |
|:--------:|:--------------------------:|:--------:|
| data1a   | Data is longer than header | 1        |
| d1b      | add a cell                 |          |
| lorem    | ipsum                      | 3        |
|          | empty outside cells        |          |
| skip     |                            | 5        |
| six      | Morbi purus                | 6        |


A horizontal rule follows.

***

Here's a definition list:

apples
  : Good for making applesauce.

oranges
  : Citrus!

tomatoes
  : There's no "e" in tomatoe.

Again, text is indented 4 spaces. (Put a blank line between each
term and  its definition to spread things out more.)

Here's a "line block" (note how whitespace is honored):

| Line one
|   Line too
| Line tree

and images can be specified like so:

![example image](https://images.unsplash.com/photo-1488190211105-8b0e65b80b4e?w=300&h=300&fit=crop "An exemplary image")

Inline math equation: $\omega = d\phi / dt$. Display
math should get its own line like so:

$$I = \int \rho R^{2} dV$$
