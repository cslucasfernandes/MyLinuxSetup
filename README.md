# MyLinuxSetup

Atualmente eu estou usando o Ubuntu 22.04.1 LTS.

Primeiro, atualizo o meu sistema:

```
sudo apt update && sudo apt upgrade -y
```

Depois instalo alguns pacotes que são necessários para programação:

- git:
- curl:
- build-essential: Um pacote que contém os compiladores gcc e g++.
- zsh: Um Shell que permite adicionar temas e algumas extensões.

```
sudo apt install git curl build-essential zsh -y
```

Após isso, instalo alguns pacotes para auxiliar minha experiência com o Ubuntu:

```
sudo apt install pavucontrol gnome-tweaks -y
```
## Oh-My-ZSH

Antes é preciso usar o ZSH pelo menos uma vez e configurá-lo. Para abri-lo, use:

```
zsh
```

Instalando o Oh-My-ZSH:

(É necessário ter o pacote 'curl')

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
