# BS - XAI Decision Explorer AIR PLD

### Explainable Artificial Intelligence Platform

Plataforma para homologação, explicabilidade e linhagem de decisões do AIR PLD utilizando conceitos de Explainable Artificial Intelligence (XAI).

> **Transformando uma Black Box em uma Glass Box através dos princípios da Explainable Artificial Intelligence.**

---

## O que é XAI?

A Inteligência Artificial Explicável (Explainable Artificial Intelligence – XAI) é um conjunto de métodos e práticas que torna compreensíveis as decisões produzidas por sistemas inteligentes. Em vez de apresentar apenas um resultado, a XAI busca responder perguntas como:

- Por que esta decisão foi tomada?
- Quais informações contribuíram para esse resultado?
- Quais regras ou modelos foram utilizados?
- Como a decisão pode ser auditada e validada?

O objetivo é permitir que pessoas compreendam, validem e confiem nas decisões produzidas por sistemas computacionais.

---

## O conceito aplicado neste projeto

Embora o AIR PLD seja baseado em regras de negócio, este projeto adota os princípios da XAI para tornar todo o processo de decisão transparente.

O sistema foi concebido para transformar o processo de homologação em um ambiente de investigação, permitindo visualizar toda a linhagem da decisão (*Decision Lineage*), desde a origem dos dados até a regra responsável pela marcação do documento.

Na prática, a plataforma procura transformar uma **caixa-preta (Black Box)** em uma **caixa de vidro (Glass Box)**, onde cada etapa da decisão pode ser explorada, compreendida e validada pelo analista.

---

## Por que XAI?

Embora a Explainable Artificial Intelligence seja frequentemente associada a modelos de Machine Learning, seus princípios podem ser aplicados a qualquer processo automatizado de tomada de decisão. Neste projeto, a XAI é utilizada para explicar decisões baseadas em regras de negócio, permitindo rastrear sua origem, compreender sua lógica e validar cada etapa do processo de homologação.

---

## Objetivo

Disponibilizar aos analistas uma plataforma intuitiva para compreender, validar e homologar decisões produzidas pelo AIR PLD, aplicando os princípios da Explainable Artificial Intelligence (XAI) para tornar transparente, auditável e rastreável um motor de decisão baseado em regras. 

O propósito da plataforma é explicar a decisão por meio da apresentação estruturada dos dados, permitindo que o analista compreenda não apenas **o que aconteceu**, mas principalmente **por que aconteceu**.

---

## Filosofia do Projeto

O desenvolvimento desta plataforma é guiado pelos seguintes princípios:

- Explicabilidade antes da tecnologia.
- Toda decisão deve ser compreensível.
- Toda marcação deve ser rastreável.
- A homologação deve ser intuitiva.
- O analista não precisa conhecer a estrutura do banco de dados.
- A interface deve explicar decisões por meio da apresentação dos dados.


## Roadmap


## Roadmap

### MVP v0.1

✅ Definição da arquitetura

✅ Documentação inicial

🚧 Dashboard XAI

🚧 Explorar Cenários

🚧 Documento

🚧 Decision Lineage

### v0.2

📌 Rule Explorer

📌 XAI Explainability

📌 Dashboard Analytics

### v1.0

🎯 Plataforma completa


## Legenda

✅ Concluído
🚧 Em desenvolvimento
📌 Planejado
🎯 Objetivo final

---

## Arquitetura
A plataforma foi concebida seguindo uma arquitetura em camadas, separando interface, regras de negócio, serviços e persistência de dados, permitindo evolução contínua e baixo acoplamento entre os componentes.

Backend

- Python
- Flask

Frontend

- Bootstrap 5
- Plotly
- DataTables
- Cytoscape.js

Persistência

- MongoDB


---

## Visão

O XAI Decision Explorer AIR PLD não foi concebido apenas como uma ferramenta de consulta de dados.

Seu propósito é permitir que analistas compreendam, validem e expliquem decisões de negócio através da apresentação estruturada dos dados, da visualização da linhagem da decisão (*Decision Lineage*) e da aplicação dos princípios da Explainable Artificial Intelligence (XAI).
