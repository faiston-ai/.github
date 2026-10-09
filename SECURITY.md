# Política de segurança

## Encontrou um problema de segurança?

**Não abra issue pública.** Avise diretamente o time de Engenharia de IA (Rafa, Adilson ou Luis) por mensagem privada.

Exemplos do que reportar:

- Senha, token ou chave de API commitada em algum repositório
- Sistema expondo dados de cliente ou dados pessoais
- Acesso indevido a sistemas internos, banco de dados ou serviços em nuvem

## Vazou um segredo? Faça nesta ordem

1. **Revogue/troque a credencial imediatamente** no serviço de origem (isso é o que importa — apagar do Git não desfaz o vazamento, o histórico guarda tudo).
2. Avise o time.
3. Remova do código e mova para `.env` / cofre de segredos.
4. Registre o que aconteceu num pós-incidente curto (template no handbook).

## Prevenção

Todos os repositórios criados a partir do `template-projeto` rodam **varredura automática de segredos** (gitleaks) a cada push e Pull Request.
