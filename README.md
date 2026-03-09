![GitHub License](https://img.shields.io/github/license/gabrieldasilvabispo/lab-redes01)

# Laboratorio de redes 01 - projetos de rede local
Projeto desenvolvido na disciplica de redes de computadores no curso tecnico de informática do Senac

aluno: Gabriel da Silva Bispo

professor: José de assis 

Data: 09/03/2025

---

##1. Objetivo
implementar uma rede local simples conectando  3  notebooks a um roteador simples com switch intergrado e uma impressora de rede.

o projeto sere realizado em duas etapas 

1. simulação da rede no cisco packet tracer
2. implementação da rede no laboratorio real

---

## 2. equipamentos utilizados neste laboratorio 

- 3 três notebooks
- 1 roteador wireles com 1 porta WAN e 4 portas LAN
- 1 impressora de rede

---


##3. Topologia da rede 
diagrama logico da rede utilizada neste laboratorio:

``` mermaid
graph TD



WAN[ internet / WAN de provedor]

Router[Roteador wireless<br>1 porta WAN<br>4 portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[impressra de rede]

WAN --->|Porta WAN| Router

Router -->|LAN 1| PC1
Router -->|LAN 2| PC2
Router -->|LAN 3| PC3
Router -->|LAN 4| Printer



