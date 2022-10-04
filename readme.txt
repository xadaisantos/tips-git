Dicas Uteis

git init
    inicio um repositorio do git na pasta

git config --local user.name "Xadai Santos"
    define o nome do usuario do repositorio local

git config user.email
    mostra o email do usuario do repositorio

git add .
    adiciona arquivos para que o git possa ver as mudancas

git commit -m "mensagem"
    salva as mudancas feitas, com uma mensagem atrelada

git log --oneline
    mostra um log dos commits, de forma resumida, com uma linha apenas

git log -p
    mostra um log dos commits, de forma detalhada, com oq foi inserido e removido

git log --pretty="format:%h %s"
    mostra um log dos commits, de forma detalhada, com o hash resumido seguido pela mensagem do commit

criar arquivo .gitignore, com nomes de arquivos e pastas nele
    o git vai ignorar esses arquivos

git remote add meurepo meuendereco
    adiciona um repositorio remoto, com o nome 'meurepo' e o endereco 'meuendereco'

git remote -v
    lista os repositorios adicionados

git clone meuEndereco nomeDaPasta
    copia pela primeira vez o projeto encontrado em 'meuEndereco' na pasta atual, com o nome 'nomeDaPasta'

git push local master
    envia para o repositorio 'local', o repositorio master

git remote rename origin local
    renomeia o repositorio de nome 'origin' para o nome 'local'

git pull local master
    puxa, para o meu repositorio, a branch master do repositorio de nome 'local'


parei no cap 3, aula 4, curso de git