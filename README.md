# Pen Int Style - Multiple 67s

一個基於 HTML5 Canvas 的互動式網頁專案。當使用者在畫布上隨意塗鴉時，其筆劃會透過路徑重採樣與插值技術，動態變形成一個優雅、發光的「67」字樣。

An interactive web project based on HTML5 Canvas. When users doodle on the canvas, their strokes dynamically morph into an elegant, glowing "67" through path resampling and interpolation techniques.

---

## 🚀 功能特點 | Features

* **動態變形 (Dynamic Morphing)：** 任何手繪線條都會平滑地轉換為預設的幾何形狀。
* **響應式設計 (Responsive Design)：** 自動適應各種螢幕尺寸，並支援滑鼠與觸控操作。
* **發光視覺效果 (Glowing Visuals)：** 變形完成後，圖形會呈現出霓虹般的白色發光質感。
* **多重繪製 (Multiple Instances)：** 可以在畫布上同時存在多個變形完成的「67」。

---

## 🛠️ 技術細節 | Technical Breakdown

該專案主要使用了以下技術邏輯：

1.  **標準化幾何 (Normalized Geometry):** 使用三次貝茲曲線 (Cubic Bezier Curves) 在 1x1 的單位方塊中定義「6"」與「7」的筆畫軌跡。
2.  **路徑重採樣 (Path Resampling):** 為了讓變形動畫順暢，系統會計算使用者畫出的原始路徑長度，並重新採樣點位，使其與目標「67」的點數完全一致。
3.  **線性插值動畫 (Morphing Animation):** 利用 Ease-out 動畫曲線進行點對點的座標插值，在 700 毫秒內完成從塗鴉到數字的轉換。

---

## 📂 使用方式 | How to Use

1.  **下載檔案 (Download):** 下載本倉庫中的 `67.html`。
2.  **執行 (Run):** 直接在瀏覽器中開啟 `67.html` 即可執行。
3.  **互動 (Interaction):**
    * 在畫布上點擊並拖曳以進行繪圖。
    * 放開滑鼠或手指後，線條會自動開始變形。

---

## 📝 授權條款 | License

本專案採用 **MIT License**。

md my google gemimi
