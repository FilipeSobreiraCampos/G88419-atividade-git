# Instalação do Git no Linux

## Introdução
O Git é um sistema de controle de versão distribuído amplamente utilizado por desenvolvedores para gerenciar código-fonte. Este guia cobre a instalação do Git em distribuições baseadas em Debian (como Ubuntu) e Red Hat (como Fedora e CentOS).

---

## Instalando o Git no Ubuntu/Debian

Para instalar o Git em distribuições baseadas em Debian, execute os seguintes comandos:

```sh
sudo apt update
sudo apt install git -y
```

Verifique se a instalação foi concluída com sucesso:

```sh
git --version
```

---

## Instalando o Git no Fedora/CentOS

Para distribuições baseadas em Red Hat, use os seguintes comandos:

```sh
sudo dnf install git -y  # Para Fedora
```

Ou para CentOS:

```sh
sudo yum install git -y
```

Confirme a instalação com:

```sh
git --version
```

---

## Configuração Inicial do Git

Após instalar o Git, configure seu nome de usuário e e-mail para garantir que seus commits sejam corretamente atribuídos:

```sh
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

Para verificar suas configurações:

```sh
git config --list
```

Agora o Git está instalado e configurado no seu sistema Linux! 🎉
