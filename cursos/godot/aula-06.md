---
layout: aulas
title: "GDScript - Condições"
summary: godot
permalink: /cursos/godot/aula-06
tags: [Aula, GDScript, 'Condições']
---

## Condição IF

```gdscript
var vida = 100

func _ready():
  if vida == 100:
    print("igual")
pass
```

## Condição ELIF

```gdscript
var vida = 100

func _ready():
  if vida == 100:
    print("igual")
  elif vida > 100:
    print("maior")
pass
```

## Condição ELSE

```gdscript
var vida = 100

func _ready():
  if vida == 100:
    print("igual")
  elif vida > 100:
    print("maior")
  else:
    print("menor")
pass
```

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/ZJwu34GcCTk?rel=0" allowfullscreen></iframe>
</div><br>