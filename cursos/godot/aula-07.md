---
layout: aulas
title: "GDScript - Condições ( Match )"
summary: godot
permalink: /cursos/godot/aula-07
tags: [Aula, GDScript, Match]
---

## Condição Match

Na GDScript não tem a condição Switch-case, em contra partida,
eles criaram uma condição chamada de match. Eu usaria ela somente
para menus, pois o valor tem que existir na condição.
Eu particularmente sempre gostei de usar a condição do if e else,
mas fica a critério de vocês.

## Exemplo

```gdscript
var vida : = 50

func _ready():

 match vida:
    100:
      print("Vida Cheia")
    50:
      print("Vida Pela Metade")
    0:
      print("Game Over")
 pass
```
Qualquer dúvida você pode assistir ao meu video, para entender melhor.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/dXov9Q4pOx4?rel=0" allowfullscreen></iframe>
</div><br>