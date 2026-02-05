<h1 align="center">DISABLE SHOW MORE OPTIONS CONTEXT MENU</h1>
<hr>
  
## CMD / POWERSHELL Command to disable the default context menu in Windows 11

### Step one - Open Windows Terminal or PowerShell

Click the **Start Menu**, type `CMD` or `PowerShell`, and open it.

### Step two - Paste the following command

reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
     
### Step three - Reboot or restart Windows Explorer

You can restart your device, or if you just don't feel like it you can do the following:

1. Open task manager
2. Look for Windows Explorer (The task with the yellow windows folder icon)
3. Right click on it, and press **restart** if you see your taskbar disappear don't worry, it will come back.

### Step four - Enjoy your classic context menu
