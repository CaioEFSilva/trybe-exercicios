# Exercício - Criando um repositório

1. Acesse a branch main e crie uma branch nova chamada atualiza-readme.

2. Acesse a branch atualiza-readme e crie um arquivo chamado infos.txt.

3. Adicione as alterações em staging e realize um commit.

4. Adicione seu nome e sobrenome ao arquivo infos.txt.

5. Adicione novamente as alterações em staging e realize um commit.

6. Crie uma branch nova a partir da branch atualiza-readme. A nova branch deve se chamar adiciona-infos.

7. Acesse a branch adiciona-infos e utilize sua criatividade para escrever o passo a passo de como o versionamento funciona no README.md. Por exemplo: “O primeiro passo é ter uma pasta versionada e criar um estrutura inicial, e fazemos isso utilizando o comando git init. O segundo passo é criar uma branch nova com o comando git branch nome-da-branch ou git checkout -b nome-da-branch…” Você pode, também, utilizar esse momento para registrar, em forma de perguntas e respostas, as dúvidas que ainda tiver sobre versionamento.

8. Adicione as alterações em staging e realize o commit.

9. Volte para a branch atualiza-readme e realize o merge das alterações feitas na branch adiciona-infos.

10. Retorne para a branch main e realize o merge das alterações.

## Resolução

1. > git checkout main <br> git branch atualizacao-readme
2. > git switch atualizacao-readme <br> touch info.txt
3. > git add . <br> git commit -m "Criando arquivo info.txt"
4. > echo "Caio Eduardo" > info.txt
5. > git add . <br> git commit -m "adicionando nome e sobrenome ao info.txt"
6. > git branch adiciona-infos
7. > git checkout adiciona-infos <br> touch README.md
8. > git add . <br> git commit -m "adicionando README.md"
9. > git switch atualizacao-readme <br> git merge adiciona-info
10. > git switch main <br> git merge atualizacao-readme