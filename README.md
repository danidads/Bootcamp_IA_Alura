# Bootcamp_IA_Alura
Projeto IA para Geração de Conteúdo para Consultora de Beleza

Este projeto utiliza uma cadeia de agentes de Inteligência Artificial para automatizar a criação de conteúdo estratégico sobre lançamehttps://github.com/danidads/Bootcamp_IA_Alura/blob/main/README.mdntos, cuidados com a pele e maquiagem, com foco em publicações para redes sociais.

A IA busca tendências, planeja conteúdos e escreve rascunhos otimizados para o público para consultora independente.
---

## ✨ Objetivo

Gerar conteúdo relevante e personalizado, com linguagem simples e visual atrativo, direcionado a mulheres entre 30 e 80 anos, fortalecendo a presença digital da consultora.

---

## 🧠 Visão Geral dos Agentes

### 🔍 Agente 1: Buscador de Notícias

- **Função:** Pesquisa os lançamentos mais recentes e relevantes (últimos 30 dias).
- **Fontes:** Google Search e site oficial.
- **Critério:** Traz até 5 lançamentos com maior destaque e entusiasmo nas notícias.
- **Ferramenta:** `google_search`
- **Modelo:** `gemini-2.0-flash`

🧠 Agente 2: Planejador de Posts
Função: Analisa os lançamentos mais recentes e cria um plano estratégico com os principais pontos que devem ser abordados em posts.

Fontes: Google Search e site oficial.

Critério: Avalia relevância e potencial de engajamento de cada lançamento, selecionando o melhor tema para ser trabalhado nos posts.

Ferramenta: google_search

Modelo: gemini-2.0-flash

✍️ Agente 3: Redator do Post
Função: Escreve 5 rascunhos criativos e envolventes de posts para Instagram, voltados ao público de jovens senhoras (30 a 80 anos), com base no tema escolhido pelo Planejador.

Fontes: Google Search e site oficial.

Critério: Linguagem simples, tom engajador, informativo, com até 4 hashtags e referências reais dos produtos/temas abordados.

Modelo: gemini-2.0-flash

📝 Agente 4: Revisor de Qualidade
Função: Revisa os rascunhos criados para garantir clareza, correção, tom adequado e impacto para o público jovem (18 a 30 anos) do Instagram.

Critério: Aprova textos prontos para publicação ou aponta melhorias necessárias com sugestões de ajustes.

Modelo: gemini-2.0-flash

