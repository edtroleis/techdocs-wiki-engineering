# Padrões de código

## Geral

- Nomes descritivos; evite abreviações.
- Funções pequenas, com uma responsabilidade.
- Sem código comentado no `main`; o histórico está no Git.

## Por linguagem

| Linguagem | Formatter | Linter | Testes |
|-----------|-----------|--------|--------|
| Python | ruff format | ruff | pytest |
| TypeScript | prettier | eslint | jest / vitest |
| Shell | shfmt | shellcheck | bats |

## Testes

- Todo bug corrigido ganha um teste que o reproduz.
- Testes determinísticos: sem dependência de horário, rede ou ordem.

```python
def test_create_item_returns_id():
    item = create_item(ItemIn(name="caneta"))
    assert item.id == 1
```
