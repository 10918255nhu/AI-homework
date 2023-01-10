# AI美術繪圖
透過簡單的文字描述，透過AI快速生產圖片。

# 使用說明
使用Colab開啟檔案會看到以下內容:
![image](https://user-images.githubusercontent.com/52593926/211605711-4b45bdb6-e132-4754-97d2-fdc6c1953ee8.png)
首先看到的部份可以用來設定想要的繪畫主題和圖片大小，

第一欄是主題的部分，可以自由設定，但必須使用英文;第二欄是圖片大小，免費版建議維持400不要更動。

第三行打勾的話會在輸出結束後自動下載圖片。


![image](https://user-images.githubusercontent.com/52593926/211608090-cf1f5a78-89b1-4e8d-bb76-6f63671f0c94.png)
再來是進階設定，第一欄的參數代表AI要模擬幾張圖片，數字越高，圖片會越接近目標。

不過這裡僅是模擬，並不會輸出內容。第二欄則是設定AI每模擬幾次就產出一張圖，以上是比較重要的部分。

第三行可以設定繪畫風格，第四行可以透過圖片URL，讓AI嘗試模擬圖片的畫風。第五行的參數越大，可以讓AI更快模擬，但結果更不穩定。

第六行則是種子碼，設定隨機數來得到不同的繪圖結果。

![image](https://user-images.githubusercontent.com/52593926/211615317-9916bfb6-67cd-4901-93db-4e936ac2c8a5.png)

結果設定完，執行下面三行程式碼設定底層資料和載入模組。

再執行底下Output區段，AI就會開始生成圖像。

# 小提示:
經過測試，類似下面的主題有不錯的準確率。
簡單的場景: "A cabin by the lake", "sunset over mountains"

非視覺的事物: "Dubstep", "Sad"

風格特別的媒體內容: "Homestar Runner"(著名卡通), "Factorio"(有著特殊美術風格的遊戲)

富含詩意的敘述: "old gods and older machines", "a doorway into a place without sunlight"
