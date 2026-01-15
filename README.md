# 🤖 Tech News Curator (n8n) 🚀

Projeto de **curadoria automática de notícias** sobre **Inteligência Artificial** e **Tecnologia**, focado em **desenvolvedores**, utilizando **n8n** como orquestrador de automações.

O workflow coleta notícias de múltiplas fontes via RSS, analisa o conteúdo com IA e gera um **resumo diário conciso em Markdown**, pronto para publicação.

---

## ⚙️ Como funciona o workflow

1. ⏰ **Schedule Trigger** — Executa automaticamente em horário definido
2. 📰 **RSS Feed Read** — Coleta notícias de fontes confiáveis (ex: G1, Dev.to)
3. ✂️ **Limit / Merge** — Controla quantidade e unifica os artigos
4. 🧩 **Aggregate / Split Out** — Organiza os dados para processamento
5. 🤖 **LLM (IA)** — Seleciona e resume as notícias mais relevantes
6. 💬 **Discord Webhook** — Publica automaticamente o resumo diário

---

## ✨ Funcionalidades

- 🔍 Curadoria inteligente de notícias
- 🧠 Foco em IA, ML e Tecnologia para devs
- 📰 Seleção de até 3 notícias mais relevantes
- ✍️ Resumos com até 50 palavras
- 📄 Saída formatada em **Markdown**
- ⚡ Totalmente automatizado com **n8n**
- 💬 Integração com **Discord**

---

## 📥 Formato de Entrada

As notícias são recebidas automaticamente via **RSS** e processadas no seguinte formato:

```json
{
  "title": "Título do Artigo",
  "url": "https://exemplo.com",
  "content": "Conteúdo completo do artigo..."
}
📤 Formato de Saída
Mensagem única em Markdown

Estrutura clara e padronizada

Ideal para:

Discord

Telegram

Newsletters

Dashboards técnicos

🛠️ Tecnologias Utilizadas
n8n (Automação e orquestração)

RSS

Inteligência Artificial (LLM)

Markdown

Webhooks (Discord)

🚀 Possíveis Melhorias
Adicionar mais fontes RSS

Filtro por stack (Java, JS, Python, etc.)

Histórico diário de resumos

Suporte multilíngue

Publicação em múltiplos canais

📄 Licença
Projeto open-source para fins educacionais e profissionais.
