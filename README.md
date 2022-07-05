# Ubuntu 20.04

```
sudo apt-get update && \
sudo apt-get -y upgrade && \
sudo apt-get -y install wget gpg fonts-firacode vim aptitude git nodejs npm

```

### VSCode

```
sudo apt-get install wget gpg
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
sudo install -o root -g root -m 644 packages.microsoft.gpg /etc/apt/trusted.gpg.d/
sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/trusted.gpg.d/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
rm -f packages.microsoft.gpg

```

```
sudo apt install apt-transport-https
sudo apt update
sudo apt install code # or code-insiders
```

### VSCode Settings

Type Ctrl + p.

```
ext install dracula-theme.theme-dracula
ext install naumovs.color-highlight
ext install mikestead.dotenv
ext install dbaeumer.vscode-eslint
ext install ritwickdey.LiveServer
ext install MS-vsliveshare.vsliveshare-pack
ext install PKief.material-icon-theme
ext install styled-components.vscode-styled-components
ext install rocketseat.RocketseatReactJS
ext install rocketseat.RocketseatReactNative
ext install miguelsolorio.fluent-icons
ext install streetsidesoftware.code-spell-checker
ext install rvest.vs-code-prettier-eslint
ext install humao.rest-client
```

You can find in the Command Palette (Ctrl+Shift+P) to **Toggle** or via Settings

### Copiar as configurações do arquivo settings.json

### Alterar as informações do Dockerfile e docker-compose.yml
