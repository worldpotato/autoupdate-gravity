# autoupdate-gravity
A systemd timer to update the gravity lists on a daily basis

# How to use the timer scripts
 1. Copy these files to `/etc/systemd/system`
 2. Enable the timer with `sudo systemctl enable update-blocklists.timer`
 3. Start the timer with `sudo systemctl start update-blocklists.timer`

