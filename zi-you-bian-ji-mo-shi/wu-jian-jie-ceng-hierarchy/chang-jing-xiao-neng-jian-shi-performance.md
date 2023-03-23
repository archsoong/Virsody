# 場景效能檢視 (Performance)

在建立場景的過程中，請切記隨時檢查當前效能 (Performance)，效能共有三種狀態：<mark style="color:green;">**Great**</mark>、<mark style="color:yellow;">**Medium**</mark>、<mark style="color:red;">**Bad**</mark>，如果效能不佳，可能會導致場景在電腦或手機上顯示會有卡頓或無法載入的情況。

\
而影響效能的因素有三大數值：每秒顯示幀數 (FPS)、物件數量 (Object count)、面數 (Faces)。其中 <mark style="color:blue;">**面數 (Faces)**</mark> 的影響最大，因此建議整個場景的物件面數要控制在  <mark style="color:blue;">**< 10萬面**</mark> 。



<mark style="color:green;">**狀態 1 - Great**</mark>：效能良好、流暢。

<figure><img src="../../.gitbook/assets/Frame 99.png" alt=""><figcaption></figcaption></figure>



<mark style="color:yellow;">**狀態 2 -**</mark> <mark style="color:yellow;">**Medium**</mark>：當增加的 3D 物件有點多時，效能就會開始往下掉。

<figure><img src="../../.gitbook/assets/Frame 100.png" alt=""><figcaption></figcaption></figure>



<mark style="color:red;">**狀態 3 -**</mark> <mark style="color:red;">**Bad**</mark>：當場景的 3D 物件數量已經過量時，效能便會直接掉到紅色的 Bad 狀態，建議此時需刪除多餘的物件，避免場景發生當機或卡頓的情況。

<figure><img src="../../.gitbook/assets/Frame 101.png" alt=""><figcaption></figcaption></figure>
