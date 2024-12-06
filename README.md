# GIT

COMANDOS:

* git add arquivo: Este comando adiciona o arquivo especificado à área de stage (preparação) do Git. Isso significa que o arquivo está pronto para ser incluído no próximo commit.
* git commit -m 'mensagem': cria um novo commit com as mudanças que foram adicionadas à área de stage. A opção -m permite que você adicione uma mensagem de commit diretamente na linha de comando.
* git commit -a -m 'mensagem': uma combinação de git add e git commit. Ele adiciona automaticamente todas as mudanças nos arquivos rastreados (tracked files) à área de stage e cria um commit com a mensagem especificada.
* git push: copia as informações do repositório local para o remoto.
* git pull: copia as informações do repositório remoto para o local com o commit
* git fetch: copia as informações modificadas para o repositório local sem o commit.
* git diff origin/master: mostra as modificações realizadas no repositório.
* git branch teste: cria uma branch com o nome teste.
* git checkout teste: troca para a branch teste.
* git merge teste: copia as modificações da branch teste para a branch atual (master). 
* git blame README.md: indica o responsável pelas alterações relacionadas a um commit específico.
* git checkout -b feature-login: cria a nova branch e automaticamente muda para ela.
* git stash: salva todas as mudanças não commitadas e retorna o diretório de trabalho ao estado limpo da última atualização HEAD.
* git rebase main: pega todos os commits da branch feature-login e reaplicá-los no topo da branch main. Isso cria um histórico linear, como se todos os commits da branch feature-login tivessem sido feitos após os commits da branch main.