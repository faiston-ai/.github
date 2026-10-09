# Como contribuir

Este arquivo vale para **todos os repositórios da organização** (o GitHub herda os arquivos do repo `.github` quando o projeto não tem o seu próprio).

O detalhe de cada regra está no [handbook](https://github.com/faiston-ai/handbook). Aqui vai o resumo do dia a dia:

## Fluxo em 6 passos

```bash
# 1. Atualize a main
git switch main && git pull

# 2. Crie uma branch com nome padrão
git switch -c feat/123-emissao-nf-automatica

# 3. Trabalhe e faça commits pequenos
git commit -m "feat(nf): gera XML de remessa a partir do pedido"

# 4. Suba a branch
git push -u origin feat/123-emissao-nf-automatica

# 5. Abra o Pull Request (o template aparece sozinho)
gh pr create

# 6. Depois da aprovação: Squash and merge → apague a branch
```

## Padrões rápidos

| Item | Padrão | Exemplo |
|---|---|---|
| Branch | `tipo/issue-descricao` | `fix/87-encoding-rejeicao-225` |
| Commit | `tipo(escopo): descrição` | `docs(readme): adiciona passo de setup` |
| Tipos | `feat` `fix` `docs` `refactor` `test` `chore` `ci` | |
| Merge | Squash and merge | |
| Review | Mínimo 1 aprovação de outra pessoa | |

Detalhes: [Fluxo Git](https://github.com/faiston-ai/handbook/blob/main/docs/02-fluxo-git.md).
