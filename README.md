# Projeto: Exploração do Copilot e Ferramentas de Criação Assistida com Inteligência Artificial

## 🎯 Objetivo

Este projeto tem como objetivo explorar e aplicar recursos de **inteligência artificial generativa** utilizando:

- Microsoft 365 Copilot
- Azure OpenAI Service
- Filtros de conteúdo (Content Filters)

As atividades foram estruturadas a partir dos laboratórios do Microsoft Learn e incluem **exemplos de uso, prompts aplicados, testes com filtros de segurança e anotações dos aprendizados adquiridos**.

---

## 📚 Laboratórios Utilizados

- [Lab 12 – Microsoft Copilot e IA Generativa](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)
- [Lab 13 – Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html)
- [Lab 14 – Filtros de Conteúdo no Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai-content-filters.html)

---

## 🧩 Estrutura do Projeto

```bash
📁 projeto-copiloto-openai/
├── exemplos-copilot/
│   └── planilha-automatizada.md
│   └── relatorio-gerado-word.md
│
├── exemplos-openai/
│   └── prompts-gerativos.txt
│   └── codigo-python-gerado.md
│
├── filtros-conteudo/
│   └── testes-moderacao.md
│   └── politicas-configuradas.md
│
├── imagens/
│   └── captura-copilot-excel.png
│   └── filtro-bloqueado-output.png
│
├── insights.md
└── README.md

```

🔹 Etapa 1: Exploração do Microsoft Copilot
Ferramentas Utilizadas:

Word: geração de relatórios automáticos

Excel: análise de dados com comandos em linguagem natural

Outlook: criação de e-mails baseados em contexto

Exemplo de prompt aplicado (Excel):

“Crie um gráfico de barras com os cinco produtos mais vendidos em abril.”

Exemplo de prompt aplicado (Word):

“Gere um resumo executivo com base neste relatório de vendas.”

Resultados:

Geração precisa de conteúdo, desde que os dados estejam estruturados.

A IA entende comandos naturais, reduzindo o tempo de execução de tarefas complexas.

🔹 Etapa 2: Interação com Azure OpenAI
Ambiente:

Azure OpenAI Playground

Modelos: GPT-35-Turbo, GPT-4, DALL·E, Whisper

Tipos de tarefas realizadas:

Geração de texto

Tradução multilíngue

Escrita de código

Criação de imagens com DALL·E

Exemplos de prompts:

text
Copiar
Editar
"Explique em linguagem simples como funciona o aprendizado supervisionado na IA."
"Gere um resumo em inglês deste texto sobre biodiversidade."
"Crie uma função em Python que leia um CSV e calcule a média por coluna."
Resultados:

A qualidade do conteúdo melhora com o uso de parâmetros como temperature, max_tokens e stop sequence.

Prompts detalhados geram respostas mais precisas e úteis.

🔹 Etapa 3: Testes com Filtros de Conteúdo
Objetivo:
Garantir que os conteúdos gerados estejam em conformidade com políticas de segurança, privacidade e ética.

Testes realizados:

Bloqueio de entrada com conteúdo ofensivo

Detecção de respostas com teor sexual, violento ou autodestrutivo

Aplicação de diferentes níveis de sensibilidade nos filtros

Exemplo de input bloqueado:

Prompt com linguagem imprópria → Bloqueado por input filter

Exemplo de saída moderada:

Resposta do modelo com conteúdo sensível → Interceptado por output filter

Conclusões:

Os filtros são eficazes e altamente configuráveis.

É possível ajustar o nível de rigor de acordo com o tipo de aplicação (educacional, empresarial, etc).

📈 Aprendizados
O Copilot aumenta significativamente a produtividade em tarefas cotidianas no Office.

O Azure OpenAI permite aplicações avançadas de IA com alta flexibilidade e controle.

Filtros de conteúdo são essenciais para uso responsável da IA, sobretudo em contextos sensíveis.

📌 Requisitos para Execução
Conta no Microsoft 365 com acesso ao Copilot

Conta Azure com permissão para uso do Azure OpenAI

Acesso ao portal Azure e Azure OpenAI Studio

🔗 Referências
Microsoft Learn – AI Fundamentals

Documentação do Copilot

Azure OpenAI Service

Content Filtering no Azure OpenAI

📬 Contato
Este projeto foi desenvolvido com fins educacionais no contexto do curso de Fundamentos de IA da Microsoft e Bootcamp DIO - XP Inc. Cloud com Inteligência Artificial.
