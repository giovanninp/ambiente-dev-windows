# 1: POWERLINE FONTS (Fonte: <[Ambiente de Desenvolvimento (React e React Native) no Windows com WSL ](https://medium.com/@gusflopes86/ambiente-de-desenvolvimento-react-e-react-native-no-windows-com-wsl-f505906d636c)> de Gustavo Lopes)

### 1.1 Download Powerline Fonts na pasta /Downloads
<[PowerlineFonts](https://github.com/powerline/fonts)>

### 1.2 Extraia os arquivos do ```fonsts-master.zip```

### 1.3 Execute o comando no PowerShell em modo de administrador
```powershell
cd ${HOME}\Downloads\fonts-master\fonts-master
```

### 1.4 Será nessário dar uma permissão para executar o instalador
```powershell
Set-ExecutionPolicy Bypass
```

### 1.5 Agora poderá executar o instalador com:
```poweshell
./install.ps1
```

# 2: [SCOOP](https://scoop.sh/)

### 2.1 Abra o PowerShell em modo de administrador e execute:
```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
```

### 2.2 Instale Scoop com:
```powershell
Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')
```
### ou 

```
iwr -useb get.scoop.sh | iex
```

# 3: GIT
### Execute o código:

```
scoop install git
```

# 4: NVM

### Execute o código:

```
scoop install nvm

nvm install node
```

# OPC: YARN

```
scoop install yarn
```

# REFERÊNCIAS:
- https://medium.com/@gusflopes86/ambiente-de-desenvolvimento-react-e-react-native-no-windows-com-wsl-f505906d636c