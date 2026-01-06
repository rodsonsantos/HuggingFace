# 🤖 Modelos de NLP com Hugging Face (Python)

Repositório dedicado a **experimentos práticos com modelos de Inteligência Artificial e Processamento de Linguagem Natural (NLP)** utilizando a biblioteca **Hugging Face Transformers**.

O objetivo é explorar o uso de **modelos pré-treinados**, com foco em aplicações reais, simples e reutilizáveis, especialmente para análise de sentimentos e classificação de textos em português.

Este projeto faz parte do meu portfólio de aprendizado contínuo em **dados, IA aplicada e automação de análises textuais**.

---

## 🎯 Objetivo do Repositório

- Aplicar modelos de NLP pré-treinados em cenários reais 
- Desenvolver scripts simples, claros e reutilizáveis  
- Explorar o uso de IA em contextos como atendimento ao cliente e feedbacks  

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Hugging Face Transformers**
- **Modelos BERT pré-treinados**
- **Google Colab**
- **VS Code**

---

## 💬 Projeto 1 — Analisador de Sentimentos  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_YHQF2eUSwjSb6W5LCafGRcJIN3SuJTe?usp=sharing)

### 🧩 Descrição  
Um script simples que utiliza o modelo `pysentimiento/bertweet-pt-sentiment` para identificar o sentimento de frases em português.

### ⚙️ Funcionalidades  
- Entrada de texto digitada pelo usuário 🧍‍♂️  
- Análise automática via IA 🤖  
- Retorno do sentimento: **POSITIVO**, **NEGATIVO** ou **NEUTRO**  
- Exibição do score de confiança  

---

## ⭐ Projeto 2 — Classificador de Reclamações (1 a 5 estrelas)  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1anwZqIDAhVV0UiDys5LEDszKIJcZA2G3?usp=sharing)

### 🧩 Descrição  
Este script classifica textos avaliativos (ex.: reclamações ou feedbacks) atribuindo uma nota de **1 a 5 estrelas** com o modelo  
`nlptown/bert-base-multilingual-uncased-sentiment`.

Ideal para treinar categorização de mensagens em cenários de atendimento ao cliente.

### ⚙️ Funcionalidades  
- Recebe a reclamação via input  
- Classifica de **1 ⭐ a 5 ⭐**  
- Converte a nota em categorias:
  - **1 ⭐ — ⚠️ Problema Grave**  
  - **2 ⭐ — ⚠️ Reclamação**  
  - **3 ⭐ — 😐 Neutro**  
  - **4 ⭐ — 😊 Satisfeito**  
  - **5 ⭐ — 🤩 Muito satisfeito / Elogio**  
- Mostra o score de confiança do modelo  

---

## 📌 Considerações Finais

Este repositório demonstra minha capacidade de:

- Utilizar modelos de IA pré-treinados
- Aplicar NLP em problemas reais
- Interpretar resultados de modelos de linguagem
- Criar soluções simples e funcionais com Python

Os projetos aqui apresentados servem como base para futuras integrações com **pipelines de dados, APIs, bancos de dados e sistemas de atendimento**.

---

## 📬 Contato

- LinkedIn: https://www.linkedin.com/in/rodsonsantos/  
- GitHub: https://github.com/rodsonsantos

Sinta-se à vontade para dar uma olhada no código-fonte e testar novas ideias! 🚀





