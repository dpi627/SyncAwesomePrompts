# 🤖 出色的 GitHub Copilot 客製化設定

透過社群貢獻的指令、提示和配置，增強您的 GitHub Copilot 體驗。獲得符合您團隊編碼標準和專案需求的一致 AI 協助。

## 🎯 GitHub Copilot 客製化功能

GitHub Copilot 提供三種主要方式來客製化 AI 回應，並針對您的特定工作流程、團隊指導方針和專案需求量身定制協助：

| **📋 [自訂指令](#-自訂指令)** | **🎯 [可重複使用的提示](#-可重複使用的提示)** | **🧩 [自訂聊天模式](#-自訂聊天模式)** |
| --- | --- | --- |
| 為程式碼生成、審查和提交訊息等任務定義通用指導方針。描述任務*如何*執行<br><br>**優點：**<br>• 自動包含在每個聊天請求中<br>• 整個儲存庫的一致性<br>• 多種實作選項 | 為特定任務建立可重複使用的獨立提示。描述*應該*做什麼，並提供可選的特定任務指導方針<br><br>**優點：**<br>• 消除重複的提示撰寫<br>• 可在團隊間共享<br>• 支援變數和相依性 | 在特定邊界內為每個請求定義聊天行為、可用工具和程式碼庫互動模式<br><br>**優點：**<br>• 上下文感知協助<br>• 工具配置<br>• 角色特定工作流程 |

> **💡 專業提示：** 自訂指令僅影響 Copilot Chat（不影響內聯程式碼補全）。您可以結合所有三種客製化類型 - 使用自訂指令作為一般指導方針，提示檔案用於特定任務，聊天模式控制互動上下文。

## 📝 貢獻

我們歡迎貢獻！請參閱我們的[貢獻指南](./CONTRIBUTING.md)了解如何提交新指令和提示的詳細資訊。

## 📋 自訂指令

團隊和專案特定指令，用於增強 GitHub Copilot 在特定技術和編碼實務上的行為：

| 標題 | 說明 | 安裝 |
| ----- | ----------- | ------- |
| [Angular 開發指令](instructions/angular.instructions.md) | Angular 特定編碼標準和最佳實務 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fangular.instructions.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fangular.instructions.md) |
| [ASP.NET REST API 開發](instructions/aspnet-rest-apis.instructions.md) | 使用 ASP.NET 建構 REST API 的指導方針 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Faspnet-rest-apis.instructions.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Faspnet-rest-apis.instructions.md) |
| [Azure Functions TypeScript](instructions/azure-functions-typescript.instructions.md) | Azure Functions 的 TypeScript 模式 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fazure-functions-typescript.instructions.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fazure-functions-typescript.instructions.md) |
| [Bicep 程式碼最佳實務](instructions/bicep-code-best-practices.instructions.md) | 使用 Bicep 的基礎架構即程式碼 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fbicep-code-best-practices.instructions.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fbicep-code-best-practices.instructions.md) |
| [Blazor](instructions/blazor.instructions.md) | Blazor 元件和應用程式模式 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fblazor.instructions.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-instructions%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Finstructions%2Fblazor.instructions.md) |

> **共有 36 個指令檔案** - [查看完整列表](instructions/)

> 💡 **使用方式：** 將這些指令複製到您的 `.github/copilot-instructions.md` 檔案或在您工作區的 `.github/instructions` 資料夾中建立特定任務的 `.github/.instructions.md` 檔案。

## 🎯 可重複使用的提示

針對特定開發場景和任務的即用提示範本，定義具有特定模式、模型和可用工具集的提示文字。

| 標題 | 說明 | 安裝 |
| ----- | ----------- | ------- |
| [ASP.NET Minimal API with OpenAPI](prompts/aspnet-minimal-api-openapi.prompt.md) | 建立具有適當 OpenAPI 文件的 ASP.NET Minimal API 端點 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Faspnet-minimal-api-openapi.prompt.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Faspnet-minimal-api-openapi.prompt.md) |
| [Azure 成本最佳化](prompts/az-cost-optimize.prompt.md) | 分析應用程式中使用的 Azure 資源並最佳化成本 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Faz-cost-optimize.prompt.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Faz-cost-optimize.prompt.md) |
| [Azure 資源健康檢查與問題診斷](prompts/azure-resource-health-diagnose.prompt.md) | 分析 Azure 資源健康狀況，從日誌和遙測中診斷問題 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Fazure-resource-health-diagnose.prompt.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Fazure-resource-health-diagnose.prompt.md) |
| [建立架構決策記錄](prompts/create-architectural-decision-record.prompt.md) | 為 AI 最佳化的決策文件建立架構決策記錄 (ADR) | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Fcreate-architectural-decision-record.prompt.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Fcreate-architectural-decision-record.prompt.md) |
| [建立實作計畫](prompts/create-implementation-plan.prompt.md) | 為新功能、重構或升級建立新的實作計畫檔案 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Fcreate-implementation-plan.prompt.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-prompt%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fprompts%2Fcreate-implementation-plan.prompt.md) |

> **共有 40 個提示檔案** - [查看完整列表](prompts/)

> 💡 **使用方式：** 在 VS Code 聊天中使用 `/prompt-name`，執行 `Chat: Run Prompt` 命令，或在開啟提示時點擊執行按鈕。

