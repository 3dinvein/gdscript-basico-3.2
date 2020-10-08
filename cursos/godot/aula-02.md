---
layout: aulas
title: "GDScript - Variáveis Dinâmicas e Variáveis Constantes"
summary: godot
permalink: /cursos/godot/aula-02
tags: [Aula, GDScript, 'Variáveis']
---

## Forma Dinâmica

```gdscript
var texto : = "valor" # é String
var vida : = 100 # é int
var vida = 100 # pode ser assim também
var carga : = 75.5 # é float
var esta_caindo : = true # é booleana
var array : = [] # inicia com o array vazio
var cubo : MeshInstance = null # cubo está vazio
```

## Forma de Constantes

```gdscript
const MAXIMA_VELOCIDADE : = 400.0
const QUANTIDADE_MAXIMA : = 45
const TECLA_D_MAIUSCULA : = 68 #tabela ascii
const TECLA_D_MINUSCULA : = 100 #tabela ascii
```

## Observação Sobre as Constantes

As variáveis CONSTANTES(const) nunca variam o seu valor, elas sempre possuem um valor fixo. 

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/NwSvZIShg4Y?rel=0" allowfullscreen></iframe>
</div><br>