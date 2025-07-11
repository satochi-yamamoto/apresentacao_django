# Instruções para agentes

Estas diretrizes orientam contribuições neste repositório.

## Mensagens de commit
- Escreva as mensagens de commit em **inglês**.
- A primeira linha deve resumir a alteração e ter no máximo 72 caracteres.

## Testes obrigatórios
Antes de criar um commit, execute os comandos abaixo e garanta que não há erros:

```
python manage.py check
python -m compileall -q .
black --check .
```

Se algum comando falhar, corrija os problemas antes de continuar.

## Estilo de código
- Formate o código usando `black .`.

