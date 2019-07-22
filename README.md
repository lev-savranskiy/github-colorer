# guthub-colorer
### guthub pull requests colorer bookmarklet

- Create  bookmark https://github.com in any browser
- Set name [Pull Requests Colorer]
- Modify url  
![](https://raw.githubusercontent.com/lev-savranskiy/guthub-colorer/master/github-colorer.PNG)
```javascript:ghels=document.getElementsByClassName("tooltipped");for(let e in ghels){let t=ghels[e],n=t.innerText&&t.innerText.trim(),r={"Review required":"orange",Approved:"green","Changes requested":"red"};r[n]&&t.setAttribute("style",`background-color:${r[n]};color:#fff!important;padding:1px 5px;`)}```
- Go to pull requests page
- Click on bookmark created before
- Pull requests are autotagged
![](https://raw.githubusercontent.com/lev-savranskiy/guthub-colorer/master/github-colorer2.PNG)
- see video at https://webm.red/8LMm.webm







