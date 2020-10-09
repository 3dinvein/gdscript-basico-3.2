---
layout: aulas
title: "GDScript - Operadores de Comparação e Operadores Lógicos"
summary: godot
permalink: /cursos/godot/aula-05
tags: [Aula, GDScript, 'Comparação']
---

## Operadores de Comparação

```gdscript
var vida : = 50

func _ready():
vida < 0 # vida é menor que zero
vida > 0 # vida é maior que zero
vida == 0 # vida é igual que zero
vida <= 0 # vida é menor ou igual que zero
vida >= 0 # vida é maior ou igual que zero
vida != 0 # vida é diferente de zero
pass
```

## Operadores Lógicos

```gdscript
var vida1 : = 50
var vida2 : = 100

func _ready():
vida1 == 50 and vida2 < 100 # vida1 é igual 50 e vida2 é < 100
vida1 > 0 or vida2 é > 0 # vida1 é maior que 0 ou vida2 que é > 0
not vida1 && not vida2 # vida1 não é 50 e vida2 não é 100
! vida1 || !vida2 # vida1 não é 50 ou vida2 não é 100
pass
```

Assista ao vídeo para mais detalhes: 
<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/DtS9dIuhbXc?rel=0" allowfullscreen></iframe>
</div><br>