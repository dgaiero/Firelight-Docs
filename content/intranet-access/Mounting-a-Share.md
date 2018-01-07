<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.1/css/font-awesome.min.css">

# How to mount a network share

## Local Network
To mount a network share on the local network, there are a couple of setup steps that you must follow first.


  1. In an elevated command prompt, enter the following command: `fsutil behavior set SymlinkEvaluation R2R:1`
  2. Press the windows start button <font face=Wingdings>&#xff;</font>.
  3. Click Start <i class="fa fa-windows" aria-hidden="true"></i> , click All Programs, and then click Accessories.
  4. Right-click Command prompt, and then click Run as administrator.
  5. If the User Account Control dialog box appears, confirm that the action it displays is what you want, and then click Continue.
  6. In the command prompt, type `fsutil behavior set SymlinkEvaluation R2R:1`. This command allows Remote to Remote symlinks on your system. This is only needed if you are mounting on the local network. For more information about symbolic link (symlinks), <a href="https://en.wikipedia.org/wiki/Symbolic_link">click here</a>.
  7.

## From the internet
