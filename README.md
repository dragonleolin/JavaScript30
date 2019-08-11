 JavaScript30

實做需要注意的地方

01. JS Drum Kit

首先要先知道按下鍵時，會做兩個動作，ㄧ個是播放音樂、ㄧ個是畫面渲染。

document.querySelector(\`audio[data-key="${e.keyCode}"]\`) 

kbd是預設標籤，是行內元素，用於表示用戶輸入

要注意點擊之後要把樣式移除掉。

找到音樂檔要確定有音樂才能播 


02. Clock


可以先調整樣式，確定初始位置

取得時間的方法，隻到每秒每分每時走的角度計算

.style.transform = `rotate(0deg)`

連續執行，可以使用setTimeout、setInvertal


03.CSS Variables

關於style內容

:root是html選取器; 變數的選取方式是-- ; 在使用時需要加var; 在用變數去記錄資料-->修改畫面; 


04-Array-Cardio

可以用console.table(inventors); 印出表格式的陣列

forEach沒有回傳值，若只有要針對每個項目做事的話，forEach比較好，但難控制順序的問題。

這一章主要是討論陣列的功能

filter: 複製一個新的陣列出來，保留想要保留的部分或刪除想刪除的

map會產生一個新陣列，在對於每個項目做事之後。

sort: 主要做排序

reduce: 整和，回傳ㄧ個值

06-Type-Ahead

著重API的讀取，和陣列的

.join: 把東西合在一起變字串


