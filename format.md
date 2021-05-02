---
layout: default
title: Formatierung
permalink: /format/
footer: no
---

## Bild
```
<img class="img-responsive" src="{{ "/img/xx/yyy.zzz" | prepend: site.baseurl }}" alt="">
```

## Link
```
<a href="URL" target="_blank">BlaBliBlu</a>
```

### Hervorhebung
```
<p class="lead">Text ist etwas größer</p>
```

### Fett
```
<strong>als fetter Text angezeigt</strong>
```

### Kursiv
```
<em>als Kursiv angezeigt</em>
```

### Ausrichtung
```
<p class="text-left">Links ausgerichteter Text.</p>
<p class="text-center">Zentrierter Text.</p>
<p class="text-right">Rechts ausgerichteter Text.</p>
<p class="text-justify">Blocksatz-Text.</p>
<p class="text-nowrap">Text ohne Umbruch.</p>
```

### Listen
unordered
```
<ul>
  <li>...</li>
</ul>
```
sortiert
```
<ol>
  <li>...</li>
</ol>
```
ohne Bullets und Nummern
```
<ul class="list-unstyled">
  <li>...</li>
</ul>
```
Inline (alle Objekte in einer Zeile)
```
<ul class="list-inline">
  <li>...</li>
</ul>
```
Horizontale Beschreibung
```
<dl class="dl-horizontal">
  <dt>...</dt>
  <dd>...</dd>
</dl>
```

### Tabellen
Einfach
```
<table class="table">
  ...
</table>
```
Gestreift
```
<table class="table table-striped">
  ...
</table>
```
mit Rahmen
```
<table class="table table-bordered">
  ...
</table>
```


## Alle Beispiele Bootstrap formating:

[http://holdirbootstrap.de/css/#type](http://holdirbootstrap.de/css/#type)