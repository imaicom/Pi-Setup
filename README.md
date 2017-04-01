# Raspberry-Pi-Setup

vi /etc/apt/sources.list<BR>
append 5 lines<BR>
deb http://ftp.jp.debian.org/debian/ squeeze main non-free contrib  
deb http://security.debian.org/ squeeze/updates main contrib non-free  
deb http://ftp.jp.debian.org/debian/ squeeze-updates main contrib non-free  
deb http://ftp.jaist.ac.jp/raspbian jessie main contrib non-free  
deb http://ftp.yz.yamagata-u.ac.jp/pub/linux/raspbian/raspbian/ jessie main contrib non-free  
  
<BR>
apt-get update<BR>
apt-get upgrade<BR>
apt-get dist-upgrade<BR>
rpi-update<BR>
<BR>
raspi-config<BR>
<BR>
<BR>
apt-get install numlockx<BR>
apt-get install gparted<BR>
apt-get install libreoffice-l10n-ja libreoffice-help-ja<BR>
apt-get install iceweasel iceweasel-l10n-ja<BR>
apt-get install pishutdown<BR>
apt-get install midori<BR>
apt-get install geany geany-plugins<BR>
apt-get install jstest-gtk<BR>
apt-get install ibus-anthy<BR>
apt-get install fonts-takao xfonts-kaname ttf-kochi-gothic xfonts-intl-japanese<BR>
apt-get install jfbterm<BR>
apt-get install ksnapshot<BR>
<BR>
vi /boot/config.txt<BR>
cut '#' disable_overscan=1<BR>
append 'dtparam=act_led_trigger=heartbeat'<BR>
append 'max_usb_current=1'<BR>
<BR>
apt-cache search 'file name'<BR>
<BR>
(CPU Temp)vcgencmd measure_temp<BR>
<BR>
(Geany setting)<BR>
<img src="geany_compile_setting.png" width="80%" height="80%" ><BR>
cc -c "%f" -lwiringPi -lm  
cc -o "%e" "%f" -lwiringPi -lm  
"sudo ./%e"  

