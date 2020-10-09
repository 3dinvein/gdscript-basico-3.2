<p align="center"><img src="./assets/images/logo-titulo.png" width="35%"></p>
<p align="center">
  <a href="https://github.com/3dinvein" alt="MadeBy">
    <img src="https://img.shields.io/badge/made%20by-Luiz%20Eduardo-blue" />
  </a>
  <a href="https://github.com/3dinvein" alt="Graphic Design">
    <img src="https://img.shields.io/badge/layout%20design%20page%20made%20by-Reinan Gabriel-blue" />
  </a>
  <a href="./README.md" alt="License">
    <img src="https://img.shields.io/badge/license-MIT-blue" />
  </a>
</p>

| [Introdução] | [Playlist] | [Site] | [Aulas] |
|--------------|------------|--------|---------|
- - -

# GDScript Básico 3.2
Aprenda o básico da programação em `GDScript`

## Introdução

GDScript é uma linguagem de auto nível, dinâmicamente tipada, usada para criar conteúdo. Utiliza uma sintaxe similar a do [Python](https://en.wikipedia.org/wiki/Python_%28programming_language%29). Seu objetivo é ser otimizada para e firmemente integrada ao motor Godot, permitindo grande flexibilidade para a criação e integração de conteúdo.

## Exemplo de GDScript

Algumas pessoas conseguem aprender melhor observando a sintaxe, então aqui está um simples exemplo:

```gd
var texto : String = "valor"
var vida : int = 100
var carga : float = 75.5
var esta_caindo : bool = false
var array : Array = [] # inicia com o array vazio
var cubo : MeshInstance = MeshInstance.new()
```

## Comentários no GDScript
Qualquer coisa desde um `#` até o fim da linha é ignorada e é considerada como um comentário.
```py
# This is a comment.
```

## Aulas de GDScript

|                                                 |              |
|-------------------------------------------------|--------------|
| Aula                                            | Estatísticas |
| [Variáveis tipadas]                             | ![Like01]    |
| [Variáveis dinâmicas e variáveis constantes]    | ![Like02]    |
| [Operações matemáticas básicas]                 | ![Like03]    |
| [Concatenação]                                  | ![Like04]    |
| [Operadores de comparação e operadores lógicos] | ![Like05]    |
| [Condições 1]                                   | ![Like06]    |
| [Condições 2]                                   | ![Like07]    |
| [Lista de valores com Arrays]                   | ![Like08]    |
| [Percorrendo e buscando valores no array]       | ![Like09]    |
| [Loop de repetição]                             | ![Like10]    |
| [Função sem retorno]                            | ![Like11]    |
| [Função sem retorno com parâmetro]              | ![Like12]    |
| [Função com retorno por valor]                  | ![Like13]    |
| [Função com retorno por referência]             | ![Like14]    |
| [Classes]                                       | ![Like15]    |
| [Herança de classe]                             | ![Like16]    |
| [Funções principais da Godot Engine 3\.2]       | ![Like17]    |
| [Váriavel do tipo onready]                      | ![Like18]    |

[Variáveis tipadas]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-01
[Like01]: https://img.shields.io/youtube/likes/rb8Rt-dcgJg?label=Likes&style=social&withDislikes
[Variáveis dinâmicas e variáveis constantes]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-02
[Like02]: https://img.shields.io/youtube/likes/NwSvZIShg4Y?label=Likes&style=social&withDislikes
[Operações matemáticas básicas]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-03
[Like03]: https://img.shields.io/youtube/likes/UVfHmfkI0LM?label=Likes&style=social&withDislikes
[Concatenação]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-04
[Like04]: https://img.shields.io/youtube/likes/hJM6LwsXp6s?label=Likes&style=social&withDislikes
[Operadores de comparação e operadores lógicos]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-05
[Like05]: https://img.shields.io/youtube/likes/DtS9dIuhbXc?label=Likes&style=social&withDislikes
[Condições 1]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-06
[Like06]: https://img.shields.io/youtube/likes/ZJwu34GcCTk?label=Likes&style=social&withDislikes
[Condições 2]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-07
[Like07]: https://img.shields.io/youtube/likes/dXov9Q4pOx4?label=Likes&style=social&withDislikes
[Lista de valores com Arrays]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-08
[Like08]: https://img.shields.io/youtube/likes/Auzix3ckqnY?label=Likes&style=social&withDislikes
[Percorrendo e buscando valores no array]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-09
[Like09]: https://img.shields.io/youtube/likes/LtKXELb1qiM?label=Likes&style=social&withDislikes
[Loop de repetição]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-10
[Like10]: https://img.shields.io/youtube/likes/NOAb-U-qxIU?label=Likes&style=social&withDislikes
[Função sem retorno]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-11
[Like11]: https://img.shields.io/youtube/likes/2p_2bWjLDZk?label=Likes&style=social&withDislikes
[Função sem retorno com parâmetro]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-12
[Like12]: https://img.shields.io/youtube/likes/3sgyhjqPWGE?label=Likes&style=social&withDislikes
[Função com retorno por valor]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-13
[Like13]: https://img.shields.io/youtube/likes/B1rHKDdWBpQ?label=Likes&style=social&withDislikes
[Função com retorno por referência]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-14
[Like14]: https://img.shields.io/youtube/likes/GcX6lLv7pHE?label=Likes&style=social&withDislikes
[Classes]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-15
[Like15]: https://img.shields.io/youtube/likes/5nlTy1jwwFc?label=Likes&style=social&withDislikes
[Herança de classe]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-16
[Like16]: https://img.shields.io/youtube/likes/si4iWeYAhEs?label=Likes&style=social&withDislikes
[Funções principais da Godot Engine 3\.2]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-17
[Like17]: https://img.shields.io/youtube/likes/VEmvQsLAmcw?label=Likes&style=social&withDislikes
[Váriavel do tipo onready]: https://3dinvein.github.io/gdscript-basico-3.2/cursos/godot/aula-18
[Like18]: https://img.shields.io/youtube/likes/aSAmL1CW05E?label=Likes&style=social&withDislikes

[Introdução]: #Introdução
[Playlist]: https://www.youtube.com/watch?v=R4fNsfGpvMQ&list=PL29O-BKxbiTs5IS4-s5ELdul-ViQYC-bh
[Aulas]: #Aulas
[Site]: https://3dinvein.github.io/gdscript-basico-3.2
[Programador e Criador do Design]: #Renan
