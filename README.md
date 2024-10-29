# HTML-CSS
 Repositorio


Como fazer um git, romulo:
Lista de Comandos Git
Git
git init - Inicia um repositório git criando uma subpasta oculta chamada .git.

Visualização do Histórico e Estado
git log --oneline --graph --all --decorate

Mostra todos os commits em um formato compacto, exibindo o grafo de branches e referências.
git rev-list --all

Lista todos os commits no repositório, incluindo aqueles não referenciados por branches.
git reflog

Mostra um histórico de todos os movimentos do HEAD, permitindo ver referências anteriores a commits.
git status

Exibe o estado atual do repositório, incluindo arquivos em stage, não rastreados e alterações não comitadas.
git diff

Mostra as diferenças entre o estado atual dos arquivos e o último commit, permitindo visualizar as alterações não comitadas.
Gerenciamento de Commits
git add <file>

Adiciona alterações de um arquivo específico à área de stage, preparando-o para o próximo commit.
git add -i

Inicia uma interface interativa para adicionar alterações, permitindo escolher quais mudanças incluir na área de stage.
git commit -m "<mensagem>"

Cria um novo commit com as alterações que estão na área de stage e inclui uma mensagem descritiva.
Manipulação de Branches
git checkout -b <branch-name> <commit-hash>

Cria uma nova branch a partir de um commit específico, permitindo acessar commits não referenciados.
git branch -d <branch-name>

Exclui uma branch, mas impede a exclusão se a branch não estiver completamente mesclada.
git branch -D <branch-name>

Exclui uma branch de forma forçada, independentemente de seu estado de mesclagem.
Integridade do Repositório
git fsck --lost-found

Verifica a integridade do repositório e lista objetos perdidos (dangling), incluindo commits que não têm referência.
git show <commit-hash>

Exibe as alterações feitas em um commit específico, mostrando detalhes sobre o conteúdo do commit.



no terminal do vscode use git init, depois ls -Force, git log, git add ., git commit -m “inicio repositorio ((nome do arquivo)) estrutura basica html”, git config –local user.email “gabriel123leonel@gmail.com”, git config –local user.name “Leonel”, git config –list


Para colocar cada versão mudada faça isso: git status 
git add .
git commit -m “(nome do arquivo)”
git log
