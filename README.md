# win-app-remove
How to remove apps after updates the win system


Let's get started by opening PowerShell as admin. 
Press the Windows Key + X and click on Windows PowerShell (Admin).

All you have to do now is copy and paste any of the following codes to remove the corresponding app. 
You won't see any prompts or confirmation, so be sure to enter the correct line.

# Remove microsoft default tools:


## Calculator:
    Get-AppxPackage *windowscalculator* | Remove-AppxPackage


## Alarms and Clock:
    Get-AppxPackage *windowsalarms* | Remove-AppxPackage

## Camera:
    Get-AppxPackage *windowscamera* | Remove-AppxPackage

## Get Office:
    Get-AppxPackage *officehub* | Remove-AppxPackage

## Get Started:
    Get-AppxPackage *getstarted* | Remove-AppxPackage

## Get Skype:
    Get-AppxPackage *skypeapp* | Remove-AppxPackage



# Viewer

## 3D Viewer:
    Get-AppxPackage Microsoft.Microsoft3DViewer | Remove-AppxPackage

## 3D Builder:
    Get-AppxPackage *3dbuilder* | Remove-AppxPackage

## Calendar and Mail:
    Get-AppxPackage *windowscommunicationsapps* | Remove-AppxPackage
    
    

# Remove microsoft default apps:

## Groove Music:
    Get-AppxPackage *zunemusic* | Remove-AppxPackage

## Uninstall Get Help:
    Get-AppxPackage *Microsoft.GetHelp* -AllUsers | Remove-AppxPackage

## Maps:
    Get-AppxPackage *windowsmaps* | Remove-AppxPackage

## Microsoft Solitaire Collection:
    Get-AppxPackage *solitairecollection* | Remove-AppxPackage

## Money:
    Get-AppxPackage *bingfinance* | Remove-AppxPackage

## Movies & TV:
    Get-AppxPackage *zunevideo* | Remove-AppxPackage

## News:
    Get-AppxPackage *bingnews* | Remove-AppxPackage

## Sports:
    Get-AppxPackage *bingsports* | Remove-AppxPackage

## People:
    Get-AppxPackage *people* | Remove-AppxPackage

## Phone Companion:
    Get-AppxPackage *windowsphone* | Remove-AppxPackage


## OneNote:
    Get-AppxPackage *onenote* | Remove-AppxPackage


## Photos:
    Get-AppxPackage *photos* | Remove-AppxPackage

## Store:
    Get-AppxPackage *windowsstore* | Remove-AppxPackage

## Voice Recorder:
    Get-AppxPackage *soundrecorder* | Remove-AppxPackage

## Weather:
    Get-AppxPackage *bingweather* | Remove-AppxPackage

## Xbox:
    Get-AppxPackage *xboxapp* | Remove-AppxPackage


## Uninstall With PowerShell

When all else fails, we can remove it from the Command Prompt.

    Get-AppxPackage Microsoft.BingNews | Remove-AppxPackage
