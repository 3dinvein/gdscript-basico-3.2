---
layout: post
title:  "Criando Atalho do Seu Programa Dentro das Categorias do Linux"
author: luiz
categories: [ linux, tutorial ]
image: assets/images/04.jpg
tags: [linux]
---

Para criar o atalho dentro das categorias do linux, é preciso definir o diretório que seu programa vai ficar, definir o seu executável, definir o icone para aparecer na categoria desejada e o mais importante que é definir em qual categoria o seu programa se encontra.

**Observação**: Os nomes das categorias são sempre em inglês.

Depois dos requisitos acima, criar um arquivo relacionado ao nome do seu programa, e com extensão .desktop. Por exemplo: `piskel.desktop`

Esse arquivo tem que ser criado dentro do seguinte diretório: `/usr/share/applications/`

O conteúdo desse arquivo como exemplo, está logo abaixo, mas também possuo um video sobre esse mesmo tema.  

```txt
[Desktop Entry] # Começamos declarando a entrada
Name=Piskel # Nome do programa
Comment=Piskel 0.14 # Coloque um comentário
GenericName=Piskel # Caso o primeiro nome der pau tem esse nome genérico
TryExec=/opt/Piskel-0.14.0-64bits/piskel # Opcional - tenta executar o executável
Exec=/opt/Piskel-0.14.0-64bits/piskel # Caminho do executável
Icon=/opt/Piskel-0.14.0-64bits/piskel.png # Icone do programa, detalhe: 512px : 512px
Terminal=false # true = "executar no terminal" ou false = "não executar no terminal"
Type=Application # Tipo da aplicação, por exemplo: é imagem ou programa
Categories=Graphics; # São categorias que existem no seu menu inicial do seu linux
StartupNotify=true # Opcional
NoDisplay=false # Opcional
#MimeType=application/octet-strea
MimeType=application/x-piskel # Serve pra fixar o tipo de aplicação - Considere Opcional
```

Para mais detalhes assistir na prática no vídeo abaixo:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/SOW3uqM0um4?rel=0" allowfullscreen></iframe>
</div><br>