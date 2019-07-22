# guthub-colorer
### guthub pull requests colorer bookmarklet

- Create  bookmark https://github.com in any browser
- Set name [Pull Requests Colorer]
- Modify url  
![](https://raw.githubusercontent.com/lev-savranskiy/guthub-colorer/master/gihub-colorer.PNG)
```javascript:ghels=document.getElementsByClassName("tooltipped");for(let e in ghels){let t=ghels[e],n=t.innerText&&t.innerText.trim(),r={"Review required":"orange",Approved:"green","Changes requested":"red"};r[n]&&t.setAttribute("style",`background-color:${r[n]};color:#fff!important;padding:1px 5px;`)}```
- Go to pull requests page
- Click on bookmark created before
- Pull requests are autotagged
- see video at https://raw.githubusercontent.com/lev-savranskiy/guthub-colorer/master/guthub-colorer.webm







