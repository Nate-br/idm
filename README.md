# IDM 

-IDM PATCHED EXECUTABLE AND 

-OPTIONAL /Batch script for Internet Download Manager (IDM) registry configuration and activation lock.

##  THE PATCHED IDM  Usage

-REPLACE THE OLD IDM WITH THE PATCHED ONE 

-RENAME IT TO IDMAN

-RUN 
  reg add "HKCU\Software\DownloadManager" /v FName   /t REG_SZ /d "FNAME" /f
  reg add "HKCU\Software\DownloadManager" /v LName   /t REG_SZ /d "LNAME" /f
  reg add "HKCU\Software\DownloadManager" /v Email   /t REG_SZ /d "4821.7390@tonec.com" /f
  reg add "HKCU\Software\DownloadManager" /v Serial  /t REG_SZ /d "L1KMV-492Z8-QHIWP-DEYG7" /f
  reg add "HKCU\Software\DownloadManager" /v idmvers /t REG_SZ /d "v6.43b15 Full" /f

  IN POWERSHELL AS ADMINISTRATOR
 
  VOILA!!!!!!!!!!

## THE SCRIPT
- **Activate**: Denies permission to IDM trial registry keys to maintain registered status.
- **Reset**: Resets activation and trial data cleanly.

## Usage
Run `lastfix.bat` as Administrator in Command Prompt.

## Write up
`Natnael Sisay IDM Registration.pdf`
`Natnael Sisay IDM.pdf`
