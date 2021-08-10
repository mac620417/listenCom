※請注意，安裝此deb時，需連網，因要安裝別的線上套件，安裝完成後，請重新開機

1.安裝listen時，請輸入密碼zzxx1122
2.此為監聽com port的功能，而鮑率的設定在 usr/local/src/listenCom/etc/listenComCfg/config.ini
   要用的鮑率，前方請勿加#
   Ex :
     #baudrate = 9600
　　　baudrate = 19200
　　　#baudrate = 38400
　　　#baudrate = 115200
　　　鮑率=19200
　　　
　　　baudrate = 9600
　　　#baudrate = 19200
　　　#baudrate = 38400
　　　#baudrate = 115200
　　　鮑率=9600
　　　
　　　
　　　
3.產生的檔案在 /tmp/the_com1.txt
   開機後要有第一筆資料進來才會建檔。若無建檔表示沒有擷取到資料

特別注意，硬體com port連接時，請將中間的橘色轉接頭移除，讓週邊的DB9與Pi上的com轉接板直接連結，讓 Tx—>Rx  Rx—>Tx
   