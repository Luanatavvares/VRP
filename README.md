

# VRPTW - Algoritmo Genético Híbrido

Este repositório contém a implementação desenvolvida durante um projeto de **Iniciação Científica** na Universidade Federal de Viçosa, cujo objetivo foi estudar métodos de **computação evolutiva** aplicados ao **Problema de Roteamento de Veículos com Janelas de Tempo (VRPTW)**.

O trabalho foi realizado no contexto do programa **PIBIC/FAPEMIG**, com orientação do professor Marcus Henrique Soares Mendes.

## Sobre o projeto

O projeto investiga o uso de **Algoritmos Genéticos combinados com técnicas de busca local** para resolver instâncias clássicas do VRPTW.

A implementação foi desenvolvida em **Python**, utilizando a biblioteca **DEAP** para construção do algoritmo evolutivo.

Os experimentos foram realizados utilizando instâncias clássicas de benchmark amplamente utilizadas na literatura:

* Instâncias de **Solomon**
* Instâncias de **Homberger**

Os resultados obtidos são comparados com os melhores valores conhecidos da literatura para avaliar o desempenho do método.

## Estrutura do repositório

```
.
├── instancias/        # Conjuntos de instâncias utilizados nos experimentos
├── src/               # Implementação do algoritmo
├── resultados/        # Resultados obtidos nos experimentos
├── scripts/           # Scripts auxiliares para execução e análise
└── README.md
```

## Tecnologias utilizadas

* Python
* DEAP (Distributed Evolutionary Algorithms in Python)
* Algoritmos Genéticos
* Busca Local



