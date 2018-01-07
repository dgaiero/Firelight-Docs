<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.1/css/font-awesome.min.css">

# How to mount a network share

## Local Network
To mount a network share on the local network, there are a couple of setup steps that you must follow first.


  1. In an elevated command prompt, enter the following command: `fsutil behavior set SymlinkEvaluation R2R:1`
    3. Click Start <i class="fa fa-windows" aria-hidden="true"></i> , click All Programs, and then click Accessories.
    4. Right-click Command prompt, and then click Run as administrator.
    5. If the User Account Control dialog box appears, confirm that the action it displays is what you want, and then click Continue.
    6. In the command prompt, type `fsutil behavior set SymlinkEvaluation R2R:1`. This command allows Remote to Remote symlinks on your system. This is only needed if you are mounting on the local network. For more information about symbolic link (symlinks), <a href="https://en.wikipedia.org/wiki/Symbolic_link">click here</a>.
  2. Open **File Explorer** from the taskbar or the **Start <i class="fa fa-windows" aria-hidden="true"></i>** menu, or press the **Windows logo key <i class="fa fa-windows" aria-hidden="true"></i> + E**.
  3. Select **This PC** from the left pane. Then, on the **Computer** tab, select **Map network drive**.
  <img src="https://static.fire-light.us/docs.fire-light.us/images/shareMount/myPC_mountShare.png">
  4. On the next screen, it is not necessary to select a particular drive letter, but it is recommended to select `X:`. For the folder, type `\\winserver1\serverData`.
  5. Make sure **Reconnect at sign-in** is checked and **connect using different credentials** is unchecked.
  <img src="https://static.fire-light.us/docs.fire-light.us/images/shareMount/mapNetworkDriveLetterPage.png">
## From the internet
2. Open **File Explorer** from the taskbar or the **Start <i class="fa fa-windows" aria-hidden="true"></i>** menu, or press the **Windows logo key <i class="fa fa-windows" aria-hidden="true"></i> + E**.
3. Select **This PC** from the left pane. Then, on the **Computer** tab, select **Map network drive**.
<img src="https://static.fire-light.us/docs.fire-light.us/images/shareMount/myPC_mountShare.png">
4. On the next screen, it is not necessary to select a particular drive letter, but it is recommended to select `X:`. For the folder, type `\\serverdata.fire-light.us@ssl\DavWWWRoot\data`.
5. Make sure **Reconnect at sign-in** is checked and **connect using different credentials** is unchecked.
<img src="https://static.fire-light.us/docs.fire-light.us/images/shareMount/mapNetworkDriveLetterPageInternet.png">.
5. When using this system, it may require you to input your username and password when opening files (specifically, Microsoft Office files). Enter your username with the `AD\` portion.
