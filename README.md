# Curso Git & GitHub 2026

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos em Github.

Além disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

Confira tudo o que temos no Youtube -> Téo Me Why segue o link:

[curso git 2025] (https://youtube.com/@teomewhy)

Além do nosso youtube se ligue no nosso site e agenda para ficar por dentro de tudo que vai rolar em 2026.

[teomewhy.org](https://teomewhy.org/schedule)

## Fluxo de trabalho Git local

1. git checkout -b <nova-branch>
2. cria ou atualiza arquivos
3. git status
4. git add
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

1. git clone <endereço do projeto>
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add *arquivos*
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
9. abrir Pull Request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -d <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)

1. Fork do projeto para seu próprio github
2. git clone <endereço do projeto fork>
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add *arquivos*
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull Request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -d <nova_branch>

-----------

Pessoas participantes:

- João