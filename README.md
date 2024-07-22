# Synology toggle reset button

<a href="https://github.com/007revad/Synology_toggle_reset_button/releases"><img src="https://img.shields.io/github/release/007revad/Synology_toggle_reset_button.svg"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F007revad%2FSynology_toggle_reset_button&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=false"/></a>
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/paypalme/007revad)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/007revad)
[![committers.top badge](https://user-badge.committers.top/australia/007revad.svg)](https://user-badge.committers.top/australia/007revad)
<!-- [![committers.top badge](https://user-badge.committers.top/australia_public/007revad.svg)](https://user-badge.committers.top/australia_public/007revad) -->
<!-- [![committers.top badge](https://user-badge.committers.top/australia_private/007revad.svg)](https://user-badge.committers.top/australia_private/007revad) -->
<!-- [![Github Releases](https://img.shields.io/github/downloads/007revad/synology_toggle_reset_button/total.svg)](https://github.com/007revad/Synology_toggle_reset_button/releases) -->

### Description

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
