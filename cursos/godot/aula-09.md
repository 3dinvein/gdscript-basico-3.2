---
layout: aulas
title: "GDScript - Percorrendo e Buscando Valores no Array"
summary: godot
permalink: /cursos/godot/aula-09
tags: [Aula, GDScript, 'Array']
---

## Buscando Valores Com WHILE (enquanto)

```gdscript
var lista_jogadores = ["luiz","gustavo","fernando"]

func _ready():
 var i = 0

 while i < lista_jogadores.size():
    print(lista_jogadores[i])
    i+=1 # ou i = i + 1
```

## Buscando Valores Com FOR (para cada)

```gdscript
var lista_jogadores = ["luiz","gustavo","fernando"]

func _ready():
 for jogador in lista_jogadores:
    print(jogador)
```

O resultado é o mesmo para ambos, mas a interpretação é diferente.

Para mais detalhes assistir na prática no vídeo abaixo:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/LtKXELb1qiM?rel=0" allowfullscreen></iframe>
</div><br>