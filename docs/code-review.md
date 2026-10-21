# Code review

## Prazos

| Tamanho do PR | Primeira revisão em |
|---------------|---------------------|
| Pequeno (< 200 linhas) | 4 horas úteis |
| Médio | 1 dia útil |
| Grande (> 800 linhas) | Prefira quebrar em PRs menores |

## O que revisar

1. **Correção**: faz o que promete? Casos de borda?
2. **Segurança**: entrada validada? Segredos expostos?
3. **Legibilidade**: outra pessoa entende sem ajuda?
4. **Testes**: cobrem o comportamento novo?
5. **Docs**: `docs/` e runbook atualizados?

## Tom

- Comente o código, não a pessoa.
- Use prefixos: `nit:` (opcional), `sugestão:`, `bloqueante:`.
