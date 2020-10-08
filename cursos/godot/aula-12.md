---
layout: aulas
title: "GDScript - Função Sem Retorno Com Parâmetro"
summary: godot
permalink: /cursos/godot/aula-12
tags: [Aula, GDScript, 'Função']
---

## Exemplo

```gdscript
func _ready():
  Minha_funcao(30,"Luiz Eduardo")
pass

func Minha_funcao(a:int, b:String) -> void:
  print(a)
  print(b)
pass
```

Resultado:

<img src="{{ 'assets/images/aulas/func2.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/3sgyhjqPWGE?rel=0" allowfullscreen></iframe>
</div><br>