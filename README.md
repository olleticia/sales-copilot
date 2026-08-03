# Sales Copilot

Sales Copilot é uma aplicação que analisa transcrições de reuniões comerciais utilizando Inteligência Artificial e gera insights para apoiar vendedores durante o processo comercial.

O projeto foi desenvolvido como parte de um desafio técnico da ZapSign, utilizando ferramentas no-code e low-code para construir uma solução funcional de ponta a ponta.

---

## Objetivo

Receber uma transcrição (.txt) de uma reunião de vendas e gerar automaticamente:

- Resumo executivo da conversa
- Score de oportunidade
- Principais insights do cliente
- Avaliação da metodologia SPIN Selling
- Recomendações de próximos passos

---

## Arquitetura

Fluxo da aplicação:

Transcrição (.txt)
↓

Interface desenvolvida no Lovable

↓

Webhook (n8n)

↓

OpenAI

↓

JSON estruturado

↓

Dashboard com os resultados da análise

---

## Tecnologias utilizadas

- Lovable
- n8n
- OpenAI API
- JSON
- Webhooks

---

## Como executar

1. Abrir a aplicação
2. Fazer upload de um arquivo `.txt`
3. Clicar em **Analyze Meeting**
4. Visualizar os insights gerados automaticamente

---

## Screenshots

### Página inicial

(Imagem aqui)

### Resultado da análise

(Imagem aqui)

---

## Link da aplicação

https://SEU-LINK.lovable.app

---

## Observações

Durante o desenvolvimento foram necessários ajustes na integração entre Lovable e n8n para garantir que os dados retornados pela IA fossem corretamente interpretados e exibidos na interface.

O projeto foi desenvolvido utilizando ferramentas no-code/low-code, com foco em integração, automação e experiência do usuário.
