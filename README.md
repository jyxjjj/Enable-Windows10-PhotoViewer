# Windows10 照片查看器启用工具
此注册表项目将帮助 Windows10 用户 启用 照片查看器

此注册表项目来自网络，故使用Unlicense进行授权，这意味着作者宣布放弃此应用版权

``` Reg
Windows Registry Editor Version 5.00
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.jpg]
@="PhotoViewer.FileAssoc.Tiff"
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.jpeg]
@="PhotoViewer.FileAssoc.Tiff"
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.gif]
@="PhotoViewer.FileAssoc.Tiff"
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.png]
@="PhotoViewer.FileAssoc.Tiff"
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.bmp]
@="PhotoViewer.FileAssoc.Tiff"
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.pcx]
@="PhotoViewer.FileAssoc.Tiff"
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.tiff]
@="PhotoViewer.FileAssoc.Tiff"
; Change Extension’s File Type
[HKEY_CURRENT_USER\Software\Classes\.ico]
@="PhotoViewer.FileAssoc.Tiff"
```