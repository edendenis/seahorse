# Como configurar/instalar/usar o `seahorse` no `Linux Ubuntu`

## Resumo

Neste documento estão contidos os principais comandos e configurações para configurar/instalar/usar o `seahorse` no `Linux Ubuntu`.

## _Abstract_

_This document contains the main commands and settings for configuring/installing/using the `seahorse` on `Linux Ubuntu`._


O `seahorse` é uma ferramenta gráfica para gerenciar senhas e chaves de criptografia no ambiente `GNOME` do `Linux`. Ele permite criar, importar e organizar chaves GPG e SSH, facilitando o armazenamento seguro de senhas e certificados.


## 1. Como configurar/instalar/usar o `seahorse` no `Linux Ubuntu` [1][3]

Para configurar/instalar/usar o `seahorse` no `Linux Ubuntu`, você pode seguir estes passos:

1. Abra o `Terminal Emulator`. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Certifique-se de que seu sistema esteja limpo e atualizado.

    2.1 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.2 Remover pacotes `.deb` antigos ou duplicados do cache local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando: `sudo apt autoclean`

    2.3 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando: `sudo apt autoremove -y`

    2.4 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`: `sudo apt update -y`

    2.5 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:  `sudo apt list --upgradable`

    2.6 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update -y`. Digite o seguinte comando e pressione `Enter`: `sudo apt full-upgrade -y`

    2.7 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando: `sudo apt autoremove -y`

    2.8 Remover pacotes `.deb` antigos ou duplicados do cache local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando: `sudo apt autoclean`

Para instalar o programa seahorse, que é um gerenciador de senhas, no Linux Ubuntu utilizando o Terminal Emulator, você pode seguir os passos abaixo:

3. **Instale o Seahorse**: Após atualizar a lista de pacotes, você pode instalar o Seahorse utilizando o seguinte comando: `sudo apt install seahorse -y`

4. **Execute o Seahorse**: Após a instalação, você pode iniciar o Seahorse diretamente do Terminal digitando: `seahorse`

    Você também pode encontrá-lo no menu de aplicações e iniciá-lo por lá.

### 2. Código completo para configurar/instalar/usar

Para configurar/instalar/usar o `seahorse` no `Linux Ubuntu` sem precisar digitar linha por linha, você pode seguir estas etapas:

1. Abra o terminal. Você pode fazer isso pressionando: `Ctrl + Alt + T`

2. Digite o seguinte comando e pressione `Enter`:

    ```
    sudo apt clean
    sudo apt autoclean -y
    sudo apt autoremove -y
    sudo apt update -y
    sudo apt uptoremove -y
    sudo apt autoclean -y
    sudo apt install seahorse -y
    seahorse
    ```


## Referências

[1] OPENAI. ***Install Seahorse on Ubuntu.*** Disponível em: <https://chat.openai.com/c/123e4567-e89b-12d3-a456-426614174000> (texto adaptado). Acessado em: 23/04/2023 17:11.

[2] OPENAI. ***Vs code: editor popular.*** Disponível em: <https://chat.openai.com/c/b640a25d-f8e3-4922-8a3b-ed74a2657e42> (texto adaptado). Acessado em: 23/04/2024 17:10.
