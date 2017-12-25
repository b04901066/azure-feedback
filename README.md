# Azure 使用心得 azure-feedback    
[Azure]: https://portal.azure.com/
## [Azure][]     

* 各種課程上的應用     

第一次接觸Azure是修蘇國棟教授的計算機概論，因為final是要做簡單的嬰兒表情辨識，但是那時候我還不會機器學習，因此便直接使用Azure提供的表情辨識服務，    結果便輕鬆全對XDD 之後自己修改範例程式後掛到自己的部落格上當教學。    
http://hungguo.blogspot.tw/2016/06/mapi.html?view=sidebar     
> -----------------------------------------------     

我去年修黃鍾揚教授開的科技創新設計專題，專題題目要做爬牆偵測，並且需要在極短的時間內就有個可以demo的版本，所以教授就介紹我和組員使用azure的雲端服務，
主要是使用[computer-vision](https://azure.microsoft.com/zh-tw/services/cognitive-services/computer-vision/ "computer-vision") API 電腦視覺。因為是教授推廣配額，所以不需要花到一毛錢，不過其實這個服務的免費版本就很夠用了。     
> -----------------------------------------------      

而這學期是修李弘毅教授開的MLDS，主要使用的是ubuntu虛擬機，因為機器學習需要運算能力強大的GPU。azure提供配備次伺服器專用的 [nVIDIA Tesla-K80](http://www.nvidia.com.tw/object/tesla-servers-tw.html)，讓我可以順利完成hw1和hw2，同樣不需要花到一毛錢(課程贊助)，不過若是實際自費還是挺貴的(對個人而言)。    

* 使用

現在微軟已經將全部的服務都整合到[Azure][]，因此要使用只要先註冊帳戶，再依照需求新建資源即可，基本上都是隨便按幾個按鈕就可以架設好資源，要用的時候可能只需要一個金鑰或密碼即可，code部分主要是用json包訊息，只要隨便搜索一下便，可找到協助快速上手的範例程式，並且支援多種語言。    

* 介面    

![Alt text](/path/to/img.jpg)

