---

# 🎓 大學三年課程整合專案總覽

本專案整合了大學三年來的重要課程內容與專題作品，涵蓋 **Python 程式設計**、**人工智慧（AI）**、**MVC 架構開發**、**計算機視覺（Computer Vision）** 等主題，方便後續查閱與維護。

---

## 📁 專案目錄結構

### 🔹 `113_1_class`
- **課程主題**：計算機視覺（Computer Vision）
- **內容特色**：
  - 多章節 Jupyter Notebook 筆記與教學
  - 多個實作專題：
    - 車牌號碼辨識（License Plate Recognition）
    - 棋盤專案（Chessboard Detection）
    - 人臉辨識（Face Recognition）
  - 附帶測試圖片與結果輸出圖

---

### 🔹 `113_1_MVC`
- **課程主題**：MVC 架構應用
- **內容特色**：
  - Visual Studio 解決方案（.sln）專案
  - 主要程式集中於 `20241113_CW/` 子資料夾
  - 適合觀摩 Controller / View / Model 區隔實作方式

---

### 🔹 `113_1_MVC_HW`
- **課程主題**：MVC 架構作業
- **內容特色**：
  - 與 `113_1_MVC` 課程搭配
  - 提供額外延伸實作與作業練習

---

### 🔹 `113_AI_class`
- **課程主題**：人工智慧應用
- **內容特色**：
  - 多次作業與演算法練習：
    - `HW2.py`：第二次作業
    - `HW4/`：第四次作業資料夾
    - `ga.py`：遺傳演算法實作（Genetic Algorithm）
    - `test.ipynb`：整合測試程式

---

### 🔹 `1122_python_final`
- **課程主題**：Python 程式設計期末專案
- **內容特色**：
  - 多個題目實作範例：
    - `problem1.py` 至 `problem4.py`
    - `problem2.ipynb`
  - `utils.py`：常用工具函式
  - `data/` 與 `Bonus/`：資料與額外挑戰題資源

---

### 🔹 `1122_class_note`
- **課程主題**：Python 課程筆記與專題實作
- **內容特色**：
  - 多個應用型小工具與資料分析專案：
    - 音標轉換工具（多版本）
    - 兩岸用詞爬蟲
    - T1 聯盟籃球數據分析
    - 醫療與電影數據處理
    - 遊戲專案
  - 子資料夾結構清晰：
    - `knowledgebase/`：知識庫資料
    - `fungame_HTML/`：遊戲前端內容
    - `exams/`：考試題目與練習
    - `code/`：Python 程式檔案整理區

---

## ⚙️ 使用說明

1. 每個資料夾對應一門課程或一項專案，皆可獨立使用。
2. 多數資料夾內含 `README.md` 或註解，說明用途與執行方式。
3. 若專案包含 `requirements.txt`，請使用 `pip install -r requirements.txt` 安裝所需套件。
4. 建議使用 Python 3.x 版本以確保最佳相容性。

---

## 📝 注意事項

- 部分專案需特定環境（如 Jupyter Notebook、特定套件庫）才能正確執行。
- 若遇到套件問題，建議使用虛擬環境（如 `venv` 或 `conda`）部署。
- 圖片與數據資料部分可能較大，建議視情況排除追蹤（加入 `.gitignore`）。

---
