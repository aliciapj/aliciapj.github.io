---
layout: post
title: "The bad guys in AI: atacando sistemas de Machine Learning"
summary: "En esta charla veremos una introducción sobre redes neuronales y explicaremos qué son las redes generativas antagónicas. Después veremos cómo las redes generativas aprenden a imitar otras redes, hasta el punto de lograr engañarlas, y por qué esto supone una vulnerabilidad en nuestros algoritmos de machine learning."
categories: talks
tags: ['python','ia','gan','attacks','security']
---

Las redes generativas antagónicas (conocidas como GANs por sus siglas en inglés) son una de las tecnologías más revolucionarias de los últimos años, no obstante han sido incluidas por Forbes en la lista de las mejores innovaciones de los últimos tres años e identificadas por MIT Tech Review como una de las tecnologías más prometedoras en 2018.

Técnicamente pueden definirse como un tipo específico de red neuronal, concebida especialmente para imitar la redes neuronales clásicas, aquellas que a día de hoy se conocen también como deep learning. Son capaces de aprender qué está modelando una red neuronal y generar datos válidos en su dominio desde cero. Esto significa que si una red neuronal categoriza imágenes de caras, una red generativa antagónica asociada aprenderá a generar nuevas imágenes de caras, ¡de gente que no existe!.

Una de las consecuencias de tener dicha capacidad de imitación es que se pueden configurar para engañar a las redes neuronales clásicas, generando datos que no es posible detectar como falsos. Este caso de uso tiene su lado oscuro, ya que el poder generar datos sintéticos indistinguibles de los datos reales puede usarse para atacar redes neuronales que estén integradas en sistemas críticos y de seguridad. La técnica para explotar esta vulnerabilidad se ha bautizado como ataque antagónico o adversarial attack.

En esta charla veremos primero una pequeña introducción sobre redes neuronales y explicaremos qué son las redes generativas antagónicas. Después veremos cómo las redes generativas aprenden a imitar otras redes, hasta el punto de lograr engañarlas, y por qué esto supone una vulnerabilidad en nuestros algoritmos de machine learning. Para ilustrar un ataque antagónico usaremos un ejemplo en Python para engañar a un sistema de reconocimiento de imágenes. Por último discutiremos por qué este problema es importante y las enormes consecuencias que puede llegar a tener en nuestros sistemas de machine learning.

### @T3chFest 2019 con Beatriz Gómez

Feria de informática y nuevas tecnologías en la Universidad Carlos III. El evento se celebró el 14 y 15 de marzo de 2019 en Getafe, Madrid.

#### Video

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
 <iframe src="//www.youtube.com/embed/d-8DdW7MTxQ" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen="" title="YouTube Video"></iframe>
</div>

#### Slides

<div style="left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.1972%;"><iframe src="https://speakerdeck.com/player/e1315eb42a174c0ea454e55183115ca0" style="border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;" allowfullscreen scrolling="no" allow="encrypted-media"></iframe></div>

#### Más info

- [Web del evento](https://t3chfest.es/2019/programa/the-bad-guys-atacando-sistemas-machine-learning)
- [Repo en GitHub](https://github.com/aliciapj/adversarial-networks)


### @PyConES 2018 con Javier Ordoñez

PyConES es la conferencia de la comunidad Python española. El evento se celebró por sexta vez del 5 al 7 de octubre de 2018 en Málaga.

#### Video

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
 <iframe src="//www.youtube.com/embed/D2m9Ejx6S9k" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen="" title="YouTube Video"></iframe>
</div>

#### Slides

<div style="left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.1972%;"><iframe src="https://speakerdeck.com/player/9f0c2640c48c40b5b1cd82a671db4b04" style="border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;" allowfullscreen scrolling="no" allow="encrypted-media"></iframe></div>

#### Más info

- [Web del evento](https://2018.es.pycon.org/talk/the-bad-guys-in-ai-atacando-sistemas-de-machine-learning)
- [Repo en GitHub](https://github.com/aliciapj/adversarial-networks)

