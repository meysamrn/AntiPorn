# AntiPorn
AntiPorn - Blocking Porno Sites. Wait for more...

# Anti Porn HOSTS File
The purpose of this repository is to distribute a useful mean to fight porn addiction.

If you are willing to improve your life and get rid of porn addiction then Google [`@NoFap`](https://en.wikipedia.org/wiki/NoFap)

## What's the HOSTS file and how it can prevent access to porn sites?
HOSTS file contains the mappings of IP addresses to host names.

With HOSTS file we can prevent our browser to access porn sites.

## What's so special about this repository?
HOSTS.txt contains a huge list of porn sites (probably the biggest list you can find on the Internet).

Just by copy-pasting its content on your machine's HOSTS file enables the blocking mechanism.

## HOSTS in Windows 7/8.x/10
1. Right mouse click on Notepad icon then click on `Run as administrator`
2. File → Open... then insert the path `C:\windows\system32\drivers\etc\hosts`
3. Add a new line and copy-paste the entire content of HOSTS.txt
4. Save
5. Reboot
### Using Cygwin
1. Open HOSTS.txt and add a newline to the beginning
1. Save and close HOSTS.txt
1. Right mouse click on Cygwin icon then click on 'Run as adminstrator`
2. `cd` to where HOSTS.txt lives
3. Run this command in Cygwin: `cat HOSTS.txt >> /cygdrive/c/Windows/System32/drivers/etc/hosts`
4. Reboot

The steps in Cygwin should be similar on in any POSIX compatible system running on Windows.

## HOSTS in Linux and macOS
1. Open the terminal
2. Type `sudo vim /etc/hosts`
3. Add a new line and copy-paste the entire content of HOSTS.txt
4. Save
5. Reboot

## HOSTS in Android (method #1)
1. Install [Hosts Go](https://play.google.com/store/apps/details?id=dns.hosts.server.change.vip)
2. Download "HOSTS.txt" and put it somewhere inside your phone
3. Open [Hosts Go](https://play.google.com/store/apps/details?id=dns.hosts.server.change.vip)
4. Click on HOSTS EDITOR button
5. Click on three dots top-right corner
6. Import HOSTS file you previously downloaded
7. Go back and START

## HOSTS in Android (method #2)
1. Install [DNS66](https://github.com/julian-klode/dns66#installing)
2. Open [DNS66](https://github.com/julian-klode/dns66#installing)
3. Click on HOSTS button to select the "HOSTS" section of the APP
4. Click on the + floating button on the lower-right corner
5. Insert a title of your choice and the following url: hhttps://raw.githubusercontent.com/Anlominus/AntiPorn/main/PornHosts
6. Save the filter you created by clicking the check mark on the top-right corner
7. Press the refresh button on the top-right corner
8. Go back to the "START" section of the APP and start it
9. You should notice a symbol indicating an active VPN on your Android system

## Make a promise
Once the mechanism is in place and working, do not disable it.

If you disable it on demand to watch porns then you defeat the very purpose of it, but more than that you betray yourself.

## Contribute

Become an open source contributor in 7 steps (_it takes less than 30 minutes_):
1. Fork this repository
2. Clone the repository into your PC
3. Create a new branch
4. Change whatever you think it has to be improved
5. Commit your changes
6. Push your changes to GitHub
7. Submit a PR

Your changes **won't be visible immediately**; first they have to be merged by the project maintainer.

## Donation
If you feel like you want to donate something

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3UN95QQCD4B7E)

- Sources: [Anti-Porn-HOSTS-File](https://github.com/4skinSkywalker/Anti-Porn-HOSTS-File)
