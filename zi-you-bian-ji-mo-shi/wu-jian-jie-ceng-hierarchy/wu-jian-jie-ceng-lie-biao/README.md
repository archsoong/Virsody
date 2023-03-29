# 物件階層列表

物件階層列表中的 3D 物件主要分為兩種：

<mark style="color:blue;">**1.空物件 (Node)**</mark>\
這是用來包含不同 3D 物件的「容器」，本身在場景中是沒有實體型態的。空物件 (Node) 目前無法自行製造，只能在素材庫中的 3D 物件中找到。你可以把其他 3D 物件放入空物件中，並將它們群組在一起。

<mark style="color:blue;">**2.實體物件 (Mesh)**</mark>\ <mark style="color:blue;">****</mark>實體的 3D 物件。

<figure><img src="../../../.gitbook/assets/Frame 93 (2).png" alt=""><figcaption></figcaption></figure>

物件階層列表中的父子層級關係（Parent-child）：

<mark style="color:blue;">**1.子層級屬性會跟隨其父層級**</mark>\ <mark style="color:blue;">****</mark>\ <mark style="color:blue;">****</mark>選擇最上面層級的空物件 (Node) 並進行狀態改變 (e.g. 縮放、移動、隱藏)，會一起影響到下層的實體物件 (Mesh)。\
點擊左側三角形可收合或展開父子層級。

<figure><img src="../../../.gitbook/assets/node上層影響下層.gif" alt=""><figcaption></figcaption></figure>



<mark style="color:blue;">**2.拖曳物件形成父子層級**</mark>

無論是空物件 (Node) 還是實體物件 (Mesh) 都可以在階層列表中自由拖移，調整階層或順序。\
注意1：只有空物件 (Node)可以形成父子層級，實體物件 (Mesh)之間無法形成父子層級。\
注意2：需點擊收合箭頭，使父子層級展開，才能將物件拖曳至該物件的子層級。

<figure><img src="../../../.gitbook/assets/自由拖移.gif" alt=""><figcaption></figcaption></figure>

物件控制：

<mark style="color:blue;">**1.重新命名**</mark>\ <mark style="color:blue;">****</mark>在列表點擊兩下，可重新命名空物件 (Node) 或實體物件 (Mesh)，也可以在右側的物件屬性中重新命名。

<figure><img src="../../../.gitbook/assets/Frame 95.png" alt=""><figcaption></figcaption></figure>

<mark style="color:blue;">**2.隱藏與上鎖**</mark>

將滑鼠懸停在列表上，物件名稱旁邊就會出現「隱藏」跟「上鎖」的按鈕，點擊後即可針對該物件進行隱藏或上鎖。

<figure><img src="../../../.gitbook/assets/Frame 96.png" alt=""><figcaption></figcaption></figure>

&#x20;















