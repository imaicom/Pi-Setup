# Raspberry-Pi-Setup

apt-get update
apt-get upgrade
rpi-update

raspi-config


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
apt-cache search <file name><BR>
