# Guia de Contribuicao

## Como Contribuir

### 1. Crie uma Branch

Sempre crie uma branch a partir da `main` para trabalhar em uma tarefa:

```bash
git checkout -b feat/nome-da-tarefa
```

### 2. Padrao de Branches

| Prefixo   | Uso                        |
|-----------|----------------------------|
| `feat/`   | Nova funcionalidade         |
| `fix/`    | Correcao de bug             |
| `docs/`   | Alteracoes na documentacao  |
| `refactor/` | Refatoracao de codigo     |

### 3. Faca Commits Claros

Siga o padrao de commits convencionais:

```
tipo: descricao curta do que foi feito
```

Exemplos:
- `feat: adiciona pagina de login`
- `docs: atualiza ata da reuniao 3`
- `fix: corrige link quebrado na sidebar`

### 4. Abra um Pull Request

- Abra um PR da sua branch para a `main`
- Descreva brevemente o que foi feito
- Solicite revisao de pelo menos um membro do grupo

### 5. Revisao

- Revise os PRs dos colegas com atencao
- Deixe comentarios construtivos
- Aprove somente quando estiver de acordo com as alteracoes

## Regras Gerais

- Nao faca push direto na `main`
- Mantenha sua branch atualizada com a `main` antes de abrir o PR
- Resolva conflitos localmente antes de solicitar merge
- Documente o que for necessario no GitPages
