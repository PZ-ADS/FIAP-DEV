# Guia rápido de Git

## Fluxo básico

1. Edite ou crie arquivos no seu projeto.
2. Verifique o status:
   ```bash
   git status
   ```
3. Adicione alterações:
   ```bash
   git add nome-do-arquivo
   # ou para tudo:
   git add .
   ```
4. Salve no histórico (commit):
   ```bash
   git commit -m "Mensagem explicando a mudança"
   ```
5. Envie para o GitHub:
   ```bash
   git push
   ```

> Antes de começar em outro computador ou depois que alguém mexer, traga as mudanças:
```bash
git pull
```

---

## Dicas rápidas

- Mensagens de commit devem ser curtas e claras, por exemplo: `Implementa função de login`.
- Use `git log` para ver o histórico.
- Se algo der errado, o Git quase sempre permite recuperar.

---

## Próximos passos

- Branches: `git branch` e `git checkout -b nome-da-branch`.
- Desfazer mudanças: `git revert` (um commit) e `git reset` (voltar ao estado anterior).
- Explore a aba **Source Control** no VSCode.
