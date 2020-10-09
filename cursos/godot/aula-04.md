---
layout: aulas
title: "GDScript - Concatenação"
summary: godot
permalink: /cursos/godot/aula-04
tags: [Aula, GDScript, 'Concatenação']
---

## Forma de Concatenação 1

```gdscript
var nome : = "Eduardo"
var sobrenome : = "Maia"
var texto : = nome + " " + sobrenome
func _ready():
print(texto)
pass
```

## Forma de Concatenação 2

```gdscript
var nome : = "Eduardo"
var sobrenome : = "Maia"
var texto : = nome + " " + sobrenome
func _ready():
print("Olá " + texto)
print("Olá ", texto)
pass
```

## Forma de Concatenação 3

```gdscript
var cubo : MeshInstance = MeshInstance.new()

func _ready():
print("olá ", cubo) # Retorna o id da MeshInstance criada
pass
```

Observação sobre a forma 3:

Toda vez que quiser concatenar objetos e funções, eu recomendo utilizar a virgula para concatenar. 

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/hJM6LwsXp6s?rel=0" allowfullscreen></iframe>
</div><br>