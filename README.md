# 教育訓練環境安裝

## 需求軟體

- [VSCode](https://code.visualstudio.com/download) - 穩定版
- [VSCode Insider](https://code.visualstudio.com/insiders) - 預覽版，但保哥會用這個版本，請大家下載務必下載這個版本。
- [Node.js](https://nodejs.org/en/download) - v22.x 以上版本 （支援 Angular 與 Github Copilot Cli）
  - 驗證 Node.js 版本 `node -v`。


## 安裝套件

### 全域安裝

- Angular CLI
```bash
npm install -g @angular/cli
```
- Github Copilot Cli
```bash
npm install -g @github/copilot
```

### VSCode 套件
  - GitHub Copilot Chat
  - Chinese (Traditional) Language Pack

## 啟動專案

- 下載 `my-angular-app` 專案
```bash
git clone https://github.com/c1985925/my-angular-app.git
```
  
- 執行以下更新專案套件
```bash
npm install
```

- 執行以下指令啟動專案
```bash
npm start
```

- 開啟瀏覽器並輸入網址 http://localhost:4200/ 即可看到專案首頁


### 啟用 Github Copilot Chat

- 開啟右側側邊欄的 Github Copilot Chat 面板
- 選擇 `agent`
- 選擇 `GPT-4.1` 
- 輸入 `hi`，若 AI 有回應即可開始使用

### 啟用 Github Copilot CLI
- 在終端機輸入以下指令
```bash
copilot
```
- 信任資料夾
```bash
│ Do you trust the files in this folder?                                                                                         
│ ❯ 1. Yes                                                                                                                       
│   2. Yes, and remember this folder for future sessions                                                                         
│   3. No (Esc)                                                                                                                 
│ Confirm with number keys or ↑↓ keys and Enter, Cancel with Esc   
```
- 登入 Github 帳號
```bash
/login
```
- 選擇 Github.com 帳號
```bash
 What account do you want to log into?

 ❯ 1. GitHub.com
   2. GitHub Enterprise Cloud with data residency (*.ghe.com)
```

- 選擇模型
```bash
/model gpt-4.1
```

- 開始使用
```bash
<your question>
```

- 離開 Cli
```bash
/exit
```
