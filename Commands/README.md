# Commands

---

## $env:path
|n|name|desc.|eg|O/P|
|-|----|-----|--|---|
|1|||`$env:path -split ';' \| select-string "pyt"`<br/><br/>`# add new entries`<br/>`[Environment]::SetEnvironmentVariable( `<br/>`"Path", $env:Path + ";`<br/>`C:\Users\paul\AppData\Local\Programs\Python\Python313\Scripts\;`<br/>`C:\Users\paul\AppData\Local\Programs\Python\Python313\;`<br/>`C:\Users\paul\AppData\Local\Programs\Python\Launcher\", "User" )`|<img src="https://i.imgur.com/ga4OQbg.png"><br/><img src="https://i.imgur.com/TNK8w9X.png">|
|2|

---

## List
|n|name|desc.|eg|O/P|
|-|----|-----|--|---|
|1|exit()|exit of python interpreter||<img src="https://i.imgur.com/0ZFQ5Zt.png">|
|2|version||`python --version`<br/><br/>`pip --version`|<img src="https://i.imgur.com/Sz8f5J3.png"><br/><img src="https://i.imgur.com/nFvBBgb.png">|

---

## Functions
|n|name|desc.|eg|O/P|
|-|----|-----|--|---|
|1|print()||`print("Hello World")`|
