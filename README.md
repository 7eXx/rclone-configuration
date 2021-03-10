# Rclone Configuration

This easy repository contains some service configuration for rclone with various account.  
Follow steps to integrate rclone and accounts with the linux os.

1. Install Rclone

2. Configure with "sudo rclone config"

3. Annotate the name account(s) creted in the previous step.

4. place the service in "/etc/serviced/system/"

5. Edit the information of the service like rclone connection name, 

    or the location of folder to link with rclone.

6. reload the daemon service with: "sudo systemctl daemon-reload"

7. To start the service exec: "sudo systemctl start onedrive-rclone.service"

8. Use generic systemd command to manage the serive

