# GIT E GITHUB

Guia prático para iniciante

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projeto

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto

- `git add server.js` // para adicionar algo no histórico

- `git commit -m "mensagem"` // envia os arquivos adicionados ao repositórios
git status
git log -> histórico de mudanças
git show 0456dbd69aa8ad8c7c29bc8838832a0a9c9b834b -> mostra mudança específica

git branch -> mostra as linhas do tempo
git branch nome/branch -> cria uma branch
git checkout nome/branch -> muda a sua branch
git marge nome/branch -> junta as branch na master
git branch -d nome/branch -> deleta a branch

git remote add origin https://github.com/Gustavoph/BasicGIT.git
git push -u origin master
git push

- `git init` //para iniciar um repositório
- `git config --global user.email email@exemplo`
- `git config --global user.name nomeExemplo`
- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
- `git add.` // Adiciona todas as mudanças ao mesmo tempo
- `git commit` // adiciona um ponto na linha do tempo
- `git log` // visualiza os pontos na linha do tempo / commit
- `git status` // informa o estado das alterações do nosso projeto
- `git show` // apresenta determinado ponto na história
- `git branch` // gerenciar novas linhas do tempo
- `git checkout` // manipula as linhas do tempo
- `git merge` // unir linhas do tempo
- `git push` // envia alterações locais para o repositório remoto
- `git clone` // clonar um projeto / repositório
- `git pull` // puxa do repositório remoto