## 🧩 自訂聊天模式

自訂聊天模式為 GitHub Copilot Chat 定義特定行為和工具，為特定任務或工作流程提供增強的上下文感知協助。

| 標題 | 說明 | 安裝 |
| ----- | ----------- | ------- |
| [4.1 Beast Mode (VS Code v1.102)](chatmodes/4.1-Beast.chatmode.md) | GPT 4.1 作為頂級編碼代理 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2F4.1-Beast.chatmode.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2F4.1-Beast.chatmode.md) |
| [無障礙模式](chatmodes/accesibility.chatmode.md) | 無障礙模式 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Faccesibility.chatmode.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Faccesibility.chatmode.md) |
| [API 架構師模式](chatmodes/api-architect.chatmode.md) | 作為 API 架構師提供指導、支援和工作程式碼 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Fapi-architect.chatmode.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Fapi-architect.chatmode.md) |
| [Azure 首席架構師模式](chatmodes/azure-principal-architect.chatmode.md) | 使用 Azure Well-Architected Framework 提供專業的 Azure 首席架構師指導 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Fazure-principal-architect.chatmode.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Fazure-principal-architect.chatmode.md) |
| [批判性思考模式](chatmodes/critical-thinking.chatmode.md) | 挑戰假設並鼓勵批判性思考以確保最佳解決方案和結果 | [![安裝到 VS Code](https://img.shields.io/badge/VS_Code-安裝-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Fcritical-thinking.chatmode.md) [![安裝到 VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-安裝-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-chatmode%2Finstall%3Furl%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fdpi627%2FSyncAwesomePrompts%2Fmain%2Fchatmodes%2Fcritical-thinking.chatmode.md) |

> **共有 32 個聊天模式檔案** - [查看完整列表](chatmodes/)

> 💡 **使用方式：** 使用 `Chat: Configure Chat Modes...` 命令建立新的聊天模式，然後在聊天輸入中從 _Agent_ 或 _Ask_ 切換到您自己的模式。

## 🔄 同步資料夾

以下資料夾每日於 UTC 午夜自動同步：

- **chatmodes/** - GitHub Copilot 的聊天模式客製化  
- **instructions/** - 各種框架和技術的指令檔案  
- **prompts/** - 可重複使用的提示範本

## 🤖 自動化

此儲存庫使用 GitHub Actions 每天自動同步內容。工作流程：

1. 每日於 UTC 午夜執行
2. 也可透過工作流程調度手動觸發
3. 從來源儲存庫獲取最新內容
4. 使用新內容更新三個資料夾
5. 僅在有更新時提交和推送更改

來源：https://github.com/github/awesome-copilot

## 📚 其他資源

- [VS Code Copilot 客製化文件](https://code.visualstudio.com/docs/copilot/copilot-customization) - Microsoft 官方文件
- [GitHub Copilot Chat 文件](https://code.visualstudio.com/docs/copilot/chat/copilot-chat) - 完整聊天功能指南
- [自訂聊天模式](https://code.visualstudio.com/docs/copilot/chat/chat-modes) - 進階聊天配置
- [VS Code 設定](https://code.visualstudio.com/docs/getstarted/settings) - 一般 VS Code 配置指南

## 🛠️ 開發配置

此儲存庫使用各種配置檔案來確保一致的程式碼風格並避免換行符號問題：

- [`.editorconfig`](.editorconfig) - 在不同編輯器和 IDE 中定義編碼風格
- [`.gitattributes`](.gitattributes) - 確保文字檔案中的換行符號一致性
- [`.vscode/settings.json`](.vscode/settings.json) - 此儲存庫的 VS Code 特定設定
- [`.vscode/extensions.json`](.vscode/extensions.json) - 推薦的 VS Code 擴充功能

> 💡 **注意：** 此儲存庫中的所有 markdown 檔案使用 LF 換行符號（Unix 風格）以避免混合換行符號問題。儲存庫已配置為自動處理換行符號轉換。

## 📄 變更記錄

### 2024-12-19 - README 翻譯與增強
- 將 README.md 翻譯為繁體中文（zh-TW）
- 新增 VS Code 和 VS Code Insiders 安裝按鈕與指令
- 適配安裝 URL 指向當前儲存庫（dpi627/SyncAwesomePrompts）
- 新增各類別檔案的詳細表格（指令、提示、聊天模式）
- 新增變更記錄區塊記錄修改歷史
- 包含開發配置說明

### 先前修改
- 設定 GitHub Actions 自動同步機制
- 建立每日同步 chatmodes、instructions 和 prompts 資料夾的工作流程
- 配置從 github/awesome-copilot 儲存庫同步內容

## 📄 授權

此專案採用 MIT 授權 - 詳見 [LICENSE](LICENSE) 檔案。

## 🤝 行為準則

請注意，此專案以[貢獻者行為準則](CODE_OF_CONDUCT.md)發布。參與此專案即表示您同意遵守其條款。

## ™️ 商標

此專案可能包含專案、產品或服務的商標或標誌。Microsoft 商標或標誌的授權使用須遵守並必須遵循 [Microsoft 商標與品牌指導方針](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general)。
在此專案的修改版本中使用 Microsoft 商標或標誌不得造成混淆或暗示 Microsoft 贊助。
任何第三方商標或標誌的使用均受這些第三方政策約束。
