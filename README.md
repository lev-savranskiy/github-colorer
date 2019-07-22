# guthub-colorer
### guthub colorer bookmarklet

- create  bookmark https://github.com in any browser
- set name [Pull Requests Colorer]
- modify url  
```javascript:ghels=document.getElementsByClassName("tooltipped");for(let e in ghels){let t=ghels[e],n=t.innerText&&t.innerText.trim(),r={"Review required":"orange",Approved:"green","Changes requested":"red"};r[n]&&t.setAttribute("style",`background-color:${r[n]};color:#fff!important;padding:1px 5px;`)}```




