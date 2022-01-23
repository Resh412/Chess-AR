**110行動裝置遊戲設計實務 - 期末專案**

**一、專題名稱： Chess AR\
二、專題功能簡述**

讓使用者透過AR
App方便且快速、隨時隨地的遊玩西洋棋，同時亦可享有沉浸式的體驗。使用者僅需在空曠場合或任一平面上使用手機上的APP即可投影出立體西洋棋進行對戰。

**三、開發環境需求**

  **環境版本**   **Unity 2020.3.25f1 (LTS)**
  -------------- -------------------------------------------------------
  **插件版本**   **ARCore SDK v1.25.0, Photon Unity Networking v2.40**

**四、西洋棋設計理念**

配合遊玩AR上的使用，且考慮到使用者周遭之情境，設計上將以簡約爲主，並以突出特點及容易辨識的朝向前進。

**五、設計圖**

![](media/image1.jpeg){width="5.768055555555556in"
height="4.104166666666667in"}

![](media/image2.jpeg){width="5.768055555555556in" height="4.075in"}

![](media/image3.png){width="5.768055555555556in"
height="4.065277777777778in"}

**六、3D製作**

使用軟體：Blender, 3ds Max

![](media/image4.jpeg){width="5.768055555555556in"
height="3.247916666666667in"}

![](media/image5.jpeg){width="5.768055555555556in"
height="3.247916666666667in"}

**七、UI設計**

![](media/image6.jpeg){width="1.3423611111111111in"
height="2.9090277777777778in"}![](media/image7.jpeg){width="1.3423611111111111in"
height="2.9145833333333333in"}![](media/image8.jpeg){width="1.3423611111111111in"
height="2.9090277777777778in"}![](media/image9.png){width="1.3208333333333333in"
height="2.8715277777777777in"}

**八、組員分工**

  **學號**    **姓名**   **負責工作**
  ----------- ---------- ------------------
  108AC1006   鄭高峰     程式撰寫
  108AC1009   陳語哲     程式編輯
  108840009   劉潔昕     平面設計
  108AC1037   黃靖娉     3D製作 & UI 界面

**九、操作說明**

![](media/image10.png){width="2.3097222222222222in"
height="2.3041666666666667in"}請注意:
在體驗正式開始之前，請確保您的裝置支援且已安裝最新版本的[*ARCore*](https://developers.google.com/ar/devices)，否則體驗過程中將會發生可預期之錯誤並造成遊戲自動關閉。

在進入初始畫面後，點擊螢幕的任意位置後遊戲便會嘗試將您連上伺服器(連線速度與穩定性因裝置、電信商與地區而異)，而後將進入大廳介面。請根據需求進行以下操作↓

發起人：建立一個新的遊戲房間，於上方欄位中輸入想要的房號後點擊Create

加入者：加入一既有的遊戲房間，於下方欄位中輸入該房的房號後點擊Join![](media/image11.jpeg){width="1.9145833333333333in"
height="3.40625in"}![](media/image12.jpeg){width="1.9145833333333333in"
height="3.40625in"}![](media/image13.jpeg){width="1.9145833333333333in"
height="3.417361111111111in"}

![](media/image14.jpeg){width="1.7623534558180227in"
height="3.1667388451443568in"}![](media/image15.jpeg){width="1.7636318897637795in"
height="3.1808016185476817in"}![](media/image16.jpeg){width="1.7585181539807524in"
height="3.1616251093613297in"}初次執行時請同意使用相機的權限，將裝置至於環境明亮處移動尋找水平面。若出現網格狀面則偵測成功，點擊以放置棋盤。點擊棋盤上的棋子將會出現其於當前回合中可移動的範圍。

![](media/image17.jpeg){width="1.86875in"
height="1.1597222222222223in"}![](media/image18.jpeg){width="1.6in"
height="1.16875in"}在一方移動過棋子後，便會輪到對方回合，場景中的文字同時也會提醒雙方當前為哪方的回合。在只有一部裝置連入的情況下(單人、本地雙人)亦可正常遊玩。

按下返回鍵可回到大廳，仍有人在房間中時棋局將被保留。最終勝利條件有二↓

1\. 將死對手的國王

2\. 對手按下投降鍵

![](media/image19.jpeg){width="1.5291666666666666in"
height="3.0340277777777778in"}![](media/image20.jpeg){width="1.625in"
height="2.998611111111111in"}![](media/image21.jpeg){width="1.5291666666666666in"
height="3.079861111111111in"}勝利後將跳轉至結算畫面，畫面則會因勝方而有所不同。