## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

### Installation
Run the script and follow the assistant:

`wget https://raw.githubusercontent.com/own3mall/openvpn-install/master/openvpn-install.sh -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

### Command line parameters

After you have used this script to install openvpn, you can also pass in command-line arguments to automate or silently do things. 

Parameters are:

`silent` (doesn't echo out anything that isn't important)

`unattended` (allows you to skip over sections provided required parameters are passed in)

`option=1` (send in 1-4 - 1 is add, 2 is remove, 3 is uninstall openvpn, 4 is exit) 

`client=nameofclient` (name of client you want to revoke or add)

### I want to run my own VPN but don't have a server for that
You can get a little VPS for just $2.99/month at [Bandwagon Host](https://bandwagonhost.com/aff.php?aff=575&pid=43).

### Donations

If you want to show your appreciation, you can donate via [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VBAYDL34Z7J6L) or [Bitcoin](https://pastebin.com/raw/M2JJpQpC). Thanks!
