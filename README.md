<div align="center">

## VERY SIMPLE Always on top code\!


</div>

### Description

This is the simplest code ever for always on top, if you find anything simpler (which i doubt) let me know!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ryan33](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ryan33.md)
**Level**          |Beginner
**User Rating**    |5.0 (20 globes from 4 users)
**Compatibility**  |VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ryan33-very-simple-always-on-top-code__1-49716/archive/master.zip)

### API Declarations

```
' Declarations for always on top
Private Declare Function SetWindowPos Lib "user32" (ByVal hwnd As Long, ByVal hWndInsertAfter As Long, ByVal X As Long, ByVal Y As Long, ByVal cx As Long, ByVal cy As Long, ByVal wFlags As Long) As Long
```


### Source Code

```
Private Sub Form_Load()
  SetWindowPos Me.hwnd, -1, 0, 0, 0, 0, 3
End Sub
```

