# 1️⃣ AKEBI

<details>

<summary><strong><code>Error With Code</code></strong></summary>

## <mark style="color:yellow;">The</mark> <mark style="color:yellow;"></mark><mark style="color:yellow;">`Runtime error 5/139. Error: Validation check error`</mark> <mark style="color:yellow;"></mark><mark style="color:yellow;">appears when the system time is set incorrectly in Windows.</mark>

<img src="../.gitbook/assets/image (4).png" alt="" data-size="original">

\-> Fix :&#x20;

&#x20;![](<../.gitbook/assets/image (1) (1).png>)

<img src="../.gitbook/assets/image (46).png" alt="" data-size="original">

### <mark style="color:yellow;">\[Warn] Found new version. Downloading... \[Error] Version verification failed: The current version is outdated.</mark> <a href="#warn-found-new-version.-downloading...-error-version-verification-failed-the-current-version-is-outd" id="warn-found-new-version.-downloading...-error-version-verification-failed-the-current-version-is-outd"></a>

If after launching you have such a console (screenshot below), it means that an update has been released and a new build (version) has been downloaded to the same folder.

![](https://docs.akebi.wiki/\~gitbook/image?url=https:%2F%2F735162219-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FZbKaBGYDYr0igtCwvs4p%252Fuploads%252FZSa9Xr4SKLlIzQJGXPNn%252Fimage.png%3Falt=media%26token=46f0e65a-3954-488c-906a-2a5dd6b90f47\&width=768\&dpr=4\&quality=100\&sign=785fa4fa8d8d82212fceba3605d2d74d893218c3ac2279897ef76c5e3649184e)

### <mark style="color:yellow;">Error at hooking API ''LoadStringA'' Dumping first 32 bytes: 48 8B C4 48 89 58 08</mark> <a href="#error-at-hooking-api-loadstringa-dumping-first-32-bytes-48-8b-c4-48-89-58-08" id="error-at-hooking-api-loadstringa-dumping-first-32-bytes-48-8b-c4-48-89-58-08"></a>

1. Open cmd as administrator
2. Type in `sfc /scannow`
3. Wait for the scan to finish
4. After it is finished, type in `DISM /Online /Clean-up /RestoreHealth`
5. Restart your PC

### <mark style="color:yellow;">Error at hooking API "LdrFindResource\_U" Dumping first 32 bytes: 48 89 5C 24 08 48</mark> <a href="#error-at-hooking-api-ldrfindresource_u-dumping-first-32-bytes-48-89-5c-24-08-48" id="error-at-hooking-api-ldrfindresource_u-dumping-first-32-bytes-48-89-5c-24-08-48"></a>

Update Microsoft Visual Runtime [https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) (all versions from old to new must be downloaded) or [https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) (run the .bat file after unzipping it into the folder (the six-pointed icon) and wait for the installation)



### <mark style="color:yellow;">Source Code error, File not found?</mark>

<img src="../.gitbook/assets/image (26).png" alt="" data-size="original">

For this error, use the Setting file to enter your key and then paste the old config file .

### <mark style="color:yellow;">ERROR Failed Connect to server , How to fix ?</mark>

<img src="../.gitbook/assets/image (28).png" alt="" data-size="original">

### If this error occurs, use VPN to try opening for example: 1.1.1.1

### <mark style="color:yellow;">Error code: 31-4302</mark>&#x20;

Go to Settings section Turn off protection: Use predefined file signatures :

<img src="../.gitbook/assets/image (31).png" alt="" data-size="original">

IF you see Orther File Detele them .

<img src="../.gitbook/assets/image (44).png" alt="" data-size="original">

### <mark style="color:yellow;">Injection failed: Cannot find AC driver, further game loading is insecure. You can disable this check by adding ''Disable Driver Check = true' in 'Inject' section in.ini file. OK</mark> <a href="#injection-failed-cannot-find-ac-driver-further-game-loading-is-insecure.-you-can-disable-this-check" id="injection-failed-cannot-find-ac-driver-further-game-loading-is-insecure.-you-can-disable-this-check"></a>

If this error occurs, you are asked to add **DisableDriverCheck = true** to cfg.ini, but each user has its own name and format, so you will have to find it yourself. You have to open each file with a text cheat and find it

At first it will look like this

Copy

```
[GenshinImpact]
Path = C:\Program Files\Genshin Impact\Genshin Impact game\GenshinImpact.exe
```

Then you indent 2 lines and on line 4 add \[Inject] and after it on a new line **DisableDriverCheck = true**

An example of what it should look like:

Copy

```
[GenshinImpact]
Path = C:\Program Files\Genshin Impact\Genshin Impact game\GenshinImpact.exe

[Inject]
DisableDriverCheck = true
```

Or

```
[GenshinImpact]
Path = C:\Program Files\Genshin Impact game\Genshin Impact game\GenshinImpact.exe

[Inject]
DisableDriverCheck = true
DisableProtectionCheck = true
```

</details>

<details>

<summary><strong><code>Error No Code</code></strong></summary>

### <mark style="color:yellow;">Interactive Map / Cheat menu is shifted, what to do?</mark> <a href="#interactive-map-cheat-menu-is-shifted-what-to-do" id="interactive-map-cheat-menu-is-shifted-what-to-do"></a>

* Turn off-screen scaling if it is enabled (set it to 100%)
* If you like to play in **Full Screen** **mode**, and you have _stretched the game resolution from 2560x1440 windowed_ to _your monitor resolution of 3840x2160_ for **Full Screen mode**, then the solution to your problem is below.

**You can :**

* a) Set the maximum screen resolution of the game to match the maximum resolution of your screen _3840x2160 main monitor = 3840x2160 game resolution_ (If it is important for you to play in this mode)
* b) Reduce the resolution of your display (screen) in Windows settings to a value acceptable to you (**DON'T TOUCH THE SCALE TAB!!!**). And after entering the game you will have in your settings the maximum resolution that you set (_was 3840_ you _set 2560_ in the display settings, so the maximum resolution of the game on the whole _screen will be 2560_).

### <mark style="color:yellow;">The cheat starts the game, but there is no console</mark> <a href="#the-cheat-starts-the-game-but-there-is-no-console" id="the-cheat-starts-the-game-but-there-is-no-console"></a>

1. Check your cfg.json for errors.
2. Check your cfg.ini for correct path to genshin (check with official launcher where genshin executable file is and compare specified directories).
3. Try to delete all cfg in cheat folder.

### <mark style="color:yellow;">In the console error \[warn] Exception 0XE (your error)</mark> <a href="#in-the-console-error-warn-exception-0xe-your-error" id="in-the-console-error-warn-exception-0xe-your-error"></a>

#### Solutions to problems (you can try any way) <a href="#solutions-to-problems-you-can-try-any-way" id="solutions-to-problems-you-can-try-any-way"></a>

* Remove all map tags and esp settings from cfg.
* Remove the paternoster scanner.
* Check your cfg validity.

### <mark style="color:yellow;">Cheat not responding to hotkeys and other stuff</mark> <a href="#cheat-not-responding-to-hotkeys-and-other-stuff" id="cheat-not-responding-to-hotkeys-and-other-stuff"></a>

* Remove the cfg.json and try to do the actions that didn't work for you again (before that you should configure the cheat as you need it)

### <mark style="color:yellow;">The game starts with the cheat and immediately crashes</mark> <a href="#the-game-starts-with-the-cheat-and-immediately-crashes" id="the-game-starts-with-the-cheat-and-immediately-crashes"></a>

* Check the version of your Windows, if it is lower than Windows10 - Windows11 then the cheat will not run for you (Windwos7, XP, Vista, etc. are not supported, Windows8 is not known).
* Check your **cfg.json** for broken lines (it could be empty, or the coding is broken, check on JSON validate websites)
* Check if you have any third-party anticheats running in your processes (vanguard, faceit, etc.)
* Check if you have antiviruses running (even if you were sure they were turned off, check again, make sure the checkboxes for scanning or protection are turned off).
* Download the new version of the Lauder from the link you were given, or you know (if you were given a link to the **mega disk**, it is **not a direct link**).
* Check the path to the **Genshin** and **Akebi** folder, if they contain **broken characters, emoji, invisible characters and anything else that might look weird somehow**, remove them or move the folder to a normal location.
* Check the version of the game running with the software and without it, if they are different, then you have a path to the old version of the game in the software (change/remove the path in cfg.ini )

### <mark style="color:yellow;">For those of you whose game has 2 drives!</mark>

Desktop Right click on Genshin and select <mark style="color:orange;">\[Open file Location]</mark> - Scroll up and select the folder <mark style="color:orange;">\[Genshin Impact game]</mark> which will appear to you like this.

![](<../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1).png>)![](<../.gitbook/assets/image (21).png>)

