---
title: Visual Arts
order: 3

sin_titulo:
  - title: "Sin Titulo #1"
    thumb: images/stgo/TodoAchoclonado.jpg
  - title: "Sin Titulo #2"
    thumb: images/stgo/CallesVertiginosas.jpg
  - title: "Sin Titulo #3"
    thumb: images/stgo/LaIglesia.jpg
  - title: "Sin Titulo #4"
    thumb: images/stgo/ElSapo.jpg
  - title: "Sin Titulo #5"
    thumb: images/stgo/Sanhattan.jpg
  - title: "Sin Titulo #6"
    thumb: images/stgo/Sanhattan2.jpg
  - title: "Sin Titulo #7"
    thumb: images/stgo/ElAgua.jpg
  - title: "Sin Titulo #8"
    thumb: images/stgo/ElMetro.jpg
  - title: "Sin Titulo #9"
    thumb: images/stgo/LaPeriferia.jpg
  - title: "Sin Titulo #10"
    thumb: images/stgo/OprimidoOpresor.jpg
  - title: "Sin Titulo #11"
    thumb: images/stgo/LaTele.jpg

animations:
  - title: Buscando
    video: videos/Buscando.mov
  - title: Encierro
    video: videos/Encierro.mp4
  - title: Cuarentena
    video: videos/Cuarentena.mp4

digital_post:
  - title: Variacion 1
    thumb: images/Variaciones/Variacion1.jpg
  - title: Variacion 2
    thumb: images/Variaciones/Variacion2.jpg
  - title: Variacion 3
    thumb: images/Variaciones/Variacion3.jpg

red_black:
  - title: C.
    thumb: images/C.jpg
  - title: E.L.
    thumb: images/EL.jpg
  - title: Emoción
    thumb: images/Emocion.jpg
  - title: Razón
    thumb: images/Razon.jpg

home_block:
  - text: Improv
    url: /improv
    image: /images/thumbs/bells-small.png
  - text: VR
    url: /vr
    image: /images/thumbs/bells-small.png
  - text: About
    url: /aboutme
    image: /images/thumbs/bells-small.png
---

## Short Animations (2020)

{% assign set = page.animations %}
{% include grid.html columns="3" thumbs="video" category="visuals" %}

## Red and black marker #2 (2017-2019)

{% assign set = page.sin_titulo %}
{% include grid.html columns="1" category="visuals" %}

## Red and black marker #1 (2009)

{% assign set = page.red_black %}
{% include grid.html category="visuals" %}

## Digital Post-Processing (2019)

{% assign set = page.digital_post %}
{% include grid.html columns="3" category="visuals" %}