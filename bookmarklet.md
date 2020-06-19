## Copy issue title

```
javascript:(() => {var r = document.querySelector("[data-pjax='#js-repo-pjax-container']").textContent.trim();%20var%20t%20=%20document.querySelector(".js-issue-title").textContent.trim();%20var%20n%20=%20document.querySelector(".gh-header-number").textContent.trim();%20prompt("",%20`${r}${n}%20${t}`);})()
```

## Copy issue title & URL

```
javascript:(() => {var r = document.querySelector("[data-pjax='#js-repo-pjax-container']").textContent.trim();%20var%20t%20=%20document.querySelector(".js-issue-title").textContent.trim();%20var%20n%20=%20document.querySelector(".gh-header-number").textContent.trim();%20prompt("",%20`${r}${n}%20${t}%20-%20${location.href}`);})()
```

## GitHub Markdown/Wiki TOC

https://qiita.com/hokkun_dayo/items/bd3ec64fba293f4aca08

こっちのほうがすき  
https://github.com/yama-t/code/tree/master/bookmarklet/github-wiki-toc
