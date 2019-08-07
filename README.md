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
