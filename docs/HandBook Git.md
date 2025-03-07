# 📘 Handbook do Git - Principais Comandos

Este guia apresenta os comandos essenciais do Git para versionamento de código e colaboração em projetos.

---

## 📌 **1. Configuração Inicial**
Antes de usar o Git, configure seu nome e e-mail:

```sh
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

Verifique as configurações:

```sh
git config --list
```

---

## 📌 **2. Criando e Inicializando um Repositório**
Criar um novo repositório local:

```sh
git init
```

Clonar um repositório existente:

```sh
git clone URL_DO_REPOSITORIO
```

---

## 📌 **3. Controle de Versão (Adicionar, Confirmar e Enviar)**
Adicionar arquivos ao rastreamento do Git:

```sh
git add nome_do_arquivo  # Adiciona um arquivo específico
git add .                 # Adiciona todos os arquivos
```

Criar um commit com uma mensagem descritiva:

```sh
git commit -m "Mensagem do commit"
```

Enviar alterações para o repositório remoto:

```sh
git push origin main  # Se estiver no branch main
```

Baixar atualizações do repositório remoto:

```sh
git pull origin main  # Atualiza o branch local com as mudanças do remoto
```

---

## 📌 **4. Trabalhando com Branches**
Criar um novo branch:

```sh
git branch nome_do_branch
```

Mudar para um branch existente:

```sh
git checkout nome_do_branch
```

Criar e mudar para um novo branch ao mesmo tempo:

```sh
git checkout -b nome_do_branch
```

Listar todos os branches:

```sh
git branch
```

Mesclar um branch ao branch atual:

```sh
git merge nome_do_branch
```

Excluir um branch:

```sh
git branch -d nome_do_branch
```

---

## 📌 **5. Histórico e Status**
Verificar o status do repositório:

```sh
git status
```

Verificar o histórico de commits:

```sh
git log
```

Exibir histórico resumido:

```sh
git log --oneline --graph --all
```

---

## 📌 **6. Desfazendo Alterações**
Desfazer mudanças em um arquivo antes de um commit:

```sh
git checkout -- nome_do_arquivo
```

Remover arquivos do staging area:

```sh
git reset nome_do_arquivo
```

Desfazer o último commit (mantendo as alterações no diretório de trabalho):

```sh
git reset --soft HEAD~1
```

Desfazer o último commit e descartar as alterações:

```sh
git reset --hard HEAD~1
```

---

## 📌 **7. Trabalhando com Repositórios Remotos**
Adicionar um repositório remoto:

```sh
git remote add origin URL_DO_REPOSITORIO
```

Listar repositórios remotos:

```sh
git remote -v
```

Alterar a URL do repositório remoto:

```sh
git remote set-url origin NOVA_URL
```

Remover um repositório remoto:

```sh
git remote remove origin
```

---

## 📌 **8. Stash - Salvando Mudanças Temporárias**
Salvar alterações sem commit:

```sh
git stash
```

Listar stashes salvos:

```sh
git stash list
```

Restaurar o stash mais recente:

```sh
git stash pop
```

Remover um stash específico:

```sh
git stash drop stash@{número}
```

---

## 🎯 **Conclusão**
Com esse handbook, você tem um guia rápido para os principais comandos do Git. Pratique esses comandos para melhorar sua fluidez com o versionamento de código! 🚀

