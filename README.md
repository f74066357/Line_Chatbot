# Line bot -我們一起玩٩(๑❛ᴗ❛๑)۶
一個人很好玩 多人玩更有趣
聚會遊戲小幫手，選擇困難的救星。    

HackMD: https://hackmd.io/@3V7qO4jNTmapv5oZz4zgpg/BkkGR-pTS
* Base on line developer
* deploy webhooks on Heroku & AWS.

@670krxjr     
![image](https://github.com/f74066357/Line_Chatbot/blob/master/src/670krxjr.png)

## purpose
聚會上炒熱氣氛的經典小遊戲，無須下載即可在line上使用是最大的特點

## line API  
* REPLY_MESSAGE
* PUSH_MESSAGE

## Finitie State Machine
![image](https://github.com/f74066357/Line_Chatbot/blob/master/src/fsm.png)

## Introduce
A.  終極密碼猜猜看(game1)  
    最終密碼為[1~100]中，每次猜測會縮小範圍 猜中即遊戲結束  

B.  這首歌我知道!(game2)  
    播放一首歌，最快猜出歌名即為獲勝者 一直猜到正確解答出現  
    輸入"不猜了"遊戲結束 公布正解  

C.  添加game2中的歌曲庫  
    傳送歌曲名稱/撥放連結 幫助遊戲擴充歌曲庫,變得更多采多姿吧  
    
## usage  
- 不論在群組或個人遊戲 第一步都是輸入"menu"來獲得選單
![](https://github.com/f74066357/Line_Chatbot/blob/master/src/1.png)
- 點擊第一個按鈕進入game1 終極密碼猜猜看
![](https://github.com/f74066357/Line_Chatbot/blob/master/src/2.jpg)
一直猜到引爆炸彈
- 點擊第二個按鈕進入game2 這首歌我知道!
![](https://github.com/f74066357/Line_Chatbot/blob/master/src/3.png)
一直猜到正確為止 輸入不猜了可以跳出遊戲
- 點擊第三個按鈕增加歌單
![](https://github.com/f74066357/Line_Chatbot/blob/master/src/4.png)
- 不符合state狀態的錯誤輸入會回傳"不要亂~"
![](https://github.com/f74066357/Line_Chatbot/blob/master/src/5.png)

## Reference
* https://github.com/NCKU-CCS/TOC-Project-2020
