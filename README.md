# Faiston · Engenharia de IA

Área interna da Faiston responsável por **automatizar processos da empresa** com sistemas, integrações e IA.
Tudo aqui é construído pelo time, com o Claude como ferramenta principal de desenvolvimento.

## 🧭 Comece por aqui

| Se você quer... | Vá para |
|---|---|
| Entender como a área funciona | [`handbook`](https://github.com/faiston-ai/handbook) |
| Criar um projeto novo | Use o repo [`template-projeto`](https://github.com/faiston-ai/template-projeto) → **Use this template** |
| Entender como escolhemos o que automatizar | [Mapeamento de áreas](https://github.com/faiston-ai/handbook/blob/main/docs/06-mapeamento-de-areas.md) — vamos até cada área, levantamos as tarefas e priorizamos com a área e a liderança |
| Ver inventário, prioridades e andamento | **hubfaiston** |
| Sugerir uma automação avulsa | Registre um **Pedido de automação no hubfaiston** |
| Reportar problema de segurança | Leia o [`SECURITY.md`](https://github.com/faiston-ai/.github/blob/main/SECURITY.md) — **não abra issue pública** |

## 👥 Time

| Pessoa | Papel |
|---|---|
| Rafael (Rafa) | Engenharia de IA |
| Adilson | Engenharia de IA |
| Luis | Engenharia de IA |

## 📐 Regras de ouro

1. **Nada vai direto pra `main`** — todo código entra por Pull Request revisado por outra pessoa.
2. **Segredo não vai pro Git.** Senha, token, chave de API → `.env` (ignorado) ou cofre de segredos.
3. **Todo repo tem `README.md` e `CLAUDE.md`.** Um explica pro humano, o outro explica pro Claude.
4. **Teste nunca roda em produção.** Desenvolvimento e testes usam ambientes e dados de teste.
5. **Decisão importante vira ADR.** Se alguém vai perguntar "por que fizemos assim?", escreva.
