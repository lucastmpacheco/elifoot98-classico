# Elifoot 98 — versão clássica para Windows e Linux

O Elifoot 98 de André Elias e Ricardo Correia, **versão 98.003** (a última do autor, 1998), igual ao original, refeito para rodar nativamente nos sistemas modernos. Inclui o jogo e o Editor de Equipas, com os dados e as telas da distribuição original.

## Windows (10 e 11, 32 e 64 bits)

1. Baixe `windows/Elifoot98-classico-instalador.exe` (confira com o `.sha256`).
2. Execute. Na primeira vez o Windows pode mostrar "O Windows protegeu o computador": clique em **Mais informações** → **Executar assim mesmo** (o instalador não tem assinatura digital paga).
3. Instale numa pasta onde o seu usuário possa gravar (a sugerida é `C:\Jogos\Elifoot 98`), não em "Arquivos de Programas".

## Linux (64 bits, nativo, sem Wine)

**Requisitos:** Linux x86_64 com glibc 2.34 ou mais nova (Ubuntu 22.04, Debian 12, Fedora 35 ou mais novos) e GTK2:
- Debian/Ubuntu/Mint: `sudo apt install libgtk2.0-0`
- Fedora: `sudo dnf install gtk2`
- Arch/Manjaro: `sudo pacman -S gtk2`
- openSUSE: `sudo zypper install gtk2`

**Instalação:**
1. Baixe `linux/Elifoot98-classico-98.003-linux-x86_64.tar.gz` (confira com o `.sha256`).
2. Extraia numa pasta sua, por exemplo `~/Jogos`: `tar xzf Elifoot98-classico-98.003-linux-x86_64.tar.gz -C ~/Jogos` (o jogo grava na própria pasta: não use `/opt` nem `/usr`).
3. Atalhos no menu de aplicativos (opcional): `~/Jogos/Elifoot98/instalar-atalho.sh`
4. Para jogar sem atalho: `cd ~/Jogos/Elifoot98 && ./elifoot98-classico` (o editor: `./elifoot98-editor`).

## Registro

O jogo vem **não registrado**, como o original: sem registro não há empréstimos, compra de jogadores nem ver o plantel dos outros. Para registrar, use a contra-senha dos autores para o código que aparece na janela de registro. O código muda de computador para computador (no Linux, depende da data de criação da pasta do jogo).

## Os links "Source code" do GitHub

As releases do GitHub mostram sempre "Source code (zip/tar.gz)": aqui eles contêm só este README e o LEIA-ME, não o código do jogo.

## Direitos

Elifoot 98 © 1998 André Elias e Ricardo Correia. "Autorizada apenas a distribuição livre e gratuita. A comercialização ou distribuição comercial, sob qualquer forma, é proibida sem autorização escrita dos autores." (do "Acerca" do jogo). Esta versão é gratuita: não a venda.
