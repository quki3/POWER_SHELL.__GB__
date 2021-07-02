# POWER_SHELL.__GB__

##For those who are not aware of how to solve this error using Windows PowerShell

##Open PowerShell (Run As Administrator)
##Check the current execution policy using this command
```bash
Get-ExecutionPolicy
```
# You should get 'Restricted'
##Run this command to make it 'Unrestricted'
```bash
Set-ExecutionPolicy Unrestricted
```
###Check again whether execution policy changed by running this command
```bash
Get-ExecutionPolicy
```
# You should get 'Unrestricted'
###Now try to run nodemon on your project
###nodemon 'filename.js'
#Hope this would be helpful
