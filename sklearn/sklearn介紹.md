# Sklearn 介紹

scikit-learn 官方網站的介紹，網站將模型和工具分為以下幾個主要類別：
https://scikit-learn.org/stable/

### 1. 分類 (Classification)
* **用途：** 識別一個物件屬於哪一個離散的類別。
* **例子：** 垃圾郵件偵測（是/否）、手寫數字識別（0-9）、圖像中的物體辨識（貓/狗/車）。
* **常見演算法：** 羅吉斯迴歸 (Logistic Regression)、支援向量機 (SVM)、隨機森林 (Random Forest)、梯度提升 (Gradient Boosting)、K-近鄰 (K-Nearest Neighbors)。

### 2. 迴歸 (Regression)
* **用途：** 預測與物件相關聯的連續數值。
* **例子：** 預測房價、預測股票價格、預測天氣的降雨量。
* **常見演算法：** 線性迴歸 (Linear Regression)、嶺迴歸 (Ridge)、Lasso、梯度提升 (Gradient Boosting)、隨機森林 (Random Forest)。

### 3. 聚類 (Clustering)
* **用途：** 將相似的數據點自動分組，這是一種非監督式學習。
* **例子：** 根據消費行為將客戶分群、將新聞文章按主題分組、自動將相似的圖片分組。
* **常見演算法：** K-均值分群 (K-Means)、HDBSCAN、階層式聚類 (Hierarchical Clustering)。

### 4. 降維 (Dimensionality reduction)
* **用途：** 減少資料中需要考慮的隨機變數或特徵的數量，同時盡可能保留重要資訊。
* **例子：** 將高維度的數據視覺化，或簡化模型以提高運算效率。
* **常見演算法：** 主成分分析 (PCA)、非負矩陣分解 (NMF)。

### 5. 模型選擇與評估 (Model selection and Evaluation)
* **用途：** 這些工具用於比較、驗證和選擇最適合的參數與模型。
* **例子：** 使用交叉驗證 (Cross-Validation) 來評估模型的穩定性、使用網格搜索 (Grid Search) 來自動尋找最佳參數組合。

### 6. 資料預處理 (Preprocessing)
* **用途：** 這是機器學習流程中非常關鍵的一步，用來將原始資料轉換為機器學習演算法可以使用的格式。
* **例子：** 將文字資料轉化為數值、將資料進行標準化 (Standardization) 或正規化 (Normalization)。