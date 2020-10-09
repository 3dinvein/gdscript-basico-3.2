---
layout: post
title:  "Como Instalar o Codeblocks 20.03 e o Freeglut Opengl no Lubuntu 20.04"
author: luiz
categories: [ linux, tutorial ]
image: assets/images/02.jpg
tags: [linux]
---

**Observação**: A distribuição que utilizei na dica logo abaixo foi o Lubuntu 20.04 Lxqt

### INSTALAR O CODEBLOCKS
```sh
sudo apt install codeblocks
sudo apt install libxxf86vm-dev
sudo apt install build-essential
```

### Baixar a biblioteca gconio.h porque o conio.h não tem pra linux. Link para download logo abaixo:
**Link**: [Biblioteca gconio.h](http://www.wence.vandermeersch.org/gconio/gconio.h)


### Depois copiar a biblioteca gconio.h e colar nesse diretório /usr/include/gconio.h

```sh
sudo cp /home/usuario/Download/gconio.h /usr/include/gconio.h
```

### PARA INSTALAR O FREEGLUT3 PARA PROGRAMAÇÃO GRÁFICA USANDO O OPENGL

```sh
sudo apt install freeglut3 freeglut3-dev
sudo ln -s /usr/lib/x86_64-linux-gnu/libglut.so.3.9.0 /usr/lib/libglut.so.3.9.0
sudo ln -s /usr/lib/x86_64-linux-gnu/libglut.so.3 /usr/lib/libglut.so.3
sudo ln -s /usr/lib/x86_64-linux-gnu/libglut.so /usr/lib/libglut.so
```

Veja o vídeo abaixo para maior compreensão

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/qLV9Wwmv4Aw?rel=0" allowfullscreen></iframe>
</div><br>