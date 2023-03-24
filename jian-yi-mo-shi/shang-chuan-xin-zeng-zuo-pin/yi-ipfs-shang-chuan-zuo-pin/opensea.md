---
description: 如何在 OpenSea 上用 IPFS 上傳作品
---

# 2 OpenSea

將作品上傳至 [OpenSea](https://opensea.io/) 後，點擊作品頁面下方的<mark style="color:blue;">「Details」</mark>。

![](<../../../.gitbook/assets/截圖 2022-06-07 下午3.22.16.png>)



並在<mark style="color:blue;">「Token ID」</mark>的地方，點擊後方藍色的 <mark style="color:blue;">ID號碼</mark> （如圖中的 439），就會開啟作品的 JSON 資料頁。

![](<../../../.gitbook/assets/截圖 2022-06-07 下午3.27.40.png>)



作品的 JSON 資料頁打開後，找到 <mark style="color:red;">”image”</mark> 開頭那行，接著可能會遇到兩種狀況：

(1) 若後方為完整的<mark style="color:blue;">「網址」</mark>形式，直接複製貼至 Virsody 後台的 IPFS 連結輸入框內即可。

![](<../../../.gitbook/assets/截圖 2022-06-13 上午1.33.31.png>)

(2) 若並非網址形式，則請將 <mark style="color:blue;">ipfs://</mark>  後方的字串複製下來，並在字串前加上網址前綴 [<mark style="color:red;">https://ipfs.io/ipfs/</mark>](https://ipfs.io/ipfs/) <mark style="color:red;"></mark> ，再貼至 Virsody 後臺的 IPFS 連結輸入框內。

![](<../../../.gitbook/assets/截圖 2022-06-10 下午6.16.36.png>)



回到 Virsody 後，將複製的字串貼至 IPFS 連結輸入框中 ( ⚠️若字串沒有網址前綴，請記得在前面加上 [<mark style="color:red;">https://ipfs.io/ipfs/</mark>](https://ipfs.io/ipfs/) <mark style="color:red;"></mark> )，並點選<mark style="color:blue;">「檢查連線」</mark>按鈕。

![](<../../../.gitbook/assets/截圖 2022-06-07 下午3.46.16.png>)



系統便會自動判定 IPFS 作品的檔案類型、呈現預覽圖。確認後便可按「下一步」，繼續完成步驟並上傳。

![](<../../../.gitbook/assets/截圖 2022-06-07 下午4.04.57.png>)
