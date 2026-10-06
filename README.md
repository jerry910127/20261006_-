# 🍿 SnackSure 零食保險販賣機 (Snack Vending Micro-Insurance)

> **Vibe Coding 作業實作**：將休閒零食與微保險（Micro-Insurance）結合的沉浸式互動 Web App。  
> 透過極低門檻、生動復古販賣機介面、Web Audio 晶片音效與趣味調味加料，徹底顛覆傳統金融保險的枯燥嚴肅感！

---

## 🌟 核心特色 (Key Features)

1. **實體感復古販賣機 (Retro Vending Machine UI)**
   - 擬真玻璃展示櫥窗，擺放 6 款零食保險（A1~C2）。
   - 復古綠色點陣 LED 動態資訊面板。
   - 投幣孔互動（支援隨時投幣加值）、實體微動開關小鍵盤（按鍵音效支援）。
   - 下方真實重力彈跳式取貨口（Pickup Door），購買後掉落咚聲撞擊動畫。

2. **零食防護營養成分表 (Nutrition Facts - 條款簡化版)**
   - **熱量 (Calories)** $\rightarrow$ 基礎保費（如：NT$ 15 / 日起）
   - **成分 (Ingredients)** $\rightarrow$ 保障內容（旅程延誤、跌倒、骨折、急診實支實付）
   - **保存期限 (Best Before)** $\rightarrow$ 保障期間（單日試吃包、週末狂歡包、家庭冒險號）

3. **客製化調味加料 (Custom Seasoning)**
   - 🌶️ **加辣**：意外保額雙倍調味升級
   - 🧀 **加起司**：加購行程延誤與不便升級條款
   - 🧄 **加蒜香**：急診與門診實支實付加倍
   - 🎁 **結合真實零食 (Bundling)**：投保成功附贈超商零食折價序號

4. **Web Audio API 純合成音效系統 (零外部依賴)**
   - 投幣清脆金屬聲、鍵盤嗶嗶聲、馬達轉動掉落撞擊咚聲、結帳成功和弦。
   - 支援右上角一鍵靜音/開啟切換。

5. **Gamification 遊戲化功能**
   - 🤖 **AI 零食推薦師**：3 題生活心理測驗，智慧推薦專屬保單。
   - 🎰 **幸運盲盒扭蛋**：一鍵隨機抽獎，自動升級隱藏款超值保單。
   - 📸 **數位保單零食包 (Unboxing Modal)**：開箱核發保單，支援複製與社群 IG 分享。

---

## 🚀 步驟三：如何上傳至 GitHub 並啟用 GitHub Pages

按照以下步驟即可將此專案免費公開至 GitHub Pages，供任何人線上操作體驗：

### 步驟 3-1：在 GitHub 建立新儲存庫 (New Repository)
1. 前往 [GitHub](https://github.com/) 登入帳號。
2. 點擊右上角 `+` $\rightarrow$ **New repository**。
3. Repository name 填寫例如：`snacksure-vending-machine`。
4. 設定為 **Public**（公開），其餘不用勾選，點擊 **Create repository**。

### 步驟 3-2：上傳專案檔案 (方式 A：Git 命令列)
在目前專案資料夾下開啟 PowerShell 執行：

```bash
git init
git add .
git commit -m "feat: complete SnackSure vending machine interactive web app"
git branch -M main
git remote add origin https://github.com/<你的GitHub帳號>/snacksure-vending-machine.git
git push -u origin main
```

*(方式 B：直接用 GitHub 網頁拖曳上傳)*
若不熟悉 Git 指令，亦可直接在剛剛建立好的 GitHub 頁面點擊 **"uploading an existing file"**，把 `index.html`、`SPECIFICATION.md` 與 `README.md` 拖曳上傳並 Commit。

### 步驟 3-3：開啟 GitHub Pages 線上公開網站
1. 進入 GitHub 儲存庫頁面，點擊上方的 **Settings**（設定）。
2. 在左側選單找到 **Pages**（位於 Code and automation 區塊內）。
3. 在 **Build and deployment** 下的 **Branch**：
   - 選擇分支：`main`
   - 資料夾選擇：`/ (root)`
4. 點擊 **Save**。
5. 等待約 1~2 分鐘重新整理，上方就會出現你的專屬線上網址：  
   `https://<你的GitHub帳號>.github.io/snacksure-vending-machine/`
