<div align="center">

## Lock Workstation \(Lock Computer\) API CALL


</div>

### Description

This line of code will allow you to lock a Windows 2000 machine. Simulates CLT+ALT+DEL and Clicking the Lock Workstations.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Nick Bork](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/nick-bork.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/nick-bork-lock-workstation-lock-computer-api-call__1-14080/archive/master.zip)





### Source Code

```
'In a module please place the following line of code
Public Declare Function LockWorkStation Lib "user32" () As Boolean
'On a command button or Sub, please this line of code
LockWorkstation
'Please note that this can also be done by putting this line of code in a button
Shell "rundll32 user32.dll,LockWorkStation"
```

