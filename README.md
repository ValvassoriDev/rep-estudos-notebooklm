# miniguia-estudos-notebooklm

## Projeto de Estudo — Modelos de Linguagem e Engenharia de Prompt

---

## Contexto e Objetivos

Este projeto foi desenvolvido como parte do desafio prático da DIO com o objetivo de utilizar Inteligência Artificial como ferramenta de aprendizagem ativa, organização de conhecimento e desenvolvimento de maturidade técnica.

O tema escolhido para o caderno temático foi **Modelos de Linguagem e Engenharia de Prompt**, com foco em compreender como funcionam os LLMs (Large Language Models), o processamento de linguagem natural (PLN), tokens, janela de contexto e boas práticas para criação de prompts eficientes.

A escolha desse tema surgiu pela crescente importância da IA no desenvolvimento de software, automação de tarefas e suporte à tomada de decisão técnica.

### Objetivos principais:

* Entender como modelos de linguagem processam informações
* Compreender o funcionamento de tokens e janela de contexto
* Aprender como melhorar respostas através da engenharia de prompts
* Desenvolver pensamento crítico no uso de IA
* Criar um material reutilizável para estudos futuros e preparação para entrevistas técnicas

---

## Curadoria de Fontes

Foram selecionadas 5 fontes abertas para upload e análise no NotebookLM.

### 1. Attention Is All You Need

Artigo responsável pela introdução da arquitetura Transformer, base dos modelos modernos de IA generativa.

Link: https://arxiv.org/abs/1706.03762

Motivo da escolha: compreender a base técnica dos LLMs.

---

### 2. Prompt Engineering Guide

Guia completo com boas práticas para criação de prompts eficientes.

Link: https://www.promptingguide.ai/

Motivo da escolha: aprofundar técnicas práticas de engenharia de prompt.

---

### 3. Documentação Oficial da OpenAI — Prompt Engineering

Material oficial com recomendações e padrões para melhor interação com modelos de IA.

Link: https://platform.openai.com/docs/guides/prompt-engineering

Motivo da escolha: utilizar referência confiável e aplicada ao mercado.

---

### 4. Google Machine Learning Glossary

Material introdutório sobre NLP, Machine Learning e conceitos fundamentais.

Link: https://developers.google.com/machine-learning/glossary

Motivo da escolha: reforçar fundamentos conceituais.

---

### 5. NotebookLM

Ferramenta utilizada para organizar, resumir e consultar os conteúdos estudados.

Link: https://notebooklm.google.com/

Motivo da escolha: aplicar IA no processo de aprendizagem ativa.

---

## Engenharia de Prompts e “Cicatrizes”

Durante o desenvolvimento deste estudo, diversos prompts foram testados até encontrar respostas mais úteis, técnicas e alinhadas com o objetivo do projeto.

Essa etapa foi importante para entender que a qualidade da resposta depende diretamente da qualidade da pergunta.

---

### Caso 1 — Tokens em Modelos de Linguagem

### Prompt Inicial

> Explique o que são tokens em modelos de linguagem.

### Problema Encontrado

A resposta foi superficial, genérica e sem conexão com aplicações reais.

---

### Prompt Refinado

> Explique o que são tokens em LLMs com foco em janela de contexto, exemplos práticos e aplicação em entrevistas técnicas.

### Resultado

A resposta ficou mais técnica, aplicável e útil para revisão profissional.

---

### Caso 2 — Processamento Duplicado em Sistemas

### Prompt Inicial

> Como evitar processamento duplicado em sistemas distribuídos?

### Problema Encontrado

A resposta ficou avançada demais para nível estágio/júnior.

---

### Prompt Refinado

> Explique como um desenvolvedor júnior pode evitar processamento duplicado em transações financeiras usando exemplos simples e práticos.

### Resultado

A resposta ficou mais adequada para entrevistas e aprendizado inicial.

---

### Principais Lições Aprendidas

* Prompts genéricos geram respostas genéricas
* Quanto mais contexto, melhor a resposta
* Informar o nível técnico esperado melhora muito a precisão
* Refinar prompts faz parte do processo profissional
* Mostrar erros e ajustes demonstra maturidade técnica

---

# Miniguia de Estudo (Entrega Final)

---

## Resumos Estruturados

### O que são LLMs

LLMs (Large Language Models) são modelos de Inteligência Artificial treinados com grandes volumes de texto para compreender, prever e gerar linguagem natural.

Eles são utilizados para responder perguntas, resumir conteúdos, traduzir idiomas, gerar código e automatizar tarefas complexas.

Sua principal base tecnológica é a arquitetura Transformer.

---

### O que são Tokens

Tokens são as unidades básicas usadas pelo modelo para processar texto.

Eles podem representar:

* palavras completas
* partes de palavras
* caracteres
* números
* símbolos

Exemplo:

A frase:

"ChatGPT ajuda muito"

pode ser dividida em vários tokens dependendo do modelo.

---

### Janela de Contexto

A janela de contexto é o limite máximo de tokens que o modelo consegue manter em memória temporária durante uma conversa.

Quando esse limite é atingido, os tokens mais antigos geralmente são descartados para permitir a entrada de novos.

Isso impacta diretamente na continuidade e coerência das respostas.

---

### Engenharia de Prompt

É o processo de criar instruções melhores para obter respostas melhores da IA.

Um bom prompt geralmente contém:

* contexto
* objetivo claro
* restrições
* formato desejado
* nível técnico esperado

---

### Como Modelos Respondem Prompts

Os modelos não consultam respostas prontas em um banco de dados.

Eles utilizam probabilidades baseadas em padrões aprendidos durante o treinamento para prever qual será o próximo token mais adequado.

Isso permite respostas coerentes e contextualizadas.

---

## Glossário

| Termo          | Significado                              |
| -------------- | ---------------------------------------- |
| Token          | Unidade básica de processamento de texto |
| Prompt         | Instrução enviada ao modelo              |
| LLM            | Large Language Model                     |
| NLP            | Natural Language Processing              |
| Transformer    | Arquitetura-base dos LLMs                |
| Context Window | Limite de memória temporária             |
| Fine-tuning    | Ajuste adicional do modelo               |
| Embedding      | Representação vetorial de texto          |

---

## Prompts Reutilizáveis

### Para Revisão Técnica

> Explique [tema] de forma técnica e objetiva para entrevista de desenvolvedor júnior.

---

### Para Comparação de Conceitos

> Compare [conceito A] e [conceito B] com exemplos práticos aplicados ao desenvolvimento de software.

---

### Para Troubleshooting

> Identifique possíveis falhas nesta abordagem e proponha melhorias com foco em boas práticas.

---

### Para Resumo de Conteúdo

> Resuma este conteúdo em formato de revisão rápida para estudo.

---

### Para Aprofundamento

> Explique este tema como se eu fosse um desenvolvedor iniciante, mas com profundidade suficiente para entrevista técnica.

---

## Conclusão

Este projeto mostrou que utilizar IA vai muito além de pedir respostas prontas.

A verdadeira evolução acontece quando usamos a IA como ferramenta de raciocínio, análise crítica e construção de conhecimento.

A experiência com NotebookLM reforçou a importância da curadoria de fontes, da engenharia de prompts e da documentação do processo de aprendizagem.

Esse repositório representa não apenas um estudo técnico, mas também uma demonstração prática de maturidade profissional e capacidade de aprendizado contínuo.

---

## Autor

Projeto desenvolvido para o desafio prático da DIO com foco em aprendizado ativo, IA aplicada aos estudos e fortalecimento de portfólio profissional.
