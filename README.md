[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/PayGsiJk)
# GitHub 基本指南

## 本堂課目標

本課程目標是提供 GitHub 的簡要介紹，並提供進階學習資源與實作建議，協助學生在平台上開始運作。
本文翻譯自Github Classroom官方範例repo

## Git and GitHub

Git 是一款分散式版本控制系統（VCS）。其核心功能在於精確追蹤程式碼變更、促進團隊協作與資源共享。
透過 Git，我們可以記錄專案的每一次更動，確保擁有完整的歷史版本資訊，並在必要時輕鬆回溯至舊版本。
它簡化了多人協作流程，讓團隊成員能在同一專案上並行開發，最後再將各自的變更合併（Merge）為最終版本。

GitHub 則是基於 Git 核心技術的線上平台，提供了易於操作的圖形化介面。它被廣泛應用於軟體界及其他領域，用於協作開發與維護專案歷史。

GitHub 是全球先進技術的匯集地。無論是數據視覺化或是開發新遊戲，其社群與工具鏈都能提供必要的支援。
本課程只會用到基礎功能。

## 理解 GitHub 工作流

GitHub flow 是一種輕量化的工作流程，讓我們在不影響既有成果的前提下，安全地進行實驗與協作。

### 儲存庫 Repositories

儲存庫是專案運行的核心單位，可視為專案的資料夾。它包含了所有專案檔案及其完整的修訂歷史紀錄。可以獨立運作，也可以邀請他人共同開發。

### 複製 Cloning 

在 GitHub 上建立的儲存庫儲存於雲端遠端。透過 Clone 操作，工程師可以在本地電腦建立副本，並使用 Git 同步兩者。這有助於修復問題、增刪檔案以及處理大型提交（Commits），且能使用偏好的編輯器而非僅限於網頁介面。
Clone 的關鍵在於它會下載當前所有的歷史數據，包括所有檔案與資料夾的歷史版本，這對於版本回溯與實驗極具價值。 
To learn more about cloning, read ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### 提交與推送 Committing and pushing

- Commit（提交）：當專案達到特定階段時，建立一個「檢查點」（Checkpoint）。建議附上具描述性的 Commit Message（例如：「新增包含專案資訊的 README」），以利自己與團隊成員理解變更內容。

- Push（推送）：將本地端的提交同步至 GitHub 遠端儲存庫，使指導者或團隊成員能看到最新的工作進度。

## 💻 GitHub 技術術語

### 儲存庫 

隨著專案增加，管理儲存庫可能變得複雜。可以使用 ["GitHub dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) 來導覽與查看專案資訊。

README：每個儲存庫都應包含 README 檔案，用以說明專案用途、功能及使用方法。這是與他人溝通的首要文件。
To learn more about repositories read ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) and ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### 分支 Branches
分支用於隔離開發中的工作，避免影響最終成品。它允許我們在受控的環境中開發新功能、修復 Bug 或進行實驗。通常會從預設分支（main）建立新分支，待代碼經過審查（Code Review）或確認無誤後，再合併回主分支。
To learn more about branching, read ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### 分叉 Forks
Fork 是另一種複製儲存庫的方式，主要用於貢獻他人的專案。它讓我們在不影響原始專案的情況下自由修改，是開源軟體協作的標準做法。
To learn more about forking, read ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### 拉取請求 Pull requests, PR
當分支上的變更準備就緒，透過 PR 通知他人進行審查與討論。可以指派特定成員為審查者。獲得認可後，變更即可合併至 main 分支。
To learn more about pull requests, read ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 


### 議題 Issues
用於追蹤功能增強、工作任務或程式缺陷（Bug）。它是管理專案待辦清單與溝通開發計畫的工具。
Project Boards：大型專案可使用專案看板來排定優先順序。
自動化連結：可以將 PR 連結至 Issue，當 PR 合併時自動關閉該議題。
To learn more about issues and linking them to your pull requests, read ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### 個人檔案 (User Profile)

個人的 Profile 頁面透過儲存庫、貢獻紀錄與討論內容，向外界展示專業經歷。Profile README 則是一個獨特的視窗，可用於向潛在雇主展示技術特點。
To learn more about your user profile and adding and updating your profile README, read ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Markdown 的應用

GitHub 廣泛使用 Markdown 語法來編排 Issues、PR 和檔案內容。這種輕量標記語言有助於資訊結構化，提升可讀性，並支援插入圖片與 GIF。
To learn more about using GitHub’s flavor of markdown, read ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### 參與 GitHub 社群

GitHub 社群由學生、專業開發者、開源愛好者等多元背景組成。互動方式包括：

Star (標星)：收藏感興趣的儲存庫，這也是 GitHub Explore 推薦演算法的重要參數。

Follow (關注)：追蹤特定開發者的動態，其公開活動會顯示在 Dashboard。

Explore (探索)：github.com/explore 是發現新專案與開發者的門戶。

## 實作環節

* 建立一個 Pull Request 並通知我已完成課程。


## 📚  Resources 
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
