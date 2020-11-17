# startup
auto setting scrypt 

sudo su -

yum -y install wget

wget https://raw.githubusercontent.com/Ruuuiii/startup/master/settingSquid && bash settingSquid \
or if using Web Arena vps,

wget https://raw.githubusercontent.com/Ruuuiii/startup/master/webArenaBasicauth && bash settingSquid 



crontab -e 

0 9,21 * * * /usr/sbin/reboot
