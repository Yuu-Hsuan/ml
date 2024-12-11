# ml

## 創一個資料夾 : 讓程式碼在此資料夾的環境中進行
1. 在桌面建一個資料夾
2. 將它拖移到 vs code 中
3. 在終端機中輸入以下指令來建立虛擬環境 : 這將在專案目錄中建立一個名為 venv 的子資料夾，包含獨立的 Python 環境
   ```
   python -m venv venv
   ```
4. 建立虛擬環境後，需要啟用它 :
   ```
   .\venv\Scripts\activate
   ```
6. 新增資料夾，取名為`main.py`
7. 進入`main.py`，右下角選「選取解譯器」
8. 選擇「建立虛擬環境」
9. 選擇「venv」
10. 選擇已安裝的 Python 版本

## 安裝所需 PIP 套件

1. 從 VS Code 介面下方往上拖曳，開啟終端機

   或按 (`Ctrl` + ```)
   
2. 輸入 PIP 指令安裝所需的套件，套件將獨立安裝於 `.venv` 資料夾中，不會和作業系統中的 Python 發生衝突
   ```
   pip install numpy matplotlib joblib tensorflow scikit-learn tqdm
   ```

## 執行程式碼

1. 確保 `svm_mnist.py` 位於專案目錄內
2. 在 VS Code 中打開 `svm_mnist.py`
3. 按下 `Ctrl` + `Alt` + `N` 或 右鍵程式碼區域，選擇 Run Python File in Terminal
4. VS code 終端機將執行程式，並顯示輸出結果

