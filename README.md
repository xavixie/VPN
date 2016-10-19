# VPN

Bare Bones (PPTP) VPN Installer for CentOS

## Installation

To get started with your own secure VPN, simply execute the following commands at your servers command-line:

	$ yum install -y git
	$ cd /opt && git clone git://github.com/xavixie/VPN.git
	$ cd VPN && bash vpn-setup-vanilla.sh

If you're on Linode, you can simply rebuild your instance with the `PPTP VPN Installer` [stackscript](http://www.linode.com/stackscripts/view/?StackScriptID=6346).

ssh root@IP
cat /etc/ppp/chap-secrets
bash md_vpn.sh


################
finalspeed:

chmod +x /etc/rc.local
vi /etc/rc.local
加入
sh /fs/start.sh

crontab -e
加入
0 3 * * * sh /fs/restart.sh


sh /fs/restart.sh; tail -f /fs/server.log