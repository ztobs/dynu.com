# dynu.com
A package for debian based linux servers like ubuntu


**Install the package**: 
sudo dpkg -i dynuiuc_2.6.2-3_amd64.deb


**Configure the script with your login credentials**: 
sudo nano /etc/dynuiuc/dynuiuc.conf


**Open crontab**: 
sudo crontab -e


**add the following line to your crontab**: 
dynuiuc -d -c /etc/dynuiuc/dynuiuc.conf

it will run as a deamon 
