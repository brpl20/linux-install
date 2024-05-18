# Linux-Ubuntu-Ubuntu-Post-Install
Shell Script de pós instalação do Linux Mint para utilização pessoal.

- https://github.com/lewagon/setup/blob/master/ubuntu.md

# Configurações de Instalaçao
- Teclado: `English (US) - English (US, alt. intl.)`

# Passo-a-Passo
1. Firefox Sync
2. Chrome Sync
3. InSync: Trabalho (Microsoft) + Pessoal (Google)
4. GitHub
5. Basics
6. Coding Setup 

# Configurações Iniciais
## Teclado Internacional com "ç":
  - [manual](https://www.vivaolinux.com.br/topico/Debian/Teclado-US-internacional-nao-consigo-configurar-para-usar-acentos-e-nem-cedilha)
  - [este](https://ubuntuforum-br.org/index.php/topic,123209.0.html)
  - [esse-tambem](https://www.danielkossmann.com/ajeitando-cedilha-errado-ubuntu-linux/)

## Terminal
- Desabilitar Secure Ctrl+V no Terminal: `Terminal Preferences => Clipboard [ ] Show unsafe past dialog`
- Alterar o Ctrl + Shift + C ou V no Terminal: `Terminal Preferences => ShortCuts`
- omzh:

```bash
*c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

```bash
sudo apt install -y git imagemagick zsh curl vim jq tree```

- Atuin:

```bash
/bin/bash -c "$(curl --proto '=https' --tlsv1.2 -sSf https://setup.atuin.sh)"```

```bash 
atuin login | atuin sync``` (ver como puxar todos os comandos inclusive das versões passadas) ToDO
```

### DotFiles 
- Aliases
- Syntax Highlight


# Basics
## Basics - GitHub 
### GH
```bash
curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg
```

```bash
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null
```

```bash
sudo apt update
```

```bash
sudo apt install -y gh
```

```bash
gh --version```
```

```bash
gh auth login -s 'user:email' -w -ssh -Y
# ssh / Y / enter / enter
``` 

## Create Code Folder & Repos Clonar 
`mkdir "~/code"`
`cd ~/code"`
```gh repo clone brpl20/procstudio_front``` 
```gh repo clone brpl20/procstudio_front``` 
```gh repo clone brpl20/procstudio_front``` 
```gh repo clone brpl20/procstudio_front``` 

## Coding - Python
- Pré Instalado no Ubuntu
```sudo apt install python3-venv python3-pip```

## Coding - Ruby
```bash
sudo apt install -y build-essential tklib zlib1g-dev libssl-dev libffi-dev libxml2 libxml2-dev libxslt1-dev libreadline-dev libyaml-dev```
```bash
git clone https://github.com/rbenv/rbenv.git ~/.rbenv```
```bash
rbenv install 3.3```
```bash
rbenv global 3.3```
```bash
exec zsh
```bash
ruby -v```

## Coding - Js/Node

## Coding - Java

## Gems
- Docx 
- omnidocx

## Apps 
* Sublime Text 
  - Sublime Plugins
* WPS 
* PDF 
* Tesseract: OCR
* ffmpeg
* VLC Media Player 
* youtube-dl
* spotify
* Oh My Sh
* Telegram(web:)
* Insync / Dropbox 
* Ruby
 - Rails 
 - gem install rake bundler rspec rubocop rubocop-performance pry pry-byebug hub colored octokit 
* Python
* Assinador Receita Fedral 
* WorkRave
* F.Lux
* ScreenShot (flameshot)
* AWS : Configurar Keys 
* Heroku : Configurar Keys
* Openbox => Atalhos
* Dmenu (alt+f3) => menu rápido/simples
* espanso => estilo autohokey do win
* autoin (Terminal comandos rapidos)


# Actions 
* Clonar Repositórios Padrões
* Configurar Github
* Baixar Configurações OhMyzshel 

# Remove Apps
* Remover o Celluloid (Aplicativo de Vídeos): 'sudo apt purge celluloid'
