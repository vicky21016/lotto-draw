# 隨機大樂透號碼抽取系統

## 專案簡介  
這是一個 **隨機大樂透號碼抽取系統**，使用 **jQuery 和 CSS** 來創建互動式網頁。

**主要特色**：  
- 兩個箱子：左邊放 1 ~ 46 號的球，位置隨機排列  
- 多種按鈕控制球的移動  
- 重新整理按鈕，將所有球放回左邊並重新排列  

---

## 功能說明  
**隨機排列**：左邊的球會 **隨機排序**  
**抽取球並移動至右邊**：  
- **從左邊箱子最前面抽一顆，放到右邊箱子最後面**  
- **從左邊箱子最前面抽一顆，放到右邊箱子最前面**  
- **從左邊箱子最後面抽一顆，放到右邊箱子最後面**  
- **從左邊箱子最後面抽一顆，放到右邊箱子最前面**  
**重置功能**：所有球回到左邊，並重新隨機排序  

---

## 技術使用  
- **前端**：HTML、CSS、jQuery  
- **主要技術點**：  
  - `jQuery` 控制 DOM 操作  
  - `CSS` 美化球的樣式與動畫  
  - **陣列操作** 來模擬抽取與移動  
