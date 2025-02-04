# NagiosInstallation

clone repositery 

git clone https://github.com/bablookewat/NagiosInstallation 

#give Permission to install.sh

chmode 777 install.sh

#Run install.sh

./install.sh

#give permission and Install plugings

chmod 777 install_plugin.sh

./install_plugin.sh

############ Update it to 4.5.9 version #########
#Before run update script stop the nagios services 

service nagios stop

#Give permission to update.sh file and install

chmod 777 update.sh

./update.sh
