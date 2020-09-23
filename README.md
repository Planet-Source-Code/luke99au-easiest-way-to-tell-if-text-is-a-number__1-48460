<div align="center">

## Easiest way to tell if text is a number


</div>

### Description

Shows you how to check if text is a numeric *Easiest way*
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[luke99au](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/luke99au.md)
**Level**          |Beginner
**User Rating**    |3.6 (50 globes from 14 users)
**Compatibility**  |VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/luke99au-easiest-way-to-tell-if-text-is-a-number__1-48460/archive/master.zip)





### Source Code

<i>'You need a command button (Command1)<br>
'Also a textbox (Text1)</i><br><br>
Private Sub Command1_Click()
 If IsNumeric(Text1.Text) Then <br>
 MsgBox "Thankyou for entering a number" <br>
 Else: MsgBox "Please enter a number" <br>
End If
End Sub <br>

