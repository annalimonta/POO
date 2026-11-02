# Comandos Git básicos

Resumo dos comandos usados para versionar arquivos nesta atividade.

| Comando                     | Para que serve                                                     |
|-----------------------------|--------------------------------------------------------------------|
| `git clone <url>`           | Cria uma cópia local de um repositório remoto.                     |
| `git status`                | Mostra os arquivos novos, modificados e preparados para commit.    |
| `git add <arquivo>`         | Prepara (*stage*) as alterações para o próximo commit.             |
| `git commit -m "mensagem"`  | Registra as alterações preparadas no histórico local.              |
| `git push`                  | Envia os commits locais para o repositório remoto (GitHub).        |
| `git log --oneline`         | Mostra o histórico de commits, um por linha.                       |

## Ramos (branches)

Um ramo é uma linha de desenvolvimento independente: as alterações feitas nele
não afetam o ramo `main` até que sejam mescladas.

| Comando                              | Para que serve                                          |
|--------------------------------------|---------------------------------------------------------|
| `git branch`                         | Lista os ramos locais (o atual aparece com `*`).        |
| `git switch -c <ramo>`               | Cria um ramo novo e já alterna para ele.                |
| `git switch <ramo>`                  | Alterna para um ramo que já existe.                     |
| `git push -u origin <ramo>`          | Envia o ramo ao GitHub e liga o ramo local ao remoto.   |
| `git branch -a`                      | Lista os ramos locais e os remotos (`remotes/origin/`). |
| `git log --oneline --graph --all`    | Mostra o histórico de todos os ramos em forma de grafo. |
