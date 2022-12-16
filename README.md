# git-comandos-uteis

## Entrar na pasta por linha de comando e depois
git init

## Configure seus dados no git
git config --global user.name "Carlos Eduardo Lucas"
git config --global user.email "carlosedlucas@gmail.com"

## Faça o commit inicial
git commit -am 'Initial'

## Adicionar os arquivos
git add arquivo.ext

## Veja o status
git status

## Salvar alterações (commit das alterações)
git commit -am 'Mensagem do que foi adicionado'

## Ver alterações
git log --all --decorate --oneline --graph

## Acessar algum commit específico
git checkout <identificador>

## Criar um novo branch daquele commit
git checkout -b <nome>

## Ver branchs
git branch

## Renomear branchs locais
git branch -m <nome> <novo_nome>

## Voltar ao master
git checkout master

## Merge (juntar o master ao seu novo branch)
git merge <nome>

## Tags
git tag v0.1.1
## apagar
git tag -d <nome>

## Clone
git clone url_do_repo

## Adicionando repositório remoto
git remote add <nome> usuario@url_do_repo

## Baixar alterações do repo remoto
git pull <nome_do_repo> <branch>

## Enviar commits para o repo remoto
git push <nome_do_repo> <branch>

## Criando seu próprio repo
git init --bare

## Git ignore (ignore alguns arquivos) com o .gitignore
https://www.gitignore.io/

## Revertendo alterações antes de commitar (arquivos precisar estar staged)
git reset --hard

## Removendo arquivos não adicionados
git clean -f

## Ver branchs remotos
git remote show <nome_do_repo>

## Apagar branchs remotos
git push --delete <nome_do_repo> <nome_branch>

## Apagar remoto
git remote -rm <nome_do_repo>
