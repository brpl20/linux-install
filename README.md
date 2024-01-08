# Linux-Ubuntu-Ubuntu-Post-Install
Shell Script de pós instalação do Linux Mint para utilização pessoal.

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
- Teclado Internacional com "ç": [manual](https://www.vivaolinux.com.br/topico/Debian/Teclado-US-internacional-nao-consigo-configurar-para-usar-acentos-e-nem-cedilha) e [este](https://ubuntuforum-br.org/index.php/topic,123209.0.html)
- Desabilitar Secure Ctrl+V no Terminal: `Terminal Preferences => Clipboard [ ] Show unsafe past dialog`
- Alterar o Ctrl + Shift + C ou V no Terminal: `Terminal Preferences => ShortCuts`

## Pra Ajeitar no Firefox 
- https://www.danielkossmann.com/ajeitando-cedilha-errado-ubuntu-linux/


# Basics
1. Essentials: ```sudo apt install -y git imagemagick zsh curl vim jq tree```
2. omzh: ```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

## Basics - GitHub 
1. ```curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg```
2. ```echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null```
3. ```sudo apt update```
4. ```sudo apt install -y gh```
5. ```gh --version```

# Repos Clonar 
`mkdir "~/code"`
`cd ~/code"`
`git clone git@github.com:brpl20/prc4.git/wikit.git/learning-blog.git/brpl-blog.git`


# Gems
- Docx 
- omnidocx

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


# Actions 
* Clonar Repositórios Padrões
* Configurar Github
* Baixar Configurações OhMyzshel 

# Remove Apps
* Remover o Celluloid (Aplicativo de Vídeos): 'sudo apt purge celluloid'
