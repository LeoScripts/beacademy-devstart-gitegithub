# beacademy-devstart-gitgithub

## config
- `git config --global user.name "nome"` - configura o nome de usuario
- `git config --global user.email "email"` - configura email do usuario

## manipulando arquivos e commits
- `git init` - inicia um repositório git
- `git add "NomeDoArquivo.extensao"` - adiciona aos itens monitoraodos
- `git clone "url do repositorio"` - Clona repositorio
- `git status` - mostra o status dos arquivos
- `git commit -m "mensagem do commit"` - salva modificaçoes feitas
- `git log`- mostra o histórico de commits
- `git rm --cached "NomeDoArquivo.extensao"` - remove determindo arquivo do monitoramento
- `git push` - envia arquivos para o repositorio remoto
- `git remote` - mostra repositorio remoto
- `git remote -v` - mostra repositorio remoto a origem
- `git reset` - resta as mudanças
- `git revert "4 primeiros dígitos do hash do commit"` - reverte as mudanças pra um commit expecifico

## ramificações(branch)
- `git branch` - listas branches
- `git branch "nome da branch"` - cria branch
- `git checkout "nome da branch"` - acessa determinda branch
- `git checkout -b "nome da branch"` - cria e acessa branch
- `git merge "nome da branch"` - mescha duas branche, ==> selecione a branch pra onde quer enviar o merge antes
- `git branch -d "nome da branch"` - deleta determinda branch

## edções sem commit(stash)
- `git stash` - guarda as edições 
- `git stash list` - lista stashs
- `git stash pop` - vai remover o stash mais recente da pilha e aplicar as mudanças que ele contém
- `git stash --include-untracked` - salva alterações sem commit


[para mais comandos](https://comandosgit.github.io/)
