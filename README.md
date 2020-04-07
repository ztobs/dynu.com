# dynu.com
A package for debian based linux servers like ubuntu

**Download the package**:
`wget https://github.com/ztobs/dynu.com/raw/master/dynuiuc_2.6.2-3_amd64.deb`


**Install the package**: 
`sudo dpkg -i dynuiuc_2.6.2-3_amd64.deb`


**Configure the script with your login credentials**: 
`sudo nano /etc/dynuiuc/dynuiuc.conf`

save it


**Open crontab**: 
`sudo crontab -e`


**add the following line to your crontab**: 
`@reboot dynuiuc -d -l /etc/dynuiuc/dynuiuc.log -c /etc/dynuiuc/dynuiuc.conf`

save it

it will run as a deamon 
