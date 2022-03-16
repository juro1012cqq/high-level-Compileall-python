# high-level-Compileall-python
## Ngôn ngữ: [<strong>Tiếng Anh</strong>](https://github.com/juro1012cqq/high-level-Compileall-python/)/<strong>Tiếng Việt</strong>

:red_circle: :orange_circle: :green_circle:
<br/>Xin chào, chào mừng đến với dự án của t.
<br/>Dự án khá <strong>bảo mật và nhanh</strong>.
<br/>

---

### <strong><i>Môi trường</i></strong> :computer:
![Window 10 icon](/Image/icons8-windows-10-15.png) ***Windows 10 hoặc phiên bản cao hơn.***
<br/>
![Python icon](/Image/icons8-python-15.png) ***[Python 3.10.x](https://www.python.org/ftp/python/3.10.2/python-3.10.2-amd64.exe) hoặc [phiên bản cao hơn](https://www.python.org/downloads/).***
<br/>

---

### <strong><i>Cài đặt</i></strong>
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

### <strong><i>Hướng dẫn sử dụng</i></strong>

```text
CÚ PHÁP:
    TH compilePYC.pyc:
        python compilePYC.pyc [options]
    TH compilePYC.exe:
        compilePYC.exe [options]
Các cài đặt:
    --del-py            : Xóa tất cả file *.py sau khi hoàn thành biên dịch sang *.pyc
    --save-py           : Không tác động đến *.py sau khi hoàn thành quá trình biên dịch
    --on-log            : Xem tất cả quá trình xử lý
    --off-log (Default) : Bỏ qua(không cần xem) quán trình xử lý.
Ví dụ:
    python compilePYC.pyc --del-py --on-log
    python compilePYC.pyc --del-py
    compilePYC.exe --del-py --on-log
    compilePYC.exe --del-py
```

---

### <strong><i>Tác giả</i></strong>
[@juro1012cqq](https://github.com/juro1012cqq)

---

### <strong><i>Bản quyền</i></strong>

Dự án này được cấp phép theo giấy phép MIT - Xem thêm tại [đây](https://github.com/juro1012cqq/high-level-Compileall-python/blob/b9ea12fabd463907b0a5d0e040b233a26b3dc565/LICENSE)