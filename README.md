# Aulas de Git e GitHub - Pretalab Ciclo 14

Este repositório foi criado para entrega do Primeiro Projeto do Ciclo 14 - PretaLab

 Como commitar um arquivo 
- Primeiro: git restore --staged <nomedoarquivo>
- Altera algo no arquivo 
- Depois:
git add .
git commit -m "commitar"
git push -u origin main

Criação de Branches
git checkout -b <nomedabranche> - criar 
git checkout <nomedabranch> - mudar para a Branche
git branch 
git add .
git commit -m "adicionar commit"
git log - aperta o q para sair da tela 
git push origin -u <nomedabranche> - primeiro push na branch nova precisa ser desta maneira, para reconhecimento do Git
git merge <nomedabranche> - commit/junção das duas branches

## Comandos Práticados
git config --global user.name "Nome" >> Define o nome do autor dos commits
git config --global user.email "email"	>> Define o e-mail do autor dos commits
git status	>> Mostra alterações no repositório
git add <arquivo> >> Adiciona arquivo ao stage
git commit -m "mensagem" >> Registra alterações
git branch >> Lista branches
git checkout -b nome	 >> Cria e troca para nova branch
git checkout nome	>> Troca de branch
git clone <url>	>>Clona repositório
git fetch	>> Busca atualizações sem aplicar
git pull	>> Atualiza branch local
git push	>> Envia commits para o remoto
git merge >> nome	Faz merge de uma branch
git rebase main	>> Reaplica commits sobre outra branch.

# Atualizando
