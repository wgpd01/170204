# 程式設計 / 演算法

為什麼學習程式設計? 解決問題、創造價值。<br>
Eight: Business Cards<br>
https://www.youtube.com/watch?v=gpM_rnQBCr0


要解決問題，就觸及方法與步驟<br>
人腦也可以執行演算法 - David J. Malan (有中文字幕)<br>
https://www.youtube.com/watch?v=6hfOvs8pY1k


觀看影片的前兩分鐘，暫停，我們來討論一下演算法: (有中文字幕)<br>
Can you solve the bridge riddle? - Alex Gendler<br>
https://www.youtube.com/watch?v=7yDmGnA8Hw0  <br>
解答:<br>
https://www.youtube.com/watch?v=7yDmGnA8Hw0&t=120


前端工程師要學程式設計嗎? 讓我們來看看這些網站:

- https://qiao.github.io/PathFinding.js/visual/

- https://d3js.org/
  例如: https://bl.ocks.org/mbostock/4061961

- 本文稍後有【參考資料】，那邊還有兩篇，供各位課後參考閱讀。 :-)


--------------------------------------------------------------------------------

Lab_JavaScript 之 140:

為何 JavaSript 的 0.1 + 0.2 不等於 0.3 ? @@"

我們來看看人類如何數數，以及電腦如何數數，它如何使用二進位儲存與處理資料:<br>
How high can you count on your fingers?<br>
https://youtu.be/UixU1oRW64Q


--------------------------------------------------------------------------------

Lab_JavaScript 之 230:

- 學會迴圈之後，如何用程式計算 1 + 2 + 3 + ... + 100?

- 想想之前的演算法，試著用中文描述運算過程

- 其中有數學模型可用嗎? (提示於本文件結尾處)




--------------------------------------------------------------------------------

#【課後閱讀】下週我們會進行課堂討論，請先抽空觀看影片:

最速排序法: (自動翻譯字幕)<br>
What's the fastest way to alphabetize your bookshelf? - Chand John<br>
https://www.youtube.com/watch?v=WaNLJf8xzC4


Sorting Algorithms Dance<br>
https://www.youtube.com/playlist?list=PLuE79vNc5Wi6q34LsQcaJ7ISQ8uOyMaL_


Can you solve the airplane riddle? (自動翻譯字幕)<br>
https://www.youtube.com/watch?v=dzrwnwOx0fw



--------------------------------------------------------------------------------

#【參考資料】

前端工程興起後的程式設計分工<br>
http://www.ithome.com.tw/node/83410

asp.net Web開發框架 (2) - 基本SPA架構<br>
http://studyhost.blogspot.tw/2016/12/aspnet-web-2-spa.html


演算法 Algorithms<br>
授課教師: 江蕙如老師<br>
http://ocw.nctu.edu.tw/course_detail.php?bgid=8&gid=0&nid=493#.V-K8ZSh96hd

演算法筆記: (國立臺灣師範大學資訊工程學系)<br>
http://www.csie.ntnu.edu.tw/~u91029/Algorithm.html

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

# Sum 1 to 100

001 + 002 + 003 + ... + 098 + 099 + 100<br>
==> 5050


001 + 002 + 003 + ... + 098 + 099 + 100<br>
100 + 099 + 097 + ... + 003 + 002 + 001<br>
==> ( 1 + 100 ) * 100 / 2 = 5050


50  49  48 ...  3   2   1<br>
51  52  53 ... 98  99  100<br>
==> 101 * 50 = 5050

