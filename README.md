# GuardIA Prompts

**Autores:** Davi Eugenio Suedt Monteiro (RM 566887) e Pedro Henrique de Oliveira Souza (RM 567422)

Acervo versionado de prompts para a aplicação GuardIA, um assistente corporativo com RAG.

## Arquivos

- `prompt-sistema-base.md`: regras gerais do assistente.
- `prompt-resumo-v1.md`: prompt de resumo.
- `prompt-perguntas-v2.md`: prompt de perguntas.
- `evals.jsonl`: casos de avaliação.
- `prompt.schema.json`: esquema de metadados.
- `prompt-check.yml`: exemplo de workflow de validação.
- `SECURITY.md` e `CHANGELOG.md`: segurança e histórico.

## Fluxo de alteração

1. Criar uma branch.
2. Alterar ou adicionar um prompt.
3. Atualizar os testes em `evals.jsonl`.
4. Abrir um pull request com revisão técnica e de segurança.
5. Executar as avaliações antes de criar uma tag de versão.

O repositório oficial do projeto é `https://github.com/DaviSuedt/guardia-prompts`.
