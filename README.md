# startup
auto setting scrypt 

sudo su -

yum -y install wget

wget https://raw.githubusercontent.com/Ruuuiii/startup/master/settingSquid && bash settingSquid \

#if you use webarena, use this code

wget https://raw.githubusercontent.com/Ruuuiii/startup/master/webArenaBasicauth



crontab -e 

0 11,23 * * * /usr/sbin/reboot
