---
layout: aulas
title: "GDScript - Função Com Retorno por Referência"
summary: godot
permalink: /cursos/godot/aula-14
tags: [Aula, GDScript, 'Função']
---

## Exemplo

```gdscript
func _ready():
  var opcoes     FuncaoPorReferencia(opcoes)
pass

func FuncaoPorReferencia(opcoes) -> Reference:
  opcoes = 1
  print(opcoes)
  return opcoes
pass
```

Resultado 1:

<img src="{{ 'assets/images/aulas/func4.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

Resultado 2:

<img src="{{ 'assets/images/aulas/func5.jpg' | relative_url }}" class="img-fluid" alt="Responsive image">

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/GcX6lLv7pHE?rel=0" allowfullscreen></iframe>
</div><br>
