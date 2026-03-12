# season-anime
Um projeto feito para obter informações dos animes da temporada atual, de forma prática.
Estou migrando esse projeto para o codeberg.org

# altera a senha do wsl UBUNTU 
wsl -u root

 passwd aluno

# instalar o nvim instável

sudo add-apt-repository ppa:neovim-ppa/unstable

sudo apt update && sudo apt install neovim

nvim --version

sudo apt update

# instalar o lazyVim

sudo apt install git xclip curl grep ripgrep fd-find unzip build-essential

git clone https://github.com/LazyVim/starter ~/.config/nvim

rm -rf ~/.config/nvim/.git

# tudo em apenas uma linha.
sudo add-apt-repository -y ppa:neovim-ppa/unstable && sudo apt update && sudo apt install -y neovim git xclip curl grep ripgrep fd-find unzip build-essential && git clone https://github.com/LazyVim/starter ~/.config/nvim && rm -rf ~/.config/nvim/.git && nvim --version
# Angular 

curl -o- https://raw.githubusercontent.com | bash && \
export NVM_DIR="$HOME/.nvm" && \
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" && \
nvm install 22 && \
nvm use 22 && \
npm install -g @angular/cli


# ideias

 mostrar em gráficos, dados numericos para facilitar compreensão
