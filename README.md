# VPN

Bare Bones (PPTP) VPN Installer for CentOS
See [http://drewsymo.com/networking/vpn/install-ptpp/](http://drewsymo.com/networking/vpn/install-ptpp/) for more information.

## Installation

To get started with your own secure VPN, simply execute the following commands at your servers command-line:

	$ yum install -y git
	$ cd /opt && git clone git://github.com/xavixie/VPN.git
	$ cd VPN && bash vpn-setup-vanilla.sh

If you're on Linode, you can simply rebuild your instance with the `PPTP VPN Installer` [stackscript](http://www.linode.com/stackscripts/view/?StackScriptID=6346).

## Author

**Drew Morris**

+ [Blog](http://drewsymo.com)
+ [Twitter](http://twitter.com/drewsymo)
+ [Google+](https://plus.google.com/u/0/114153589610660530694)

## Recommended Providers

+ [Fastdot Cloud VPS Hosting](http://fastdot.com) (Australia, Asia-Pacific, UK, USA)
+ [AUSWEB VMware Hosting](http://www.ausweb.com.au) (Australia)