---
layout: page
permalink: /publications/
title: publications
description: # publications by categories in reversed chronological order.
nav: true
nav_order: 1
---

<!-- Bibsearch Feature {% include bib_search.liquid %} -->

<div class="publications">

<!-- Quick Navigation -->
<div class="publication-navigation" style="margin-bottom: 2rem; padding: 1rem; background-color: var(--global-card-bg-color); border-radius: 8px;">
  <strong>Jump to:</strong>
  <a href="#conferences" style="margin: 0 0.5rem;">Conferences & Workshops</a> | 
  <a href="#journals" style="margin: 0 0.5rem;">Journal Articles</a> | 
  <a href="#bookchapters" style="margin: 0 0.5rem;">Book Chapters</a> | 
  <a href="#magazines" style="margin: 0 0.5rem;">Magazine Articles</a>
</div>

<h2 id="conferences"><b>Peer-reviewed Conference and Workshop Publications</b></h2>
{% bibliography --query @*[pubtype=conference] %}

<div style="width: 100%; height: 3px; background: linear-gradient(to right, transparent, var(--global-theme-color), transparent); margin: 3rem 0;"></div>

<h2 id="journals"><b>Peer-reviewed Journal Articles</b></h2>
{% bibliography --query @*[pubtype=journal] %}

<div style="width: 100%; height: 3px; background: linear-gradient(to right, transparent, var(--global-theme-color), transparent); margin: 3rem 0;"></div>

<h2 id="bookchapters"><b>Book Chapters</b></h2>
{% bibliography --query @*[pubtype=bookchapter] %}

<div style="width: 100%; height: 3px; background: linear-gradient(to right, transparent, var(--global-theme-color), transparent); margin: 3rem 0;"></div>

<h2 id="magazines"><b>Magazine Articles</b></h2>
{% bibliography --query @*[pubtype=magazine] %}

</div>
