/*
Title: Initial Account Setup
sort: 1
*/

# How to setup your account.

Once an account has been provisioned for you, you should receive an email. If you do not receive an email, please contact [webmaster@fire-light.us](mailto:webmaster@fire-light.us).

The email will look something like the following:

```Text
Dear John,

An account has been made for you on winserver1 on AD network ad.fire-light.us. To finish setup of your account, please visit https://uac.fire-light.us to set your password. To use this site, you must login with your username and domain (AD\jrdoe). Once you login, click reset password, and type your current password, given below and the new password of your choice.

Your initial credentials are:

Domain	Username	Password
AD        jrdoe       @38aeec86115d12e0290f69744521f15318b951b1

Your user folder is available through the UNC path: \\winserver1\NGUsers\jrdoe. You can access this folder directly on any intranet connected computer. If you are on the external network, you will need to use RDP and the gateway server. For more information visit (Coming Soon) https://docs.fire-light.us/rdp/setup. Your user folder name can be identified by your account ID: jrdoe.

Thank you,

AD
```

# The Password Reset Process
To setup your account, visit https://uac.fire-light.us.

This website will redirect to https://fs.fire-light.us. You will be prompted with a login screen, as shown below:

<img src="https://static.fire-light.us/docs.fire-light.us/images/AccountSetup/ADFS_SSO_Initial_Filled.png" width="200">

- For username where it says `someone@example.com`, fill in your username. For example, someone with the name of `John R. Doe` would have a username of `AD\jrdoe`. Your username will typically be your first initial, middle initial and last name.\
- At this point, you will be redirected back to https://uac.fire-light.us. You should see `Welcome John` (or your first name). If you do not, sign-out and email [connect@fire-light.us](mailto:connect@fire-light.us).
- At this point, click on the Reset password button, shown below.

<img src="https://static.fire-light.us/docs.fire-light.us/images/AccountSetup/resetPasswordButton.png" width="200">

- On this page, **make sure** that the username is yours and `You are currently logged in as: jrdoe@ad.fire-light.us` is your username at `ad.fire-light.us`.

<img src="https://static.fire-light.us/docs.fire-light.us/images/AccountSetup/resetPasswordInfo.PNG" width="400">

You may recieve an error if you did not eneter the correct old password or the system rejected your password.
Any other error should never happen, so if you come accross one, please email [connect@fire-light.us](mailto:connect@fire-light.us).
