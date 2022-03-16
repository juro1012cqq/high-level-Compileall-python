# high-level-Compileall-python
## Language: <strong>English</strong>/[<strong>Vietnamese</strong>](https://github.com/juro1012cqq/high-level-Compileall-python/blob/main/vietnamese.md)

:red_circle: :orange_circle: :green_circle:
<br/>Hi there, welcome to my project.
<br/>It is pretty <strong>secure and fast</strong>.
<br/>

---

### <strong><i>Enviroment</i></strong> :computer:
![Window 10 icon](/Image/icons8-windows-10-15.png) ***Windows 10 or above ver.***
<br/>
![Python icon](/Image/icons8-python-15.png) ***[Python 3.10.x](https://www.python.org/ftp/python/3.10.2/python-3.10.2-amd64.exe) or [above ver](https://www.python.org/downloads/).***
<br/>

---

### <strong><i>Installation</i></strong> :hammer_and_wrench:
<div align="center">
<a href="#CMD" title="Command Prompt"><image src="https://github.com/juro1012cqq/high-level-Compileall-python/blob/main/Image/icons8-command-line-50.png"/></a>
<a href="https://git.com" title="Git"><image src="https://github.com/juro1012cqq/high-level-Compileall-python/blob/main/Image/icons8-git-50.png"/></a>
</div>


```PS1
git clone https://github.com/juro1012cqq/high-level-Compileall-python.git
```

<div align="center">
<a href="#CMD" title="Windows PowerShell"><image src="https://github.com/juro1012cqq/high-level-Compileall-python/blob/main/Image/icons8-powershell-50.png"/></a>
</div>

```PS1
$url = "https://github.com/juro1012cqq/high-level-Compileall-python/raw/main/compilePYC.zip"
$fileSave = "Your path"
$unZipTo = "Your location that you want to unzip."
Invoke-WebRequest -Uri $url -Outfil $fileSave
Expand-Archive -Path $fileSave -DestinationPath $unZipTo
```
:gift::tada::tada::tada:
<br/>

---

### <strong><i>Used guide</i></strong> :blue_book:

```text
Systax:
    Case compilePYC.pyc:
        python compilePYC.pyc [options]
    Case compilePYC.exe:
        compilePYC.exe [options]
Options:
    --del-py            : Delete all file *.py  finish compiled
    --save-py           : Don't impact file *.py after finish compiled
    --on-log            : See all the proccessed
    --off-log (Default) : Break all the processed
Exam:
    python compilePYC.pyc --del-py --on-log
    python compilePYC.pyc --del-py
    compilePYC.exe --del-py --on-log
    compilePYC.exe --del-py
```

---

### <strong><i>Author</i></strong> :black_nib:
[@juro1012cqq](https://github.com/juro1012cqq)

---

### <strong><i>License</i></strong> :page_with_curl:

This project is licensed under the MIT License - see more at [here](https://github.com/juro1012cqq/high-level-Compileall-python/blob/b9ea12fabd463907b0a5d0e040b233a26b3dc565/LICENSE)