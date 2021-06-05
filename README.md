# 如何使用

将下面的脚本作为一个书签保存起来，进入评测页后，一直点击就可以了

```html
javascript:var frame = window['zhuti']; var select =
frame.document.querySelectorAll('select'); var aaa = select[0].options; for(let
j = 0;j < select.length;j++){ if(j!==0){ var items = select[j].options;
items[[1,2,3][~~(Math.random()*100)%3]].selected=true; } }
frame.document.querySelector('#Button1').click();
```

# 脚本仅供学习
