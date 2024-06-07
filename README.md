# vscode

vscodeの設定を書き出す。

## bashの履歴にコマンドを追加

```bash
cd && code .bash_history #履歴を表示
code --list-extensions #拡張機能を表示
```

## 拡張機能追加

```bash
code --install-extension hogehoge
```

### 一括インストール

 ```bash
 npm run install
 ```

## PC 環境設定

```powershell
# chocolatey install
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

```bash
choco install git nodejs vscode sourcetree starship hackfont googlechrome googlejapaneseinput -y

# Docker
choco install docker-desktop

# other: 7zip todoist
```
