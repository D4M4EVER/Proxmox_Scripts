<h1 align="center" id="heading"> Select a Proxmox Helper Below </h1>

<details>
<summary markdown="span">Proxmox VE 7 Post Install</summary>
 
<p align="center"><img src="https://www.proxmox.com/images/proxmox/Proxmox_logo_standard_hex_400px.png" alt="Proxmox Server Solutions" height="55"/></p>

<h1 align="center" id="heading"> Proxmox VE 7 Post Install </h1>

This script will Disable the Enterprise Repo, Add & Enable the No-Subscription Repo, Add & Disable Test Repo (repo's can be enabled/disabled via the UI in Repositories) 
and attempt the *No-Nag* fix. 
 
Run the following in the Proxmox Web Shell. ⚠️ **PVE7 ONLY**

```yaml
bash <(curl -s https://raw.githubusercontent.com/D4M4EVER/Proxmox_Scripts/main/misc/pve_post_install.sh )
```

Proxmox with auto update while running this script, it may take some time depending on your current version and/or internet speed.

____________________________________________________________________________________________ 

</details>

<details>
<summary markdown="span">Proxmox VE 7 Dark Theme</summary>
 
<p align="center"><img src="https://camo.githubusercontent.com/f6f33a09f8c1207dfb3dc1cbd754c2f3393562c11b1c999751ad9a91a656834a/68747470733a2f2f692e696d6775722e636f6d2f536e6c437948462e706e67" height="100"/></p>

<h1 align="center" id="heading"> Proxmox Discord Dark Theme </h1>

A dark theme for the Proxmox VE 7 Web UI by [Weilbyte](https://github.com/Weilbyte/PVEDiscordDark)
 
Run the following in the Proxmox Web Shell.

```yaml
bash <(curl -s https://raw.githubusercontent.com/Weilbyte/PVEDiscordDark/master/PVEDiscordDark.sh ) install
```

To uninstall the theme, simply run the script with the `uninstall` command.

____________________________________________________________________________________________ 

</details>

<details>
<summary markdown="span">Proxmox Backup Server 2.1 Post Install</summary>
 
<p align="center"><img src="https://www.proxmox.com/images/proxmox/Proxmox_logo_standard_hex_400px.png" alt="Proxmox Server Solutions" height="55"/></p>

<h1 align="center" id="heading"> Proxmox Backup Server 2.1 Post Install </h1>

This script will Disable the Enterprise Repo, Add & Enable the No-Subscription Repo, Add & Disable Test Repo (repo's can be enabled/disabled via the UI in Repositories) 
and attempt the *No-Nag* fix. 
 
Run the following in the Proxmox Web Shell. ⚠️ **PBS 2.1 ONLY**

```yaml
 bash <(curl -s https://raw.githubusercontent.com/D4M4EVER/Proxmox_Scripts/main/misc/pbs_post_install.sh )
```

It's recommended to update Proxmox after running this script, before configuring Proxmox Backup Server.

____________________________________________________________________________________________ 

</details>

<details>
<summary markdown="span">Proxmox Backup Server 2.1 Dark Theme</summary>
 
<p align="center"><img src="https://camo.githubusercontent.com/f6f33a09f8c1207dfb3dc1cbd754c2f3393562c11b1c999751ad9a91a656834a/68747470733a2f2f692e696d6775722e636f6d2f536e6c437948462e706e67" height="100"/></p>

<h1 align="center" id="heading"> Proxmox Discord Dark Theme </h1>

A dark theme for the Proxmox Backup Server Web UI by [Luckyvb](https://github.com/Luckyvb/PBSDiscordDark)
 
Run the following in the Proxmox Web Shell.

```yaml
bash <(curl -s https://raw.githubusercontent.com/Luckyvb/PBSDiscordDark/master/PBSDiscordDark.sh ) install
```

To uninstall the theme, simply run the script with the `uninstall` command.

____________________________________________________________________________________________ 

</details>

 ____________________________________________________________________________________________ 
 Scripts based off [tteck](https://github.com/tteck/Proxmox) Proxmox Helpers
