<p align="center">
  <a href="https://github.com/rythampkhandelwal/WowSpotify"></a>
</p>

<h2> 
  <div align="center">
    <b>Patcher for Spotify Desktop Client on Windows </b>
  </div> 
</h2>

<p align="center"> •
  <a href="#requirements">Requirements</a> •
  <a href="#features">Features</a> •
  <a href="#installation--update">Installation</a> •
  <a href="#uninstall">Uninstall</a> •
  <a href="#faq">FAQ</a> •

</p>

<h1 id="requirements">Requirements</h1>

- **OS:** Windows 7-11
- **Spotify:** [Official desktop version](https://loadspot.pages.dev) (Microsoft Store version is not suitable)
- **PowerShell:** 5.1 and above

<h1 id="features">Features</h1>

- **Blocks all banner, video, and audio ads** in the client
- **Hiding podcasts, episodes, and audiobooks** from the homepage (optional)
- **Block Spotify automatic updates** (optional)
- **Some native experimental features have been changed**
- **Analytics sending has been disabled** 

<h1 id="installation--update">Installation / Update</h1>
<h3>Choose installation type:</h3>
<details>
<summary><small>Usual installation (New theme)</small></summary><p>
  
  #### During installation, you need to confirm some actions, also contains:
  
  - New theme activated (new right and left sidebar, some cover change)

  <h4> </h4>
  
#### Just download and run [Install_New_theme.bat](https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/Install_New_theme.bat)

or

#### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/run.ps1') } -new_theme"
```


</details>
  

<details>
<summary><small>Usual installation (Old theme)</small></summary><p>
  
  #### During installation, you need to confirm some actions, also contains:
  - Forced installation of version 1.2.13 (since the old theme was removed in subsequent versions)
  - Old theme activated
  - Automatic blocking of Spotify updates


  <h4> </h4>
  
#### Just download and run [Install_Old_theme.bat]

### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/run.ps1') } -v 1.2.13.661.ga588f749-4064 -confirm_spoti_recomended_over -block_update_on"
```


</details>
 
<details>
<summary><small>Full installation</small></summary><p>
  
  <h4>Full installation without confirmation, what does it do?</h4> 
  
  - New theme activated (new right and left sidebar, some cover change)
  - Hiding podcasts/episodes/audiobooks from the homepage
  - Removal of Spotify MS if it was found 
  - Installation of the recommended version of Spotify (if another client has already been found, it will be installed over) 
  - Blocking of Spotify updates
  - After the installation is completed, the client will autorun.
  
<h4> </h4>

#### Just download and run [Install_Auto.bat](https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/scripts/Install_Auto.bat)

or

#### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/scripts/Install_Auto.bat') } -confirm_uninstall_ms_spoti -confirm_spoti_recomended_over -podcasts_off -block_update_on -start_spoti -new_theme -adsections_off -lyrics_stat spotify"
```

</details>

<details>
<summary><small>Other types of installations</summary><p>

<details>
<summary><small>Installation for premium</small></summary><p>
  
  #### Usual installation only without ad blocking, for those who have a premium account, also contains:
  
  - New theme activated (new right and left sidebar, some cover change)
  - Disabled only audio ads in podcasts

  <h4> </h4>
  
#### Just download and run [Install_Prem.bat](https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/scripts/Install_Prem.bat)

or

#### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/run.ps1') } -premium -new_theme"
```


</details>


<h1 id="uninstall">Uninstall</h1>

- Just run [Uninstall.bat](https://github.com/rythampkhandelwal/WowSpotify/raw/refs/heads/master/Uninstall.bat)



<h1 id="disclaimer">Disclaimer</h1>

WowSpotify is a tool that modifies the official Spotify client, provided as an evaluation version — use it at your own risk.
