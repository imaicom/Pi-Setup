# Raspberry-Pi-Setup

apt-get update
apt-get upgrade
rpi-update

raspi-config


apt-get install pishutdown
apt-get install midori
apt-get install geany geany-plugins
apt-get install jstest-gtk
apt-get install ibus-anthy
apt-get install xfonts-takao xfonts-kaname ttf-kochi-gothic xfonts-intl-japanese
apt-get install jfbterm

vi /boot/config.txt
cut '#' disable_overscan=1
append 'dtparam=act_led_trigger=heartbeat'

apt-cache search <file name>
