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