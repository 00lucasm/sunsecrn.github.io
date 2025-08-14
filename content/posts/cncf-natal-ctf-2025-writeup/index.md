---
id: index
aliases: []
tags:
  - ctf
  - writeup
  - cloud
authors:
  - "00lm"
categories:
  - writeup
date: "2025-08-13"
description: ""
draft: false
showAuthor: false
showAuthorsBadges: true
title: "CNCF Natal CTF 2025 - Writeup"
---

Este CTF foi criado pela comunidade [Sunsec](https://sunsec.net/) com apoio do grupo [CNCF RN](https://chat.whatsapp.com/JpgK5OwEwHiI3iQhE8CuXF) para abordar temas relacionados a tecnologias Cloud Native, como containers, Kubernetes, CI/CD, segurança em nuvem e muito mais!

Writeup dos desafios que resolvi:

| desafio                    | categoria         | pontos | resolvido |
|----------------------------|-------------------|--------|-----------|
| Bucket aberto demais       | FL[AWS]           | 110    | Sim       |
| Lista pra quem?            | FL[AWS]           | 110    | Sim       |
| Git vazado                 | FL[AWS]           | 110    | Sim       |
| Snapshot público           | FL[AWS]           | 110    | Sim       |
| Proxy e IMDS               | FL[AWS]           | 110    | Sim       |
| O Lambda entrega           | FL[AWS]           | 110    | Sim       |
| Logs suspeitos             | CI/CD             | 100    | Sim       |
| Artifact escondido         | CI/CD             | 100    | Sim       |
| Código indecifrável?       | CI/CD             | 100    | Sim       |
| Porto Inseguro             | CI/CD             | 100    | Não       |
| Qual meu objetivo?         | Pergunta/Resposta | 50     | Não       |
| Onde estão as nuvens?      | Pergunta/Resposta | 50     | Sim       |
| Quem está fazendo o build? | Pergunta/Resposta | 50     | Não       |

## Bucket aberto demais

## Lista pra quem?

## Git vazado
  
## Snapshot público

## Proxy e IMDS

## O Lambda entrega

## Logs suspeitos

## Artifact escondido

## Código indecifrável?

Analisando os _raw logs_ do job "build" encontrado no repositório do CNCF-Natal-CTF, pude observar muitas informações.

## Onde estão as nuvens?

Desafio de pergunta e resposta bastante simples e direto, a resposta era: **aws**

Foi um pouco _guessing_, eu sei, mas não tinha muito o que fazer. Boa parte dos desafios envolviam ownar alguma coisa de AWS e logo entendi que tinha uma boa chance de ser isso