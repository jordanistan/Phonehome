# Fonehome 
### Start AutoSSH on System Startup Using Systemd on Linux

You will need to add a new file call autossh.service via this path 

`/etc/systemd/system/autossh.service`

After creating the systemd .service file do:

# Reload Systemd to find the new service file
 systemctl daemon-reload
# Check the status of the .service file
 systemctl status autossh.service
# Restart the .service  
 systemctl restart autossh.service
# Enable autossh.service to be started on bootup:
 systemctl enable autossh.service
