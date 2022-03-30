# Pseudo Element
偽類 (pseudo class) 就是在選已經存在的東西，比方說 a:hover 就是選了已經存在的 <a> 的某一個狀態
 
偽元素 (pseudo element) 就是在創造一個新的假元素，因為他不在 DOM 裡面，而是創造的了一個我們看不見的元素。
  比如說 ::first-line，第一行並沒有被任何的 tag 包住，所以在選取的過程就像是用了一個看不到的 tag 把第一行包起來，所以才選得到這行。

# :hover :link :active : visited

# The CSS Box Model
Margin - transparent
 
Border - goes around the padding and content
 
Padding - transparent

 
# Box-sizing
在 CSS box model 中，對元素指定寬度和高度會應用於 content box，如果又在該元素設定 border 或 padding 時，在視覺上會很像是增加元素的大小。
 也就是說當你想要讓該元素為某寬度或高度時，需要自行手動減去 border 或 padding 所佔用的空間，才能讓元素符合原本預期的寬高。

 # Color (Hex Code)
 Hex code
 
 rgb: rgb(255,255,255), rgb(255,0,0)

 Color name: red, pink
 
 hsla(hue, saturation, lightness, alpha)
 
 #p1 {background-color: hsl(120, 100%, 50%);}   
 
# RGBA/RGA Colors
 
