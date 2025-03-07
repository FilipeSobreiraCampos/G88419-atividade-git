# Instalação do Git no Windows

Para instalar o Git no Windows, siga os passos abaixo:

## Passo 1: Baixar o Git

1. Acesse o [site oficial do Git](https://git-scm.com/).
2. Clique no botão **Download** para Windows. O site detectará automaticamente seu sistema operacional.

## Passo 2: Iniciar a Instalação

1. Após o download ser concluído, execute o arquivo `.exe` que você baixou.
2. O assistente de instalação será aberto. Clique em **Next** para continuar.

## Passo 3: Escolher Opções de Instalação

Durante o processo de instalação, você terá várias opções. As opções padrão são adequadas para a maioria dos usuários, mas você pode ajustá-las conforme necessário.

- **Select Components**: Mantenha as opções padrão.
- **Choosing the default editor**: Escolha um editor de texto. O padrão é o **Vim**, mas você pode selecionar outro, como o **Notepad++** ou o **Visual Studio Code**.
- **Adjusting the name of the initial branch in your Git repository**: O padrão é "master", mas pode ser alterado se necessário.
- **Adjusting your PATH environment**: Selecione **Git from the command line and also from 3rd-party software** para adicionar o Git ao PATH.
- **Choosing HTTPS transport backend**: Selecione **Use the OpenSSL library**.
- **Configuring the line ending conversions**: A opção padrão **"Checkout Windows-style, commit Unix-style line endings"** é recomendada.

## Passo 4: Instalar

1. Após selecionar todas as opções, clique em **Next** e depois em **Install**.
2. Aguarde a instalação ser concluída.

## Passo 5: Finalizar a Instalação

1. Após a instalação ser concluída, clique em **Finish**.
2. Você pode optar por abrir o **Git Bash** ou o **Prompt de Comando** após a instalação.

## Passo 6: Verificar a Instalação

1. Abra o **Git Bash** ou o **Prompt de Comando**.
2. Digite o seguinte comando para verificar a instalação:
   ```bash
   git --version
O Git retornará a versão instalada. Exemplo:

git version 2.34.1.windows.1

Pronto! O Git foi instalado com sucesso no seu sistema Windows.
