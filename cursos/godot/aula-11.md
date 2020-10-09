---
layout: aulas
title: "GDScript - Função Sem Retorno"
summary: godot
permalink: /cursos/godot/aula-11
tags: [Aula, GDScript, Void]
---

## Exemplo

```gdscript
func _ready():
  MostrarNome()
pass

func MostrarNome() -> void:
  var nome : String = "Eduardo"
  print(nome)
pass 
```

Resultado:

<img src="{{ 'assets/images/aulas/func1.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/2p_2bWjLDZk?rel=0" allowfullscreen></iframe>
</div><br>