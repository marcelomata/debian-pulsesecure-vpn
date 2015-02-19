### Ansible workbook that installs Pulse SSL/VPN, Juniper SSL/VPN client on Debian 64-bit ###

#### By: Christian Nygaard Game-Hosting GH AB ####
Url: http://www.game-hosting.com Managed services for game companies

###### Install ansible #######
$ apt-get install ansible

###### Run the workbook to install msjnc #######
$ ansible-playbook -c local -i hosts playbook.yml

###### Surf to your ssl vpn, and run the Network connect setup ######
http://vpn.yourdomain.com

###### You should now be able to use the commandline app msjnc to connect to your VPN #######
$ msjnc

Done
