---
layout: aulas
summary: linux
title: "Linux - Fila de Envio e Recebimento de Email"
permalink: /cursos/linux/aula-01
tags: [aula,'linux']
---

## Observação:
Os comandos realizados no teminal linux são sempre em minúsculo.
Para fixar na mente de vocês o que é fila de email, lembrem disso:
A fila é igual a pasta temp, onde possuiem arquivos temporários parados lá. 

## Comando Mailq ou Postqueue -P

Retorna a fila de envio e recebimento de email, com dados como o id e o email da pessoa que enviou ou a que era pra receber, as vezes vem os dois juntos. Normalmente, quando um email vai parar na fila de envio e recebimento, é por que há um erro no email, então precisamos analisar o email enviado e o email recebido para que possamos remover o email errado.

## Comando Postqueue -F

Pára com o serviço da fila de email, é usado mais quando queremos analisar mais profundamente o registro de email, fazendo uma cópia do registro e etc...

## Comando Postsuper -D ID

Esse comando exclui o email da fila que está trancando o fluxo, é usado muito usado por mim mesmo, é esse e o próximo comando.

## Comando Postsuper -D ALL

Esse comando exclui todos os emails da fila que está trancando o fluxo, é usado quando não temos mais dúvidas sobre o email se é importante ou não.

Assista ao vídeo para mais detalhes: 

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/0gKLYLPUDss?rel=0" allowfullscreen></iframe>
</div><br>