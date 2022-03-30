
pseudo-element v.s. pseudo-class
================================================
偽類 (pseudo class) 就是在選已經存在的東西，比方說 a:hover 就是選了已經存在的 <a> 的某一個狀態。
 
偽元素 (pseudo element) 就是在創造一個新的假元素，因為他不在 DOM 裡面，而是創造的了一個我們看不見的元素。
比如說 ::first-line，第一行並沒有被任何的 tag 包住，所以在選取的過程就像是用了一個看不到的 tag 把第一行包起來，所以才選得到這行。

偽類 pseudo-class 使用單冒號來起始撰寫
Pseudo-classes are keywords that start with a colon:

偽元素 pseudo-element使用雙冒號起始撰寫
Pseudo-elements start with a double colon ::


 
pseudo-class
================================================
:link 連結未被訪問過
 
:visited 連結已被訪問過
 
:focus 元素被聚焦
 
:hover 滑鼠游標移到元素上
 
:active 滑鼠點擊到放開前

 
 
The CSS Box Model
================================================
Box Model 主要由四個部分主成，由內而外分別是 Content ( 內容 )、Padding ( 內邊距 )、Border ( 邊框 ) 和 Margin ( 外邊距 )


 
Box-sizing
================================================
在CSS box model中，對元素指定寬度和高度會應用於content box，如果又在該元素設定border或padding時，在視覺上會很像是增加元素的大小。
也就是說當你想要讓該元素為某寬度或高度時，需要自行手動減去border或padding所佔用的空間，才能讓元素符合原本預期的寬高。


 # Color (Hex Code)
 Hex code
 
 rgb: rgb(255,255,255), rgb(255,0,0)

 Color name: red, pink
 
 hsla(hue, saturation, lightness, alpha)
 
 #p1 {background-color: hsl(120, 100%, 50%);}   
 
# RGBA/RGA Colors
 
rgb(red, green, blue)
#p1 {background-color:rgb(255,0,0);}
#p2 {background-color:rgb(0,255,0);}
#p3 {background-color:rgb(0,0,255);}
rgba(red, green, blue, alpha)
#p1 {background-color: rgba(255, 0, 0, 0.3);}   /* red with
opacity */
 
#CSS3 Gradients
 
 
關於height的百分比
================================================
height:100%
如果在一個div設置一張背景圖，並設置width:100% ;hight:100% ，
會發現div的高度根本稱不開。這時需在html，body上設hight:100%，
因為height的百分比值需要父級有一個可以生效的高度值才起作用。

height:100vh
vh(view height)指瀏覽器內部的可視區域高度的百分比，window.innerWidth/window.innerHeight
上述例子問題也可以使用vh單位解決，不用在html，body上設hight:100%
但是vh單位在IE8以下版本不支援。
 
 
 #style
 <style>
        body{
            background: linear-gradient(yellow,blue) ;
            width: 100%;
            height: 100vh;
        }
 </style>
