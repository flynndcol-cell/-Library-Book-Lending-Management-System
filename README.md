# -Library-Book-Lending-Management-System
一個初具雛形的 圖書館 必備軟件，有問題 or BUG 可以反饋讓我們知道。 **本軟件使用python開發

📋 圖書借閱管理系統 — 用戶須知 / User Notice
🇹🇼 繁體中文說明 (Traditional Chinese)
歡迎使用本圖書借閱管理系統（v0.3.4）。為了確保您的系統順暢運行與借閱資料安全，請在開始使用前詳細閱讀以下注意事項：

1. 系統運行與環境
免安裝 Python：本系統為獨立執行的桌面應用程式，雙擊 LibraryBookLendingManagementSystem_v0.3.4.exe 即可直接開啟，電腦中不需要安裝 Python 或任何額外套件。

單機離線運作：系統完全在您的本機電腦中運行，不需要網路連線，所有資料均妥善保存在本地，兼顧隱私與安全性。

2. 資料儲存與擺放位置（非常重要）
檔案必須同級存放：應用程式 LibraryBookLendingManagementSystem_v0.3.4.exe 與 data 資料夾必須放在同一個目錄下。所有的書籍、會員與借閱紀錄都會自動儲存在 data/library_data.json 檔案中。

切勿單獨移動執行檔：若要將程式捷徑放在桌面，請對該 .exe 檔案點擊滑鼠右鍵選擇 「傳送到 > 桌面捷徑」。絕對不要把執行檔單獨剪下貼到其他地方，否則程式會找不到資料庫而顯示為全新空白狀態。

3. 定期備份習慣
建議您養成定期備份的好習慣。只要將整個 data 資料夾複製一份到備份位置（例如隨身碟或雲端硬碟），就能在電腦發生突發狀況時確保資料不遺失。

4. 未來版本更新
若日後軟體推出更新版本，您只需要下載新的執行檔並替換舊檔案即可。

旁邊的 data 資料夾請完全不要動，更新後系統就會自動讀取您原有的所有圖書與會員資料。

5. Windows 系統安全警示說明
當您首次開啟應用程式時，若 Windows 畫面上跳出藍色或紅色的防護視窗（如：「Windows 已保護您的電腦」），這是正常現象，請放心使用。

這是因為本程式為獨立開發的小型工具，未向微軟購買商業數位憑證所致。

解決方式：只需點擊警示視窗中的 「其他資訊」 文字，再點選右下角的 「仍要執行」 按鈕，即可順利進入系統。

🇬🇧 English Documentation
Welcome to the Library Management System (v0.3.4). Please read the following notes carefully before using the application to ensure smooth operation and data security:

1. System Requirements & Environment
No Python Required: This system is a standalone desktop application. Simply double-click LibraryBookLendingManagementSystem_v0.3.4.exe to launch it. No Python installation or extra packages are needed.

Offline Operation: The software runs locally on your computer without requiring an internet connection, ensuring high privacy and data security.

2. Data Storage & File Location (Crucial)
Keep Files in the Same Folder: The executable LibraryBookLendingManagementSystem_v0.3.4.exe and the data folder must remain in the same directory. All book, member, and borrowing records are automatically saved in data/library_data.json.

Do Not Move the Executable Alone: If you want a desktop shortcut, right-click the .exe file and select "Send to > Desktop (create shortcut)". Do NOT move or cut the .exe file alone to another location, as it will lose connection with the data folder and show a blank database.

3. Regular Backups
We strongly recommend making regular backups. Simply copy the entire data folder to a backup device (such as a USB drive or cloud storage) to prevent data loss in case of hardware failures.

4. Future Updates
When future software updates are released, simply download the new executable and replace the old .exe file.

Do NOT delete or modify the data folder, and the new version will automatically load all your existing library data.

5. Windows SmartScreen Security Warning
When launching the executable for the first time, Windows may display a security prompt ("Windows protected your PC"). This is completely normal and safe.

Since this is a lightweight, independently developed software without a commercial digital certificate, Windows flags unrecognized applications by default.

How to proceed: Click on "More info" inside the warning window, then click the "Run anyway" button in the bottom right corner to open the application.

# 📚 圖書借閱管理系統 (Library Management System) v0.3.4

一個簡單實用的單機版圖書借閱管理桌面應用程式。採用 Python 與 Tkinter 開發，資料直接儲存於本地，適合小型單位或個人進行基本的書籍與會員管理。

A simple and practical standalone library management system built with Python and Tkinter. Designed for local data storage, suitable for small institutions or personal use to manage books and members.

---

## 🇹🇼 繁體中文說明

### 🛠️ 目前主要功能
1. 書籍管理：支援 ISBN條碼、書名、作者、分類、總數量與可借數量追蹤，以及即時關鍵字搜尋。
2. 會員管理：記錄會員基本資料（編號、姓名、電話），支援帳號停權與未繳罰款追蹤。
3. 借還書作業：支援快速輸入、自訂借閱天數與每日逾期罰款計算。
4. 歷史紀錄與數據：保留借閱歷史軌跡，並提供簡單的館藏與借閱數據統計儀表板。

### ⚠️ 關於 Windows 執行防護提示的說明
當您下載並首次雙擊執行 `main.exe` 時，Windows 系統可能會跳出藍色或紅色的防護視窗（如：「Windows 已保護您的電腦」）。

這是正常現象，請放心，本程式絕對安全無毒。
由於本系統是獨立開發的小型軟體，尚未向微軟購買商業數位憑證，因此 Windows 會對未知的應用程式進行安全提示。如果您或使用者遇到這個提示，只需按照以下步驟即可正常開啟：

1. 點擊警告視窗中的 「其他資訊」 (More info) 連結文字。
2. 畫面右下角將會出現 「仍要執行」 (Run anyway) 按鈕，點擊它即可順利啟動程式。

---

## 🇬🇧 English Documentation

### 🛠️ Current Features
1. Book Management Tracks ISBNbarcode, title, author, category, total copies, available copies, and real-time keyword search.
2. Member Management Manages member profiles (ID, name, phone), account suspension status, and unpaid fines.
3. Borrowing & Returns Supports quick entry, custom loan periods, and overdue fine calculations.
4. History & Statistics Keeps track of borrowing history and provides a basic statistics dashboard.

### ⚠️ Note on Windows SmartScreen Warning
When running `main.exe` for the first time, Windows may display a security prompt (Windows protected your PC). 

This is completely normal and safe. 
Since this is a lightweight, independently developed application without a commercial digital certificate, Windows flags unrecognized binaries. To proceed
1. Click on the More info link in the warning window.
2. Click the Run anyway button that appears in the bottom right corner to launch the application.
