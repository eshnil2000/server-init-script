Copy to /etc/init.d
chmod +x /etc/init.d/test
Add any commands in the "start" function or "stop" function.

update-rc.d test defaults
update-rc.d test enable

Create an AMI image with this initi script.

Launch an instance with this AMI.
the commands in the start section will execute.
