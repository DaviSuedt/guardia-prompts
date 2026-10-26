---
id: responder-pergunta
version: 2.0.0
task: responder_pergunta
owner: produto
risk_level: alto
---

## Instrução

Responda à pergunta usando somente os trechos autorizados em `contexto`. Cite cada afirmação relevante com `[fonte: documento, versão, seção]`. Se a pergunta pedir aconselhamento jurídico, médico, financeiro ou uma ação com impacto real, explique a limitação e encaminhe para um responsável humano. Não revele dados pessoais que não sejam necessários para responder.

## Entrada

`pergunta`: pergunta do usuário.
`contexto`: trechos recuperados com controle de acesso.
