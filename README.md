#邏設(project)
作者  110321025 110321071

LED顯示輸、贏、平手

![邏設1](https://user-images.githubusercontent.com/122535127/212076436-a7a7d4d0-4c11-457b-a2e4-0fd88d8beca7.png)

s1、s2、s3、s4 決定出 剪刀、石頭、布、開始

![image](https://user-images.githubusercontent.com/122535127/212078333-56aa38f4-04b0-4334-8eb5-c365809fd57a.png)

8x8全彩點矩陣，顯示輸(紅) 贏(綠) 平手(藍) 亮燈

![image](https://user-images.githubusercontent.com/122535127/212085553-0cfaa227-a282-485b-ae3f-fa569581534e.png)

功能說明：玩家透過按鍵與FPGA做猜拳，顯示結果在上方LED與8*8LED矩陣亮燈

輸入 輸出設置

![image](https://user-images.githubusercontent.com/122535127/212103923-857512ec-f253-4a0b-b07f-ea8b7c7195c8.png)


random

![image](https://user-images.githubusercontent.com/122535127/212089891-ae9e18a6-2983-4b32-8786-b79c4b331a79.png)

設定平手 輸 贏 剪刀 石頭 布 代表的值

![image](https://user-images.githubusercontent.com/122535127/212092196-dc7a45f2-819d-4be0-be16-082a2a39c67e.png)

玩家輸入所代表的是剪刀、石頭 或 布

![image](https://user-images.githubusercontent.com/122535127/212095257-155f61a0-89c1-49f2-ad1a-56e045d59056.png)

和fpga_choice做猜拳 並印出結果


![image](https://user-images.githubusercontent.com/122535127/212095667-bc2160d7-d17a-4657-bdf6-10c6dc0b6049.png)

設定 各結果代表的亮燈

S0=藍燈 , S1=紅燈 , S2=綠燈 , S3=不亮燈

![image](https://user-images.githubusercontent.com/122535127/212095897-cede17cc-6d34-4d91-9e36-5e8c09979e71.png)
