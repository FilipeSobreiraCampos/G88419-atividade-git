# 📌 Passo a Passo: Hospedando Código no GitLab

Este guia explica como criar um repositório no GitLab e enviar seu código utilizando Git.

---

## 🛠️ **Pré-requisitos**
Antes de iniciar, certifique-se de ter:
- Uma conta no [GitLab](https://gitlab.com/)
- O Git instalado no seu computador ([Baixar Git](https://git-scm.com/))
- Um projeto criado localmente

---

## 📌 **1. Criar um Repositório no GitLab**
1. Acesse [GitLab](https://gitlab.com/)
2. Clique em **"New project"**
3. Escolha a opção **"Create blank project"**
4. Defina um nome para o repositório
5. Escolha a visibilidade: **público**, **privado** ou **interno**
6. Clique em **"Create project"**

---

## 📌 **2. Configurar o Git Localmente**
### **2.1. Inicializar o Git no Projeto**
Abra o terminal (cmd, PowerShell ou Git Bash) e navegue até a pasta do projeto:

```sh
cd /caminho/do/seu/projeto
```

Inicie o Git no diretório do projeto:

```sh
git init
```

### **2.2. Vincular ao Repositório no GitLab**
Copie a URL do repositório criado e rode o comando:

```sh
git remote add origin https://gitlab.com/usuario/nome-do-repositorio.git
```

Verifique se a conexão foi estabelecida:

```sh
git remote -v
```

Caso seu repositório seja privado, autentique-se com um **Personal Access Token (PAT)** ao usar `git push` ou `git clone`.

---

## 📌 **3. Adicionar e Enviar Arquivos ao GitLab**
### **3.1. Adicionar Arquivos ao Controle do Git**
Para adicionar todos os arquivos do projeto:

```sh
git add .
```

### **3.2. Criar um Commit**
Confirme as alterações com uma mensagem descritiva:

```sh
git commit -m "Primeiro commit - adicionando arquivos iniciais"
```

### **3.3. Enviar Código para o GitLab**
Agora, envie os arquivos para o repositório remoto:

```sh
git push -u origin main
```

Se o branch principal for `master`, use:

```sh
git push -u origin master
```

Caso seu repositório seja privado, o Git pode solicitar autenticação.

---

## 📌 **4. Atualizando o Repositório**
Para atualizar o código no GitLab:

```sh
git add .
git commit -m "Atualizando arquivos"
git push origin main
```

Se houver alterações remotas, baixe-as antes de enviar novas mudanças:

```sh
git pull origin main
```

---

## 📌 **5. Clonar um Repositório Existente**
Se desejar baixar um repositório para sua máquina:

```sh
git clone https://gitlab.com/usuario/nome-do-repositorio.git
```

Se o repositório for privado, forneça um **Personal Access Token** quando solicitado.

---

## 🎉 **Conclusão**
Agora você sabe como hospedar e gerenciar seu código no GitLab! 🚀

