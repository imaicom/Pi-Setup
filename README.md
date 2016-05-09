# Raspberry-Pi-Setup

vi /etc/apt/sources.list<BR>
append 'deb http://ftp.jp.debian.org/debian/ squeeze main non-free contrib'<BR>
append 'deb http://security.debian.org/ squeeze/updates main contrib non-free'<BR>
append 'deb http://ftp.jp.debian.org/debian/ squeeze-updates main contrib non-free'<BR>
<BR>
apt-get update<BR>
apt-get upgrade<BR>
rpi-update<BR>
<BR>
raspi-config<BR>
<BR>
<BR>
apt-get install libreoffice-l10n-ja<BR>
apt-get install libreoffice-help-ja<BR>
apt-get install iceweasel iceweasel-l10n-ja<BR>
apt-get install pishutdown<BR>
apt-get install midori<BR>
apt-get install geany geany-plugins<BR>
apt-get install jstest-gtk<BR>
apt-get install ibus-anthy<BR>
apt-get install xfonts-takao xfonts-kaname ttf-kochi-gothic xfonts-intl-japanese<BR>
apt-get install jfbterm<BR>
<BR>
vi /boot/config.txt<BR>
cut '#' disable_overscan=1<BR>
append 'dtparam=act_led_trigger=heartbeat'<BR>
<BR>
apt-cache search 'file name'<BR>


