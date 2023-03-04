# desafi-dio git/github

# scrpt backup xampp/glpi

xcopy "C:\xampp" "D:\Backup Xampp\xampp" /e/h/c/i/y
ren "D:\Backup Xampp\xampp" "%date:~0,2%%date:~3,2%%date:~6,4%"

pause

# script backup xampp/glpi rede

xcopy "D:\Backup Xampp\%date:~0,2%%date:~3,2%%date:~6,4%" "\\Suporte-ryan\Backup\xampp\%date:~0,2%%date:~3,2%%date:~6,4%\" /e/h/c/i/y

pause
