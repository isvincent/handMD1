# 🏔️ 高中地理｜第 4 章 地形系統

> 用「**投入 → 作用 → 產出**」的系統觀點，看懂地形怎麼形成、如何改變，又怎樣影響我們的生活。

這是一份 **HackMD 書本模式（Book Mode）** 數位教材，同時附有可直接部署到 **GitHub Pages** 的課程首頁。

- 📘 **HackMD 書本**：`https://hackmd.io/@USERNAME/geo-ch4`（完成設定後可用）
- 🌐 **課程網站**：`https://<你的 GitHub 帳號>.github.io/<儲存庫名稱>/`

---

## 📚 教材內容

| 篇章 | 檔案 | 重點 |
|---|---|---|
| 📖 書本目錄 | [`notes/00-book.md`](notes/00-book.md) | HackMD 書本模式的目錄頁 |
| 0 導論 | [`notes/01-intro.md`](notes/01-intro.md) | 台江內海的故事、學習目標、本章架構 |
| **第一節 地形系統與營力** | | |
| 1-1 內營力 | [`notes/02-endogenic.md`](notes/02-endogenic.md) | 地形系統運作圖、褶曲、斷層、火山 |
| 1-2 外營力 | [`notes/03-exogenic.md`](notes/03-exogenic.md) | 風化、崩壞、差異侵蝕、八卦台地 |
| 🧪 活動 4-1 | [`notes/04-activity-4-1.md`](notes/04-activity-4-1.md) | 女王頭的歲月痕跡 |
| **第二節 流水、冰河塑造的地形與辨識** | | |
| 2-1 河流地形 | [`notes/05-fluvial.md`](notes/05-fluvial.md) | 峽谷、瀑布、沖積扇、三角洲、曲流、河階 |
| 2-2 岩溶地形 | [`notes/06-karst.md`](notes/06-karst.md) | 滲穴→殘丘、鐘乳石、泰國洞穴救援 |
| 2-3 冰河地形 | [`notes/07-glacial.md`](notes/07-glacial.md) | 冰斗、角峰、U 型谷、峽灣、冰磧、黃土 |
| 🧪 活動 4-2 | [`notes/08-activity-4-2.md`](notes/08-activity-4-2.md) | 地形系統運作（屏東平原） |
| **第三節 風、波浪塑造的地形與辨識** | | |
| 3-1 風成地形 | [`notes/09-aeolian.md`](notes/09-aeolian.md) | 礫漠、岩漠、沙丘、黃土高原 |
| 3-2 海岸地形 | [`notes/10-coastal.md`](notes/10-coastal.md) | 海蝕、海積、離水與沉水海岸 |
| 🧪 活動 4-3 | [`notes/11-activity-4-3.md`](notes/11-activity-4-3.md) | 桃園海岸的變遷 |
| 🔎 地理探究 | [`notes/12-inquiry.md`](notes/12-inquiry.md) | 地形變遷、突堤效應、地名裡的地形 |
| 📝 總複習 | [`notes/13-review.md`](notes/13-review.md) | 概念圖、判讀口訣、名詞索引、自我評量 |

**每篇都包含**：Mermaid 流程圖解、比較表格、🗺️ Google 地圖線上踏查、✅ 隨堂小測（答案收在摺疊區塊）。

---

## 🗂️ 儲存庫結構

```
.
├── index.html        # GitHub Pages 首頁（含站內閱讀器）
├── README.md         # 本說明文件
├── .gitignore        # 排除課本 PDF
└── notes/            # HackMD 筆記原始檔（Markdown）
    ├── 00-book.md    # 書本目錄
    ├── 01-intro.md
    └── ... 13-review.md
```

---

## 🚀 一、建立 HackMD 書本

1. **取代帳號名稱**：把 `notes/` 所有檔案中的 `USERNAME` 換成你的 HackMD 帳號或團隊路徑名稱。
   用 VS Code 的「在檔案中取代」（`Ctrl` + `Shift` + `H`）一次替換最快。
