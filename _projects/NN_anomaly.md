---
layout: post
title: Neural Networks for anomaly detection
description: PMC, GAN, CAE, SOM et DBN pour la détection d'anomalies dans différents contextes
---

Retrouvez les notebooks de ce projet dans [ce repository Github](https://github.com/erivaninan/Neural-Networks-for-Anomaly-Detection){:target="_blank"}.


============

Ce projet explore l’application de modèles d’apprentissage profond pour la détection d’anomalies dans des données variées, telles que les comprimés et gélules (MVTec Pill), les chiffres manuscrits (MNIST) et les données de sécurité réseau (CICIDS2017). Différentes approches ont été mises en œuvre, incluant les perceptrons multicouches (PMC), les réseaux antagonistes génératifs (GAN), les cartes de Kohonen (SOM) et les réseaux de croyances profonds (DBN). Les résultats démontrent la pertinence et les limites de chaque méthode selon le type de données et le contexte d’application. Ces travaux offrent une vision comparative des capacités des modèles de deep learning pour résoudre des problématiques critiques dans des domaines tels que la détection de défauts industriels, l’analyse de données manuscrites et la cybersécurité.

Il s'agit d'un projet soumis en vue de l’accomplissement des exigences de l’ISUP et Sorbonne Université pour l’obtention du diplôme de Master 2 Data Science.

**Consignes du projet**

  * Présentation succincte des réseaux de neurones, comprenant comment fonctionne l’apprentissage supervisé du PMC.
  * Utilisation de R pour le PMC avec comparaison avec une méthode statistique classique.
  * Démonstration d’un logiciel (ou autre fonction que nnet de R) traitant des réseaux neuronaux.
  * Utilisation d’un logiciel pour une démonstration de carte de Kohonen.
  * Démonstration des réseaux antagonistes génératifs, dits GANs.
  * Démonstration logicielle pour un modèle de réseaux profonds tels que DBN.
  * Éthique


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
delimited block for Pandoc to syntax highlight it by specifying the languagae after the start of a block (e.g. `~~~cpp`) which would look like :

~~~cpp
#include <iostream>
using namespace std;

int main() 
{    
    cout << "Size of char: " << sizeof(char) << " byte" << endl;
    cout << "Size of int: " << sizeof(int) << " bytes" << endl;
    cout << "Size of float: " << sizeof(float) << " bytes" << endl;
    cout << "Size of double: " << sizeof(double) << " bytes" << endl;

    return 0;
}
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
