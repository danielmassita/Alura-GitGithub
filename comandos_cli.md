### Básico pra inicializar o GIT BASH...
Abrir o link do GIT - Ctrl+C
Abrir o Git CMD (ou clicar com o mouse e usar "Git Here")

### Comandos básicos de CLI pra navegar nas pastas...
ls (lista as pastas no diretório atual)
cd (change directory)
cd Documents (entra na pasta Documents)
cd (sai da pasta pro arquivo superior)

### Comandos básicos pra começar a trabalhar com o repositório do GitHub...
git clone URL (paste)
cd Git
cd AluraGitGithub

ls (listará os arquivos dentro da pasta que criamos uma cópia, no caso index.html, app.js e README.md)
git log (apresentará o histórico de alterações "commits")
:q (pra sair do log)
Ctrl+L (limpar linhas)
git log --oneline (apresentará o resumo do histórico de alterações "commits")

### Atualizando um repositório acaso tenham tido alterações na origem...
git pull URL
git status (dentro do CLI do VS Code pra ver os "modified")
git commit index.html -m "mensagem do commit"
git commit app.js -m "mensagem do commit"
git commit . (pra atualizar todas as alterações)
git push origin main (devolve para o repositório origem)

