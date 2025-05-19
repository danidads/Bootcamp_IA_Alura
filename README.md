# Bootcamp_IA_Alura
Projeto IA para Geração de Conteúdo para Consultora de Beleza

Este projeto utiliza uma cadeia de agentes de Inteligência Artificial para automatizar a criação de conteúdo estratégico sobre lançamentos, cuidados com a pele e maquiagem, com foco em publicações para redes sociais.

A IA busca tendências, planeja conteúdos e escreve rascunhos otimizados para o público para consultora independente.
---

## ✨ Objetivo

Gerar conteúdo relevante e personalizado, com linguagem simples e visual atrativo, direcionado a mulheres entre 30 e 80 anos, fortalecendo a presença digital da consultora.

---

## 🧠 Visão Geral dos Agentes

### 🔍 Agente 1: Buscador de Notícias

- **Função:** Pesquisa os lançamentos mais recentes e relevantes da Mary Kay (últimos 30 dias).
- **Fontes:** Google Search e site oficial da Mary Kay Brasil.
- **Critério:** Traz até 5 lançamentos com maior destaque e entusiasmo nas notícias.
- **Ferramenta:** `google_search`
- **Modelo:** `gemini-2.0-flash`

```python
lancamentos = agente_buscador(topico, data_de_hoje)

## 🗂️ Agente 2: Planejador de Posts

- **Função:** Analisa os lançamentos encontrados e planeja os principais pontos para os posts.
- **Ação:** Aprofunda informações usando Google Search e site oficial.
- **Resultado:** Escolhe o lançamento mais relevante para ser transformado em conteúdo.
- **Modelo:** `gemini-2.0-flash`

```python
plano = agente_planejador(topico, lancamentos)
