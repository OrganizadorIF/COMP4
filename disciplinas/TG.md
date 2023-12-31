---
layout: default
title: Teoria dos Grafos
parent: Disciplinas
nav_order: 3
---

<h1 align="center"><span style='font-weight: bold;'>Teoria dos Grafos</span></h1>

<h2 style="color: black;" align="center"><span style='font-weight: bold;'>Professor(a):</span> Diego Saqui</h2>

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Mapa Conceitual</span></h2>

<img src="https://raw.githubusercontent.com/OrganizadorIF/COMP4/main/assets/images/mapagrafos.png" alt="Mapa Conceitual" style="width: 90%; margin-left: auto; margin-right: auto; display: block;">

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Resumo</span></h2>

<div style="text-align: justify; margin-bottom: 20px;">"Teoria dos Grafos" é uma disciplina fundamental na Ciência da Computação que estuda as propriedades, representações e algoritmos relacionados a estruturas gráficas. Grafos são representações abstratas de conexões entre entidades, compostos por vértices (ou nós) conectados por arestas (ou conexões). Essa disciplina explora conceitos como tipos de grafos (dirigidos, não-direcionados, ponderados), algoritmos de busca (como busca em largura e busca em profundidade), algoritmos de caminho mínimo, algoritmos de árvore geradora mínima (como algoritmo de Prim e algoritmo de Kruskal), entre outros. A Teoria dos Grafos é amplamente aplicada em áreas como redes de computadores, análise de algoritmos, modelagem de sistemas, planejamento de rotas, e diversas outras áreas onde a relação entre elementos pode ser representada por meio de conexões.</div>

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Conceitos Importantes</span></h2>

<h3 style="color: black; margin-bottom: 10px;" align="center"><span style='font-weight: bold;'><u>Grafos</u></span></h3>

<div style="text-align: justify; margin-bottom: 10px;">Estrutura matemática que consiste em um conjunto de vértices (pontos ou nós) conectados por arestas (linhas ou conexões). Essa representação abstrata é utilizada para modelar relacionamentos entre entidades, onde os vértices representam os elementos e as arestas indicam as relações entre esses elementos. Os grafos podem ser direcionados (quando as arestas têm uma direção) ou não-direcionados (quando as conexões são bidirecionais), e podem incluir pesos para representar custos ou valores associados às conexões. Essa estrutura é fundamental para a resolução de problemas de otimização, redes, algoritmos de caminho e diversas outras aplicações computacionais.</div>

<h3 style="color: black; margin-bottom: 10px;" align="center"><span style='font-weight: bold;'>Exemplo de Grafo</span></h3>

<img src="https://upload.wikimedia.org/wikipedia/commons/3/31/Ciclo_em_um_grafo.png" alt="Exemplo de Grafo" style="width: 90%; margin-left: auto; margin-right: auto; display: block;">

<h3 style="color: black; margin-bottom: 10px; margin-top: 20px;" align="center"><span style='font-weight: bold;'><u>Árvores</u></span></h3>

<div style="text-align: justify; margin-bottom: 10px;">Tipo especial de grafo sem ciclos, formado por vértices conectados de modo que exista um único caminho entre quaisquer dois vértices. Ela é um grafo conexo, ou seja, todos os vértices estão interligados, e não possui ciclos, o que significa que não há caminhos fechados. Além disso, uma árvore com n vértices sempre terá n−1 arestas. As árvores são fundamentais na modelagem de hierarquias, estruturas de dados como árvores binárias, algoritmos de busca e na resolução de problemas em diversas áreas, como computação, biologia, redes e otimização.</div>

<h3 style="color: black; margin-bottom: 10px;" align="center"><span style='font-weight: bold;'>Exemplo de Árvore</span></h3>

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/24/Tree_graph.svg/1200px-Tree_graph.svg.png" alt="Exemplo de Árvore" style="width: 60%; margin-left: auto; margin-right: auto; display: block;">

<h2 style="color: black; margin-bottom: 20px; margin-top: 20px;" align="center"><span style='font-weight: bold;'>Materiais de Estudo</span></h2>

**Vídeos:**
   - [Aula 01 – Introdução e Propriedades](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384272)
   - [Aula 02 – Classes de Grafos](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384275)
   - [Aula 03 – Passeios, trilhas e caminhos](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384278)
   - [Aula 04 – Representações computacionais de grafos](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384291)
   - [Aula 05 – Manipulação de Grafos com Python e Networx](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384294)
   - [Aula 06 – Isomorfismo](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384296)
   - [Aula 07 – Conectividade em Grafos e Métricas](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384298)
   - [Aula 08 – Passeios em Grafos Conexos, Random Walks e Cadeias de Markov –Parte 01](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384309)
   - [Aula 09 – Passeios em Grafos Conexos, Random Walks e Cadeias de Markov – Parte 02](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384311)
   - [Aula 10 – Page Rank](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384315)
   - [Aula 11 – Árvores](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384326)
   - [Aula 12 – Árvores Spanning e código de Prüfer](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384328)
   - [Aula 13 – Algoritmo de Kruskal](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384330)
   - [Aula 15 - Busca em Largura](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384346)
   - [Aula 16 – Busca em Largura – Algoritmo Backtracking](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384348)
   - [Aula 17 – Busca em Profundidade](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384351)
   - [Aula 18 – Ordenação Topológica](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384353)
   - [Aula 19 - Algoritmo de Dijkstra](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384362)
   - [Aula 21- Heurística AStar](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384365)
  
**PDFs/Slides:**
   - [Aula 01 – Introdução e Propriedades](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384273)
   - [Aula 02 – Classes de Grafos](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384276)
   - [Aula 03 – Passeios, trilhas e caminhos](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384279)
   - [Aula 04 – Representações computacionais de grafos](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384292)
   - [Aula 05 – Manipulação de Grafos com Python e Networx](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384294)
   - [Aula 06 – Isomorfismo](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384297)
   - [Aula 07 – Conectividade em Grafos e Métricas](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384299)
   - [Aula 08 – Passeios em Grafos Conexos, Random Walks e Cadeias de Markov –Parte 01](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384310)
   - [Aula 09 – Passeios em Grafos Conexos, Random Walks e Cadeias de Markov – Parte 02](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384312)
   - [Aula 10 – Page Rank](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384316)
   - [Aula 11 – Árvores](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384325)
   - [Aula 12 – Árvores Spanning e código de Prüfer](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384327)
   - [Aula 13 – Algoritmo de Kruskal](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384329)
   - [Aula 15 - Busca em Largura](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384345)
   - [Aula 16 – Busca em Largura – Algoritmo Backtracking](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384347)
   - [Aula 17 – Busca em Profundidade](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384350)
   - [Aula 18 – Ordenação Topológica](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384352)
   - [Aula 19 - Algoritmo de Dijkstra](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384361)
   - [Aula 21- Heurística AStar](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384364)
  
**Complementares:**
  - [Jure Leskovec](https://presencial.muz.ifsuldeminas.edu.br/mod/url/view.php?id=384274)

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Atividades</span></h2>
  
**Lista de Exercícios:**
  - [Atividade 1](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=384281)
  - [Atividade 2](https://presencial.muz.ifsuldeminas.edu.br/pluginfile.php/446832/mod_assign/introattachment/0/Atividade%20de%20Treino%202.pdf?forcedownload=1)

<h2 style="color: black;  margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Colab</span></h2>

Seção voltada para a colaboração entre os alunos.

Links abertos com resumos, anotações e materiais de revisão.
