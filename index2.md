---
layout: home
title: Bienvenue !
feature_image: /assets/img/logo_h.svg
feature_text: |
    Bienvenu sur le site de l'Association Morlanaise Langues et Culture (M'Langues).
    Sur ce site vous trouverez toutes les informations sur les activitées
    proposées par l'association.
---


L'association M'Langues est une association à
but non lucratif créée le 9 novembre 2018 avec pour objectif de promouvoir la
découverte et la diffusion de la culture sous toute ses formes et l'apprentissage
des langues étrangères par une approche ludique et conviviale.

L'association est ouverte à tous et propose des activités pour adultes et enfants
à partir de 4 ans.
N'hésitez pas à nous [contacter](/contact/).
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
