---
layout: page
permalink: /publications/
title: publications
---


### Journal papers

{% bibliography -q@article %}

### Conference papers

{% bibliography -q@inproceedings[workshop !~ .] %}

### Workshop papers/abstracts

{% bibliography -q@*[workshop] %}


### PhD Dissertation

{% bibliography -q@phdthesis %}