Then you copy this path into Akebilaucher's path selection section and it will show a folder for you to select genshinImpact.exe .

### <mark style="color:yellow;">Why didn't I show the menu and crashed when I came in game ?</mark>

* If you do not show menu please check if you are enabling overplay software showing parameters such as MSIburner, if yes please turn it off . press F1 to open the menu or mark ' according to your file setting.&#x20;

### <mark style="color:yellow;">Why am I deleted laucher when I switched on ?</mark>

\- You go <mark style="color:orange;">\[Windows Security]</mark> - <mark style="color:orange;">\[Viruss & threat protection]</mark> sections <mark style="color:orange;">\[Viruss & threat protection settings]</mark> select <mark style="color:orange;">\[Manage settings]</mark> Turn off all .\
**-** Go <mark style="color:orange;">\[App & Bowser control]</mark> - Select <mark style="color:orange;">\[Reputation based protection setting</mark>] - Turn off all .

### <mark style="color:yellow;">How do I enable kill aura ?</mark>

\- Go to \[Setting] enable dangerous function , after enabling it will show up at Item <mark style="color:red;">\[World]</mark>&#x20;

### <mark style="color:yellow;">ERROR ManualMap: Failed to initialize static TLS for image. Error: 0</mark>

Download these 2 files : [Driver](https://drive.google.com/drive/folders/1LkP66KHFBcu3IVi6AxCdj7JU5Vrx4H7n?usp=sharing)\
After downloading please coppy 2 this folder into akebi folder

### <mark style="color:yellow;">Why can't I download akebi ?</mark>

IF you download this link : [http://akebi-private.com/uploads/AkebiPrivate.zip](http://akebi-private.com/uploads/AkebiPrivate.zip)

you may not be able to download first you try using VPN (there will be some countries it will not support download) or change to mega .

Link mega example : [https://mega.nz](https://mega.nz/file/tb0lCSKL#9pvRkl4hWRUvaUb-jk1vp1tIyQfu1dqLteH3KMYlKm0)

If you stick the password request please change the browser and reload .

### <mark style="color:red;">For those who have tried the above ways and still can not, please reinstall the window</mark>

Download link WIn 10 iso: [here](https://support.microsoft.com/en-us/windows/create-an-iso-file-for-windows-10-38547366-1dcb-7afd-1726-9eb222d72705)&#x20;

Download link WIn 11 iso: here

### <mark style="color:yellow;">What is a download Link for people with launch problems ?</mark>

For those who do not run files as usual If you want to use this File, do the following steps\
Go in <mark style="color:orange;">\[Windows Security]</mark> - <mark style="color:orange;">\[Viruss & threat protection]</mark> sections <mark style="color:orange;">\[Viruss & threat protection settings]</mark> select <mark style="color:orange;">\[Manage settings</mark>] Turn off all .

* Selects Exclusions <mark style="color:orange;">\[ add or remove Exclusions]</mark> Select Folder , Select the folder section , select the folder akebi (this selection will ignore almost the firewall to let the file run and do not need to turn off anything more) as I understand the fins .&#x20;

</details>

<details>

<summary>Questions You May Need</summary>

## <mark style="color:yellow;">How To Safe ?</mark>

* The advice for you guys is to keep the delay range 20m, 30m, don't touch it.
* Don't go to other people's Worlds <mark style="color:blue;">(friends, bth)</mark> if it doesn't have RP or Lo UID Whether it is safe or not is a matter of chance, there is no cheat that is 100% safe except for 1 house but has few features.

## <mark style="color:yellow;">How to get File TP ?</mark>

Here : [Click](https://discord.com/channels/1104940962804936856/1231627318380859514)

### <mark style="color:yellow;">How do I enable kill aura ?</mark>

* Go to ![](<../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)
* &#x20;![](<../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1).png>) **Enable** dangerous function , after enabling it will show up at  .<img src="../.gitbook/assets/image (3) (1) (1) (1) (1).png" alt="" data-size="original">
* Enable :
* &#x20;![](<../.gitbook/assets/image (4) (1) (1).png>)
* value to 300-500k dmg ( crash dmg  mode )
* Or enable ![](<../.gitbook/assets/image (29).png>)

### <mark style="color:yellow;">How do I turn on the interactive map?</mark>

* Open the map - Look at the left corner of the map. The word sync map will appear .
* Just pull it out like a menu .

### <mark style="color:yellow;">Why isn't my auto-challenge working?</mark>

* Turn off no clip  .
* Check the operating range and if it's too far, run along the path until it gets it .

### <mark style="color:yellow;">Why can't you solve the puzzle yourself?</mark>

* It will do whatever is in the filter .
* Otherwise, understand .

### <mark style="color:yellow;">The shows info do nothing?</mark>

* Because the AKEBI interface has been updated, you want to see the information panel .
* Go to TP section ![](<../.gitbook/assets/image (17).png>) Press the eye icon to display .
* The function display panel is similar .

### <mark style="color:yellow;">Why is my Menu so small? How can I make it as big as the video?</mark>

* When you open the menu, look at the right corner of the menu and you will see this <img src="../.gitbook/assets/image (23).png" alt="" data-size="line"> scale here&#x20;

### <mark style="color:yellow;">How can I see the description of that feature and what effect it has?</mark>

* Point your mouse on this icon![](<../.gitbook/assets/image (22).png>)it will describe the function for you.

### <mark style="color:yellow;">How to display file extensions like json, exe etc!</mark>

* File .json (for those who don't see it ) - go to the teleports folder press View-go to the show section and select File name extension :
*

    <figure><img src="../.gitbook/assets/Screenshot 2023-10-03 132433.png" alt=""><figcaption></figcaption></figure>

<img src="../.gitbook/assets/image (18).png" alt="" data-size="original">

</details>
