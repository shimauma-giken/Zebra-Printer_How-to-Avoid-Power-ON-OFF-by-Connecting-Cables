## Zebra-Printer_How to Avoid Power ON-OFF by Connecting Cables
 Zebra プリンタ；シリアル・USBケーブルの着脱で電源ON・OFFしないようにする方法

テストや現場でケーブルの抜き差しの度にプリンタが電源ON/OFFしてしまうのがストレスだったので。 
有線接続で運用している現場でも重宝される。  
下記コマンドでDTRによる電源制御が無くなる。元に戻す場合はON設定にすればよい。  
  
  
<pre>
! U1 setvar "power.dtr_power_off" "off"
! U1 getvar "power.dtr_power_off"
"off"
</pre>

 詳細は本家のドキュメントを参照。  
 https://zebratechnologies.force.com/s/article/Enabling-and-Disabling-DTR-on-Mobile-Printers?language=en_US  
 
  
