# Loading 
## Ver 1
![](screenshot/SmartSelect_20220528-214837_Opera.jpg)
<details>
<summary>HTML & CSS</summary>
HTML

```html
<center>
 <div class="loading" >
  <span id="loadingcycle" ></span> 
  <span>L</span> <span>o</span> <span>a</span>
  <span>d</span> <span>i</span> <span>n</span>
  <span>g</span> <span>.</span> <span>.</span>
  <span>.</span>
  </div>
</center>
```
CSS

```css
@keyframes spin{
 to{transform : rotate(360deg) ;}
}

.loading{
 --innercolor : lightgreen ;
 --mcolor : darkgray ;
}

#loadingcycle{
 width : 15px ;
 height : 15px ;
 border : solid 2px var(--mcolor) ;
 border-top : solid 2px var(--innercolor)  ;
 border-radius : 50% ;
 animation : spin 1s infinite linear ;
}

.loading>span{
 display : inline-block ;
 color : var(--mcolor)  ;
}

```
</details>





