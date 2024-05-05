# Guia de Comandos Git

## Configurações Iniciais

Configurar seu nome de usuário e email:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

## Operações Básicas

### Criar um Repositório Local

```bash
git init
```

### Verificar o Status do Repositório

```bash
git status
```

### Adicionar Todos os Arquivos para um Novo Commit

```bash
git add .
```

### Realizar um Novo Commit

```bash
git commit -m "Descrição do commit"
```

## Trabalhando com Repositórios Remotos

### Configurar um Repositório Remoto

```bash
git remote add origin https://github.com/seunome/seurepositorio.git
```

### Enviar Commits para o Repositório Remoto

```bash
git push
git push -u origin <NomeBranch>
git push -u origin main
git push -u origin main --force
```

### Clonar um Repositório Remoto

```bash
git clone https://github.com/seunome/seurepositorio.git
```

### Requisitar Novas Atualizações do Repositório

```bash
git pull
```

## Gerenciando Branches

### Criar e Mudar de Branches

```bash
git checkout -b <NomeBranch> # Criar nova branch
git checkout <NomeSuaBranch> # Mudar de branch
git push origin <NomeSuaBranch> # Dar um push na branch específica
git push -u origin <NomeSuaBranch> # Primeiro push com (-u)
```

## Atalhos e Configurações

### Configurar Atalhos e Editor

```bash
git config --global core.editor code --wait
git config --global --edit
```

### Configurar Atalhos no CLI do Git

```bash
[core]
    editor = code --wait
[user]
    email = seuemail@gmail.com
    name = Seu Nome 
[alias]
    s = !clear & git status -s
    c = !clear & git add . & git commit -m
    l = !clear & git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(yellow)%cr'
    amend = !clear & git add . && git commit --amend --no-edit
```
