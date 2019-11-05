# Fonehome 
### Start et-fone-home.service on System Startup Using Systemd on Linux

You will need to add a new file call autossh.service via this path 

`/etc/systemd/system/et-fone-home.service`

After creating the systemd .service file do:

# Reload Systemd to find the new service file
 systemctl daemon-reload
# Check the status of the .service file
 systemctl status et-fone-home.service.service
# Restart the .service  
 systemctl restart et-fone-home.service.service
# Enable autossh.service to be started on bootup:
 systemctl enable et-fone-home.service.service
