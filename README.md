# Gustavo Henrique Magalhães Silva

Construo agentes e automações com LLM para problemas de operação: atendimento, triagem, consulta a políticas internas e lucro de loja em marketplace.

Antes disso, trabalhei 3 anos na EY como consultor de Tech Risk (ITGC, SOX, LGPD, ISO 27001). Isso aparece no jeito que eu construo: regra que não pode falhar fica no código, não no prompt, e nada é dado como pronto sem avaliação medida.

## Trabalho em empresa

Projetos internos. O código fica com a empresa, então aqui vai o que foi feito e o resultado.

### Agente de Ocorrência

Empresa de telecom. Ferramentas: Copilot Studio, Power Apps, Power Automate, SharePoint e Power BI.

A área comercial recebia cerca de 600 ocorrências por mês, e cada uma era aberta, acompanhada e fechada de um jeito diferente. Construí um agente que centralizou a abertura, o fechamento e a visualização de todas elas num lugar só.

- Com os dados num lugar só, um painel no Power BI passou a mostrar em que área estavam os gargalos e onde dava para ajudar.
- O tempo médio de resposta ao cliente caiu de 5 a 6 dias para 1 a 2 dias.
- O head de operações passou a ter uma visão geral da área.

### Agentes da esteira de delivery

Ferramentas: agentes e skills no Claude, API do banco de dados interno, planilhas compartilhadas e Power BI.

Criei agentes e skills, usados dentro do Claude, para acompanhar a esteira interna de delivery.

- Os agentes leem os dados pela API do banco interno e pelas planilhas compartilhadas e centralizam tudo no Power BI.
- Com ajuda de LLM, apontam onde a esteira pode melhorar e encontram gargalos pequenos que atrasavam o trabalho em dias.
- Também ajudam a montar as apresentações para a diretoria (C-level).

## Projetos de portfólio

| Projeto | Problema | Resultado medido | Stack |
|---|---|---|---|
| [Patas & Cia](https://github.com/GustavoHMS21/Agente-Clinica-Pata-e-Cia) | Clínica veterinária com 60 conversas de WhatsApp por dia e uma recepcionista | 97% no eval com o modelo real, 36 de 36 ataques de prompt barrados, US$ 0,0095 por mensagem | Claude, FastAPI, SQLite |
| [Rota Sul RH](https://github.com/GustavoHMS21/rota-sul-rag-rh) | RH de 3 pessoas recebendo 350 perguntas por mês sobre políticas | 61 de 61 respostas certas, 43 de 43 citações certas, 10 de 10 manipulações barradas | RAG com pgvector, bge-m3, Groq, FastAPI |
| [GSeller](https://github.com/GustavoHMS21/GSeller) ([demo](https://g-seller.vercel.app)) | Seller de Mercado Livre e Shopee que não sabe quanto lucrou em cada pedido | Painel no ar, com as regras de lucro em funções puras testadas | Next.js, TypeScript |
| [Triagem de e-mails](https://github.com/GustavoHMS21/triagem-emails-llm) | Vazamento e gás esperando na fila atrás de pedido de segunda via | Fila por setor e urgência, LLM local com JSON validado, CI com Postgres real | Qwen3 (Ollama), Pydantic, Postgres, Streamlit |
| [Tech Challenge](https://github.com/GustavoHMS21/postech-tech-challenge-fase1-cancer-mama) | Apoio ao diagnóstico de câncer de mama | Recall de 0,952 nos casos malignos, com explicação por SHAP | scikit-learn, SHAP, Streamlit |

As empresas dos casos são fictícias. Os números saem das avaliações e testes que estão em cada repositório.

## Tempo de construção

Pelo histórico de commits:

- Patas & Cia: 3 dias (6 a 8 de outubro de 2026)
- Triagem de e-mails: 3 dias (3 a 5 de outubro de 2026)
- GSeller: 8 dias (8 a 15 de outubro de 2026)
- Rota Sul RH: 12 dias (26 de setembro a 7 de outubro de 2026)

## Estudando agora

Java com Spring Boot e AWS Cloud Practitioner (com um [simulador de prova](https://github.com/GustavoHMS21/Treino-AWS) que fiz para mim).
