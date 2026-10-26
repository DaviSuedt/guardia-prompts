# GuardIA Prompts

Acervo versionado de prompts para a aplicação GuardIA, um assistente corporativo com RAG.

## Estrutura

- `prompts/system/`: regras gerais do assistente.
- `prompts/tasks/`: prompts específicos por tarefa.
- `tests/evals.jsonl`: casos de avaliação.
- `schemas/prompt.schema.json`: formato mínimo dos prompts.
- `.github/workflows/prompt-check.yml`: validação automática em cada pull request.

## Fluxo de alteração

1. Criar uma branch.
2. Alterar ou adicionar um prompt.
3. Atualizar os testes em `tests/evals.jsonl`.
4. Abrir um pull request com revisão técnica e de segurança.
5. Executar as avaliações antes de criar uma tag de versão.

A URL proposta no trabalho é `https://github.com/empresa/guardia-prompts`.
