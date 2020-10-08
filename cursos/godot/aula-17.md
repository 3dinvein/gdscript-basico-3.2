---
layout: aulas
title: "GDScript - Funções Principais da Godot Engine 3.2"
summary: godot
permalink: /cursos/godot/aula-17
tags: [Aula, GDScript, 'Godot']
---

## func _enter_tree():

Acontece antes da função func _ready(). Ela pode ser chamada quando objeto entra dentro da hierarquia da árvore.
Esta função seria equivalente a função Awake da Unity 3D.

## func _exit_tree():

Ela pode ser chamada quando objeto sai da hierarquia da árvore.

## func _init()

Este é o construtor da nossa classe. Exemplo: var classe:Classe=Classe.new()
O termo Classe.new() é chamado para criar a estrutura da nossa classe, e por isto, ele é considerado um construtor.

## func _ready():

A chamada acontece apenas uma vez no inicio. Esta função seria equivalente a função Start() da Unity 3D.

## func _process(delta):

A chamada acontece o tempo todo a cada segundo. Esta função seria equivalente a função Update() da Unity 3D.

## func _physics_process(delta):

A chamada acontece o tempo todo a cada segundo para objetos que tenham física. Esta função seria equivalente
a função FixedUpdate() da Unity 3D.


<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/rb8Rt-dcgJg?rel=0" allowfullscreen></iframe>
</div><br>