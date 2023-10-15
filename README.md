# odoo16_test_server
 odoo16 homelab installation for test


how to install odoo 16 on ubuntu 
# installation with installation program

 1. sudo apt update && upgrade
 2.  wget -q -O - https://nightly.odoo.com/odoo.key | sudo gpg --dearmor -o /usr/share/keyrings/odoo-archive-keyring.gpg
 3.  echo 'deb [signed-by=/usr/share/keyrings/odoo-archive-keyring.gpg] https://nightly.odoo.com/15.0/nightly/deb/ ./' | sudo tee /etc/apt/sources.list.d/odoo.list
 4.  sudo apt-get update && sudo apt-get install odoo
 **configure odoo**
 
 - [ ] sudo /etc/odoo/odoo.conf : and change password, localhost and admin setting
 - [ ] sudo -u postgres psql : to connect to database cli
 - [ ] \du : to list odoo user
 - [ ] alter user odoo with password 'pswd'; : to set password you enter in configuration file
 - [ ] \q: quit database cli
 - [ ] and go in the navigator and launch ; localhost:8069 and configure step by step

# credential 

VM ; 

 - login : odoo
 - password : odoo

Odoo web app 

 - username : odoo@test.local
 - password : Admin
 - master password : @dmin1


# Thanks
