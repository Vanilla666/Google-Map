<h1>先創html</h1>
把經緯度的文字加入 <br/>
給個div把Button放在一起 <br/>
再來把GoogleMap放在另一個div <br/>

<h1>開始RWD排版</h1>
設置手機、平板、電腦的格式<br/>
googleMap排版調整

<h1>Js創建</h1>
<h3>Geolocation API</h3>
首先是否支援 Geolocation API，如果不支援就無法進行<br/>
Geolocation API 去調用經緯度，在調用時會有個物件當參數，請利用物件參數讀取經緯度，讀取到經緯度後把它寫回html裡<br/>
最後把經緯度當參數傳入GoogleMap的函數<br/>
<h3>GoogleMap</h3>
首先要去Google API 找到 Maps JavaScript API 之後申請金鑰才能開始GoogleMap<br/>
程式碼第147行創建GoogleMap第一個參數是指要畫在哪個div,第二個參數是會有2個必要設定的參數形式是key:value<br/>
zoom:17  縮放區域  數字越大縮放越大 0~21 (必要參數)   center:new google.maps.LatLng(x,y),  經緯度 (必要參數)<br/>
當然還可以調用其他key:value 但是先不做介紹 </br>
做好以上調整後即可畫出GoogleMap</br>
<h4>紅色箭頭的樣式</h4>
