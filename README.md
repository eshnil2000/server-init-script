#Copy to /etc/init.d
sudo chmod a+x /etc/init.d/test
sudo chown root:root /etc/init.d/test
#Add any commands in the "start" function or "stop" function.

sudo update-rc.d test defaults
sudo update-rc.d test enable

#Create an AMI image with this initi script.

#Launch an instance with this AMI.
#the commands in the start section will execute.