2. **建立 13 篇筆記**：在 HackMD 新增筆記，把 `01-intro.md`～`13-review.md` 的內容分別貼上（開頭的 YAML 區塊會自動設定標題與標籤）。
3. **設定自訂連結**：每篇筆記點「分享 → 發布」，把自訂連結（permalink）設為對應名稱：

   | 檔案 | permalink |
   |---|---|
   | `00-book.md` | `geo-ch4` |
   | `01-intro.md` | `geo-ch4-01` |
   | `02-endogenic.md` | `geo-ch4-02` |
   | … | … |
   | `13-review.md` | `geo-ch4-13` |

4. **建立書本目錄**：新增一篇筆記貼上 `00-book.md`，發布後在分享選單切換為 **書本模式（Book mode）**。
5. **確認權限**：所有筆記的「閱讀權限」設為「所有人」，學生才能開啟。

> 💡 HackMD 的介面與選項名稱會隨版本調整；若找不到上述按鈕，請參考 HackMD 官方說明中「Book mode」與「Publish / Permalink」的章節。

---

## 🌐 二、部署 GitHub Pages 首頁

1. 在 GitHub 新增儲存庫（例如 `geo-landform-system`），上傳 `index.html`、`README.md`、`.gitignore` 與 `notes/` 資料夾。
2. 開啟 `index.html`，修改最上方的設定：
   ```js
   const HACKMD_USER = "USERNAME";   // 改成你的 HackMD 帳號
   const BOOK_SLUG = "geo-ch4";      // 書本目錄的 permalink
   ```
3. 到儲存庫 **Settings → Pages**，Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾 `/ (root)`，按 Save。
4. 約 1～2 分鐘後即可在 `https://<帳號>.github.io/<儲存庫名稱>/` 看到網站。

**首頁功能**
- 章節卡片：每篇可「在本站閱讀」或「前往 HackMD」。
- 站內閱讀器：直接讀取 `notes/*.md`，支援 HackMD 的 `:::info / success / warning`、`:::spoiler` 摺疊、Mermaid 圖與核取方塊。即使還沒建立 HackMD 書本，網站也能完整閱讀。
- 深淺色切換、手機版排版。

> ⚠️ 站內閱讀器需透過網址（GitHub Pages 或本機伺服器）開啟；直接雙擊 `index.html` 會因瀏覽器安全限制無法載入筆記。本機預覽可在資料夾中執行：
> ```bash
> python -m http.server 8000
> ```
> 再開啟 `http://localhost:8000`。

---

## 🧑‍🏫 教學建議

| 節次 | 建議內容 | 課堂活動 |
|---|---|---|
| 第 1 節 | 導論＋1-1 內營力 | 用 Google 地圖觀察 921 斷層崖、基隆山 |
| 第 2 節 | 1-2 外營力 | 學生活動 4-1 女王頭（分組辯論：保存或順其自然） |
| 第 3 節 | 2-1 河流地形 | 等高線判讀練習：沖積扇、河階 |
| 第 4 節 | 2-2 岩溶＋2-3 冰河 | 學生活動 4-2 屏東平原 |
| 第 5 節 | 3-1 風成＋3-2 海岸 | 學生活動 4-3 桃園海岸 |
| 第 6 節 | 地理探究 | 地名裡的地形（臺灣堡圖判讀）＋總複習 |

---

## ©️ 版權說明

- 本教材依高中地理「地形系統」單元的學習內容**重新撰寫**，未收錄原教科書之文字與圖片。
- 原教科書 PDF 屬出版社著作，已透過 `.gitignore` 排除，**請勿上傳至公開儲存庫**。
- 若要加入圖片，建議使用自行拍攝、或 Wikimedia Commons 等標示 CC 授權的圖片，並註明出處。

---

*Made with HackMD Book Mode × GitHub Pages*
