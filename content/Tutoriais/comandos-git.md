---
title: "Manual de Comandos de Git"
---

# Comandos

# 01

**git init** → Utilizado parainicializar um repositório git (só deve ser feito para criar um novo repositório local)

Sintaxe: `git init`

# 02

**git clone** → Clona um repositório já existente no github.

Sintaxe: `git clone <<url-do-repo.git>>`

# 03

**git config** → Necessário para configurar o git para uso pela primeira vez.

Sintaxe:

`git config --list`→ lista as configurações do git

`git config --global user.email fulanodetal@exemplo.br` → configura o email do usuário. Deve ser o mesmo da conta do GitHub

`git config --global user.name "Fulano de Tal"` → configura o nome do usuário.

# 04

**git branch** → Lista todas as branches presentes naquelerepositório

Sintaxe: `git branch`

<aside> 💡 Digite :WQ para sair da lista que foi aberta

</aside>

# 05

**git branch <<nome da branch>>** → Cria uma nova branch com o nome escolhido

Sintaxe: `git branch exemplo-de-nome`

# 06

**git checkout <<nome da branch>>** → entra na branch com o nome selecionado

Sintaxe: `git checkout exemplo-de-nome`

<aside> 💡 Bônus: podemos combinar os dois comandos acima usando `git checkout -b exemplo-de-nome`. Dessa forma criamos a branch e a acessamos.

</aside>

# 07

**git status** → lista as mudanças realizadas na branch desde o último commit

Sintaxe: `git status`

<aside> 💡 Digite :WQ para sair da lista que foi aberta

</aside>

# 08

**git add** → Adiciona arquivos para o commit. Pode ser feito arquivo por arquivo ou adicionar a pasta inteira do projeto.

Sintaxe:

`git add -- all` → Adiciona todos os arquivos que ainda não foram adicionados

`git add .` → Adiciona todos arquivos da pasta atual

`git add nome-do-arquivo` → Adiciona o arquivo

# 09

**git commit** → Permite a criação de um novo **commit**, isto é uma nova **fotografia/snapshot** do código em um determinado momento do tempo.

Sintaxe: `git commit -m "Descrição da alteração"`

<aside> 💡 Não se esqueça das aspas aqui

</aside>

# 10

**git push** → Sobe os commits realizados para o github (ou outra plataforma de nuvem)

Sintaxe: `git push origin nome-da-branch`