**Configurando o Git:**
- `$ git config --list`
- `$ git config --global user.name "Nome Sobrenome"`
- `$ git config --global user.email seuemail@email.com`
- `$ git config --global init.defaultBranch main`
- `$ git config --global credential.helper store`
- `$ git config --global --show --origin credential.helper`

**Criando um Repositório Local:**
- `$ mkdir repo-name` (criar um repositório local)
- `$ cd repo-name` (navegar para um repositório)
- `$ cd ..` (retornar a um diretório anterior)
- `$ git clone URL` (clonar um repositório remoto)
- `$ git init` (inicializar um repositório Git)
- `$ git remote add origin https://github.com/username/nome-do-repositorio.git` (conectar um repositório local a um repositório remoto)

**Clonando uma Branch Específica:**
- `$ git clone URL --branch branchName --single-branch`

**Desfazendo Alterações no Repositório Local:**
- `$ rm -rf .git` (desfazer git init)
- `$ git restore fileName` (restaurar alterações antes do git add)

**Alterando Mensagem do Último Commit:**
- `$ git commit --amend`
- `$ git commit --amend -m "nova mensagem"`

**Desfazendo um Commit:**
- `$ git reset`
- `$ git reset --soft`
- `$ git reset --mixed`
- `$ git reset --hard`

**Enviando Alterações:**
- `$ git remote add origin URL`
- `$ git push -u origin URL`

**Atualizando o Repositório Local:**
- `$ git pull`

**Criando uma Nova Branch:**
- `$ git checkout -b branchName`
- `$ git checkout main` (retornar para a branch main)
- `$ git branch -v` (listar o último commit de cada branch)
- `$ git merge branchName` (mesclar alterações da branch com a main)
- `$ git branch` (listar branches)
- `$ git branch -d branchName` (excluir branch)

**Outros Comandos:**
- `$ git fetch origin main` (baixar alterações do remoto para o local sem mesclar)
- `$ git merge origin/main` (baixar alterações mesclando)
- `$ git diff main origin/main` (ver diferenças entre as branches)
- `$ git add .` (enviar todos os arquivos para commit)
- `$ git add fileName` (enviar um arquivo específico para commit)
- `$ git status` (verificar o status da área de preparação)
- `$ touch README.MD` (criar um arquivo README.md)
- `$ cat repo-name` (ver os arquivos do repositório)
- `$ git commit -m "mensagem do commit"` (gravar alterações no repositório)
- `$ git log` (ver a lista de commits)
- `$ echo file/repoName/ > .gitignore` (enviar para a pasta .gitignore)
