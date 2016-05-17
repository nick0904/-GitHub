
##藉由終端機上傳資料夾到GitHub
####本文以上傳桌面的資料夾(上傳檔案到Github)到GitHub為例
![GitHub](https://github.com/nick0904/-GitHub/blob/master/desk.png)
-------------------------------------------------------------------
####首先打開終端機(Terminal Tool)
#####輸入 cd desktop
#####輸入 ls
![GitHub](https://github.com/nick0904/-GitHub/blob/master/g01.png)
-------------------------------------------------------------------
####確認資料夾位置後
#####輸入 git init
#####輸入 ls -A (可以發現資料夾多一個 .git)
![GitHub](https://github.com/nick0904/-GitHub/blob/master/g02.png)
-------------------------------------------------------------------
####有了.git 我們就可以將資料夾上傳到GitHub
#####輸入git add -A
#####輸入git commit -m "自定義描述文字"
![GitHub](https://github.com/nick0904/-GitHub/blob/master/g03.png)
-------------------------------------------------------------------
####遠端傳送
#####輸入 git remote add origin http://...
#####輸入 git push -u origin master
![GitHub](https://github.com/nick0904/-GitHub/blob/master/g04.png)
-------------------------------------------------------------------
####檢視GitHub
#####上傳成功
![GitHub](https://github.com/nick0904/-GitHub/blob/master/g05.png)
-------------------------------------------------------------------
####更新資料夾到GitHUb
#####step01: 終端機找到資料夾
#####step02: git add -A
#####step03: git commit -m "更改描述"
#####step04: git push -u origin master
-------------------------------------------------------------------
#### 下載其他人的GitHub
##### 先由終端機找到欲存放他人GitHub的資料夾
##### git init (初始化),如果檔案以初始化則可省略此步驟
##### git clone http://...(欲下載的目標GitHub檔案)
##### 最後會出現類似下面兩行文字,表示下載成功囉
##### Unpacking objects: 100% (44/44), done.
##### Checking connectivity... done.


