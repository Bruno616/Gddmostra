<p align="center">
  <img src="https://i.ibb.co/56s7K8j/292330192-445386850928422-7259301303587158181-n-jpg.png" alt="Minimalist RPG GDD Banner">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Versão-0.2.9-blue?style=for-the-badge" alt="Versão">
    <img src="https://img.shields.io/badge/Markdown-%23%23302c9b.svg?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">

</p>

# GDD Template

Este repositório contém um template completo para um Documento de Design de Jogo (GDD) em português, estruturado em Markdown. Esse template visa fornecer uma base sólida e organizada para que desenvolvedores de jogos possam documentar todos os aspectos importantes do design de seus jogos de maneira detalhada e estruturada.

## Objetivo

O objetivo principal deste repositório é ajudar desenvolvedores de jogos, desde iniciantes até veteranos, a criarem documentos de design bem estruturados e abrangentes. Este template cobre uma ampla gama de tópicos importantes, incluindo mecânicas de jogo, narrativa, design de níveis, arte, áudio, monetização, e muito mais.

## Para quem é destinado

- **Desenvolvedores de Jogos:** Que estão no processo de criar e documentar seus jogos.
- **Estudantes de Game Design:** Que desejam aprender e praticar a criação de GDDs.
- **Equipes de Desenvolvimento:** Que precisam de uma estrutura clara e colaborativa para planejar e documentar o design do jogo.
- **Entusiastas de Jogos:** Que têm interesse em entender melhor o processo de design de jogos.

## Estrutura do Documento

O template é dividido nas seguintes seções principais:
1. **Informações Gerais:** Detalha as informações básicas sobre o jogo, como título, plataforma, gênero e público-alvo.
2. **Mecânicas de Jogo:** Descreve as regras, controles, objetivos, sistema de pontuação, interações, progressão, IA, dinâmicas e economia do jogo.
3. **Narrativa:** Apresenta a história principal, personagens, cenários, missões e diálogos do jogo.
4. **Design de Níveis:** Estrutura, mapas, desafios, fluxo e balanceamento de dificuldade dos níveis.
5. **Arte e Estilo Visual:** Detalha o estilo artístico, personagens, cenários, interface do usuário e paleta de cores.
6. **Áudio:** Descreve a trilha sonora, efeitos sonoros, dublagem e som ambiente.
7. **Progresso e Salvamento:** Explica os sistemas de progressão e salvamento do jogo.
8. **Monetização:** Detalha o modelo de negócio e itens pagos.
9. **Testes e Qualidade:** Plano de testes e coleta de feedback dos jogadores.
10. **Conclusão:** Resume os principais pontos do GDD e os próximos passos no desenvolvimento do jogo.

## Como Utilizar

1. **Clone o Repositório:** `git clone https://github.com/allefrodrigo/gdd-template.git`
2. **Edite o Template:** Abra o arquivo Markdown e preencha cada seção com as informações do seu jogo.
3. **Personalize:** Adapte e adicione seções conforme necessário para atender às necessidades específicas do seu projeto.

# Sumário

1. [Informações Gerais](#1-informações-gerais)<br>
    1.1. [Título do Jogo](#11-título-do-jogo)  
    1.2. [Plataforma](#12-plataforma)  
    1.3. [Gênero](#13-gênero)  
    1.4. [Público-Alvo](#14-público-alvo)  
    1.5. [Visão Geral do Jogo](#15-visão-geral-do-jogo)  

2. [Mecânicas de Jogo](#2-mecânicas-de-jogo)<br>
    2.1. [Regras Básicas](#21-regras-básicas)  
    2.2. [Controles](#22-controles)  
    2.3. [Objetivos e Metas](#23-objetivos-e-metas)  
    2.4. [Sistema de Pontuação](#24-sistema-de-pontuação)  
    2.5. [Mecânicas de Interação](#25-mecânicas-de-interação)  
    2.6. [Sistemas de Progressão e Recompensas](#26-sistemas-de-progressão-e-recompensas)  
    2.7. [Inteligência Artificial (IA)](#27-inteligência-artificial-ia)  
    2.8. [Dinâmicas de Jogo](#28-dinâmicas-de-jogo)  
    2.9. [Economia do Jogo](#29-economia-do-jogo)  

3. [Narrativa](#3-narrativa)<br>
    3.1. [História Principal](#31-história-principal)  
    3.2. [Personagens](#32-personagens)  
    3.3. [Cenários](#33-cenários)  
    3.4. [Missões e Quests](#34-missões-e-quests)  
    3.5. [Roteiro e Diálogos](#35-roteiro-e-diálogos)  

4. [Design de Níveis](#4-design-de-níveis)<br>
    4.1. [Estrutura dos Níveis](#41-estrutura-dos-níveis)  
    4.2. [Mapas e Layouts](#42-mapas-e-layouts)  
    4.3. [Desafios e Puzzles](#43-desafios-e-puzzles)  
    4.4. [Fluxo dos Níveis](#44-fluxo-dos-níveis)  
    4.5. [Balanceamento de Dificuldade](#45-balanceamento-de-dificuldade)  

5. [Arte e Estilo Visual](#5-arte-e-estilo-visual)<br>
    5.1. [Estilo Artístico](#51-estilo-artístico)  
    5.2. [Personagens e Animações](#52-personagens-e-animações)  
    5.3. [Cenários e Ambientes](#53-cenários-e-ambientes)  
    5.4. [Interface do Usuário (UI)](#54-interface-do-usuário-ui)  
    5.5. [Paleta de Cores](#55-paleta-de-cores)  

6. [Áudio](#6-áudio)<br>
    6.1. [Trilha Sonora](#61-trilha-sonora)  
    6.2. [Efeitos Sonoros](#62-efeitos-sonoros)  
    6.3. [Dublagem](#63-dublagem)  
    6.4. [Ambiente Sonoro](#64-ambiente-sonoro)  

7. [Progresso e Salvamento](#7-progresso-e-salvamento)<br>
    7.1. [Sistema de Progressão](#71-sistema-de-progressão)  
    7.2. [Sistema de Salvamento](#72-sistema-de-salvamento)  

8. [Monetização](#8-monetização)<br>
    8.1. [Modelo de Negócio](#81-modelo-de-negócio)  
    8.2. [Itens Pagos](#82-itens-pagos)  

9. [Testes e Qualidade](#9-testes-e-qualidade)<br>
    9.1. [Testes de Jogo](#91-testes-de-jogo)  
    9.2. [Feedback dos Jogadores](#92-feedback-dos-jogadores)  

10. [Conclusão](#10-conclusão)<br>
    10.1. [Sumário](#101-sumário)  
    10.2. [Próximos Passos](#102-próximos-passos)  