大金冷氣系統
=
#####windoiws10 sql server 2008R2 安裝設定
#####資料庫還原
#####組態設定
#####執行程式

##windoiws10 sql server 2008R2 安裝設定

[https://www.youtube.com/watch?v=DUCbvfFEO34](https://www.youtube.com/watch?v=DUCbvfFEO34)

##資料庫還原

在sql server studio中還原備份檔 
![](https://github.com/t2831245/-/blob/master/picture/1.png?raw=true)  

選擇還原用的**[.bak]**檔
![](https://github.com/t2831245/-/blob/master/picture/2.png?raw=true)  

在**[選項]**的部分將**[複寫現有的資料庫]**打勾
![](https://github.com/t2831245/-/blob/master/picture/3.png?raw=true)  

##資料庫還原
開啟組態管理員  
![](https://github.com/t2831245/-/blob/master/picture/4.png?raw=true)  
將**[SQL Server Browser]**調成手動後啟動
![](https://github.com/t2831245/-/blob/master/picture/5.png?raw=true)  
![](https://github.com/t2831245/-/blob/master/picture/6.png?raw=true)  
選擇**[SQLEXPRESS]**->**[TCP/IP]**並將**[IPALL]**->**[TCP通訊阜]**改成**[1433]**
![](https://github.com/t2831245/-/blob/master/picture/7.png?raw=true)
重新啟動 **[SQL Serve]**
![](https://github.com/t2831245/-/blob/master/picture/8-1.png?raw=true)

##執行程式
使用**[]Run As]**->**[Java Application]**執行程式
![](https://github.com/t2831245/-/blob/master/picture/11.png?raw=true)
![](https://github.com/t2831245/-/blob/master/picture/12.png?raw=true)
