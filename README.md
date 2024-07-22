# Synology toggle reset button
Script to disable or enable the reset button and show current setting

- If you run the script with the disable option it will disable the reset button.
- If you run the script with the enable option it will enable the reset button.
- If you run the script without any option it will show the current reset button status.

### Download the script

1. Download the latest version _Source code (zip)_ from https://github.com/007revad/Synology_toggle_reset_button/releases
2. Save the download zip file to a folder on the Synology.
3. Unzip the zip file.

## There are 2 ways to run the script

### Scheduling the script in Synology's Task Scheduler

See <a href=how_to_schedule.md/>How to schedule a script in Synology Task Scheduler</a>

### Running the script via SSH

[How to enable SSH and login to DSM via SSH](https://kb.synology.com/en-global/DSM/tutorial/How_to_login_to_DSM_with_root_permission_via_SSH_Telnet)

**Note:** Replace /volume1/scripts/ with your Synology's path to where the script is located.

**To check the current setting of the reset button:**
```
sudo /volume1/scripts/toggle_reset_button.sh
```

**To disable the reset button:**
```
sudo /volume1/scripts/toggle_reset_button.sh disable
```

**To enable the reset button:**
```
sudo /volume1/scripts/toggle_reset_button.sh enable
```

<br>
