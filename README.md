<div align="center">

## Easy Regestry Manipulation \- ERM


</div>

### Description

This code is useful for write, read and delete strings in regestry using wscript. You can now forget the cookies...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jo B](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jo-b.md)
**Level**          |Intermediate
**User Rating**    |4.0 (24 globes from 6 users)
**Compatibility**  |VbScript \(browser/client side\)

**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jo-b-easy-regestry-manipulation-erm__4-6716/archive/master.zip)





### Source Code

```
dim objReg
set objReg = Createobject("Wscript.shell")
objReg.regwrite "HKCU\Software\testKey\Option","Value"
'To read use, for example :
' msgbox objReg.regread("HKCU\Software\testKey\Option)
'To delete use :
' objReg.regdelete "HKCU\Software\testKey\Option","
```

