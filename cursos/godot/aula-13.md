---
layout: aulas
title: "GDScript - Função Com Retorno por Valor"
summary: godot
permalink: /cursos/godot/aula-13
tags: [Aula, GDScript, 'Função']
---

## Exemplo

```gdscript
func _ready():
  Minha_Funcao(2,6)
pass

func Minha_Funcao(a:int, b:int) -> int:
  print(a)
  print(b)
  var soma = a+b
  print(soma)
  return soma
pass
```

Resultado:

<img src="{{ 'assets/images/aulas/func3.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/B1rHKDdWBpQ?rel=0" allowfullscreen></iframe>
</div><br>