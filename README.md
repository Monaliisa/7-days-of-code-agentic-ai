# #7DaysOfCode — Agentes de IA & Engenharia de Prompts (Python + LangChain)

Bem-vindo(a) ao **#7DaysOfCode de Agentes de IA e Engenharia de Prompts** da Alura! 

Neste desafio de 7 dias, **não existem exercícios soltos ou atividades extras**: **o projeto inteiro é o desafio**. A cada dia, você receberá uma nova demanda real de engenharia para evoluir o mesmo sistema — construindo, tijolo por tijolo, um **Agente Autônomo de Atendimento e Logística Reversa para o e-commerce NovaMart**.

---

## A Dinâmica do Desafio: 7 Dias, 1 Projeto Evolutivo

Você acaba de assumir a liderança técnica de IA da **NovaMart**, um grande e-commerce que sofre com milhares de chamados diários de clientes querendo rastrear pedidos, trocar produtos ou pedir reembolso.

A cada dia do **#7DaysOfCode**, uma nova funcionalidade crítica precisa entrar em produção. O resultado do **Desafio do Dia 1** é a fundação para o **Desafio do Dia 2**, que se conecta ao **Desafio do Dia 3**, até que no **Dia 7** todas as peças se unam em um **Agente Completo em Produção**:

```text
[Dia 1: Cérebro e Prompt] 
       |
       v
[Dia 2: Extração JSON/Pydantic] 
       |
       v
[Dia 3: Ferramentas / Tool Calling] 
       |
       v
[Dia 4: Ciclo ReAct de Decisão] 
       |
       v
[Dia 5: Memória Conversacional] 
       |
       v
[Dia 6: RAG nas Políticas de Troca] 
       |
       v
[Dia 7: Agente Integrado Completo da NovaMart]
```

---

## Diretriz de Complexidade e Abordagem

- **Nível:** Iniciante a Intermediário.
- **Filosofia Pedagógica:** Menos abstrações complexas de grafos e muito mais domínio real de **Engenharia de Prompts, Tool Calling, RAG e Encadeamento Lógico (LCEL)** no LangChain.
- **Como funciona cada Notebook:**
  1. **Briefing do Desafio do Dia:** Qual problema do projeto da NovaMart precisamos resolver hoje e como ele evolui o que fizemos ontem.
  2. **Fundamentação Rápida & Ferramental:** Os conceitos essenciais explicados direto no código.
  3. **Mão na Massa (A Construção do Desafio):** Passo a passo guiado para construir e validar o módulo daquele dia.
  4. **Check-point de Entrega do Dia:** Validação final do componente construído no desafio do dia (sem dar spoiler do próximo desafio).

---

## Pré-requisitos e Stack Tecnológica

### Pré-requisitos
- Conhecimento básico de **Python** (variáveis, funções, dicionários, listas);
- Chave de API do **Google Gemini** (`GOOGLE_API_KEY`, obtida gratuitamente no [Google AI Studio](https://aistudio.google.com/));
- Conta Google para rodar os notebooks no **Google Colab**.

### Stack Tecnológica
- **Linguagem:** Python 3.10+
- **Modelo (LLM & Embeddings):** Google Gemini (`gemini-3.8-flash` e `gemini-embedding-001`)
- **Orquestração:** [LangChain](https://python.langchain.com/) (`langchain`, `langchain-google-genai`, `langchain-community`)
- **Validação e Dados Estruturados:** Pydantic
- **Banco de Dados Vetorial (RAG):** ChromaDB / FAISS
- **Ambiente:** Google Colab / Jupyter Notebook

---

## Estrutura do Repositório

```text
alur-7-days-of-code-agentic-ai/
├── README.md
├── requirements.txt
├── emails-desafios/                                       # Textos dos e-mails diários (Enunciados + Dados de Apoio)
│   ├── email-dia-01.md
│   ├── email-dia-02.md
│   ├── email-dia-03.md
│   ├── email-dia-04.md
│   ├── email-dia-05.md
│   ├── email-dia-06.md
│   └── email-dia-07.md
├── notebooks/                                             # Gabaritos Oficiais (liberados no dia seguinte)
│   ├── dia-01-fundamentos-e-prompt-engineering.ipynb
│   ├── dia-02-estruturando-dados-com-json-mode.ipynb
│   ├── dia-03-tool-calling-basico.ipynb
│   ├── dia-04-o-ciclo-react-e-raciocinio.ipynb
│   ├── dia-05-memoria-e-contexto-conversacional.ipynb
│   ├── dia-06-rag-consultor-de-politicas.ipynb
│   └── dia-07-projeto-final-assistente-integrado.ipynb
└── data/                                                  # Arquivos de apoio do projeto
    ├── pedidos_novamart.json
    └── politicas_troca.txt
```

---

## Como Executar os Desafios Diários

1. Abra o **Google Colab** ([colab.research.google.com](https://colab.research.google.com/)).
2. Carregue o notebook do dia correspondente (começando por `notebooks/dia-01-fundamentos-e-prompt-engineering.ipynb`).
3. Configure sua chave `GOOGLE_API_KEY` nos **Secrets** do Colab (aba lateral de chaves) ou insira quando solicitado na célula de configuração.
4. Ao concluir a entrega de cada dia, compartilhe seu progresso com a comunidade usando a hashtag **#7DaysOfCode**!
