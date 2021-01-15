# GIT E GITHUB

Guia prático para iniciante

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projeto

### Iniciando 

git init -> para iniciar um repositório

git config --global user.email email@exemplo
git config --global user.name nomeExemplo

git add <nome do arquivo> -> para adicionar algo no histórico
git commit -m "mensagem" -> envia os arquivos adicionados ao repositórios
git status

git log -> histórico de mudanças
git show 0456dbd69aa8ad8c7c29bc8838832a0a9c9b834b -> mostra mudança específica

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto

git branch <nome da branch>
git checkout <nome da branch>