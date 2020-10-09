---
layout: aulas
title: "GDScript - Variáveis tipadas"
summary: godot
permalink: /cursos/godot/aula-01
tags: [Aula, GDScript, 'Variáveis']
---

## Forma Privada

```gdscript
var texto : String = "valor"
var vida : int = 100
var carga : float = 75.5
var esta_caindo : bool = false
var array : Array = [] # inicia com o array vazio
var cubo : MeshInstance = MeshInstance.new()
```

## Forma Pública

```gdscript
export (String) var texto : String = "valor"
export (int) var vida : int = 100
export (float) var carga : float = 75.5
export (bool) var esta_caindo : bool = false 
```

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/rb8Rt-dcgJg?rel=0" allowfullscreen></iframe>
</div><br>