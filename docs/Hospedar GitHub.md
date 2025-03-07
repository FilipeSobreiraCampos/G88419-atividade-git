# 📌 Passo a Passo: Hospedando Código no GitHub

Este guia descreve como criar um repositório no GitHub e enviar seu código usando o Git.

---

## 🛠️ **Pré-requisitos**
Antes de começar, certifique-se de ter:
- Uma conta no [GitHub](https://github.com/)
- O Git instalado no seu computador ([Baixar Git](https://git-scm.com/))
- Um projeto criado localmente

---

## 📌 **1. Criar um Repositório no GitHub**
1. Acesse [GitHub](https://github.com/)
2. Clique no botão `+` no canto superior direito e selecione **"New repository"**
3. Escolha um nome para o repositório
4. Defina como **público** ou **privado**
5. Marque a opção **"Add a README file"** (opcional)
6. Clique no botão **"Create repository"**

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

### **2.2. Vincular ao Repositório no GitHub**
Copie a URL do repositório criado e rode o comando:

```sh
git remote add origin https://github.com/usuario/nome-do-repositorio.git
```

Verifique se a conexão foi estabelecida:

```sh
git remote -v
```

---

## 📌 **3. Adicionar e Enviar Arquivos ao GitHub**
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

### **3.3. Enviar Código para o GitHub**
Agora, envie os arquivos para o repositório remoto:

```sh
git push -u origin main
```

Se o branch principal for `master`, use:

```sh
git push -u origin master
```

---

## 📌 **4. Atualizando o Repositório**
Para atualizar o código no GitHub:

```sh
git add .
git commit -m "Atualizando arquivos"
git push origin main
```

Caso já tenha alterado algo diretamente no GitHub, atualize seu repositório local antes de enviar novas mudanças:

```sh
git pull origin main
```

---

## 📌 **5. Clonar um Repositório Existente**
Se quiser baixar um repositório para sua máquina:

```sh
git clone https://github.com/usuario/nome-do-repositorio.git
```

---

## 🎉 **Conclusão**
Agora você sabe como hospedar e gerenciar seu código no GitHub! 🚀

