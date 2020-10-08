---
layout: aulas
title: "GDScript - Loop de Repetição"
summary: godot
permalink: /cursos/godot/aula-10
tags: [Aula, GDScript, Loop]
---

## Exemplo 1 - Conjunto de Valores

```gdscript
func _ready():

  var conjunto_de_variaveis = {"a":0,"b":1,"c":2}

  for i in conjunto_de_variaveis:
    print(conjunto_de_variaveis[i])
  pass
```

## Resultado:

<img src="{{ 'assets/images/aulas/for1.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

## Exemplo 2 - Intervalos

```gdscript
func _ready():

  for i in range(3,6):
    print(i)
  pass
```

Resultado:

<img src="{{ 'assets/images/aulas/for2.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

## Exemplo 3 - Caracteres de Texto

```gdscript
func _ready():

  for caracter in "carro":
    print(caracter)
  pass
```

Resultado:

<img src="{{ 'assets/images/aulas/for3.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

## Exemplo 4 - Números Inteiros

```gdscript
func _ready():

  for inteiro in 4:
    print(inteiro)
  pass
```

Resultado:

<img src="{{ 'assets/images/aulas/for4.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

## Exemplo 5 - Números Flutuantes

```gdscript
func _ready():

  for flutuante in 3.3:
    print(flutuante)
  pass
```

Resultado:

<img src="{{ 'assets/images/aulas/for5.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/NOAb-U-qxIU?rel=0" allowfullscreen></iframe>
</div><br>