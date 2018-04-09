# CovertRates
A project to implement research found at https://www.trustwave.com/Resources/SpiderLabs-Blog/Smuggler---An-interactive-802-11-wireless-shell-without-the-need-for-authentication-or-association/
Basically, run a listener on a remote machine, and use the sender to send data/commands/whatever via 802.11 wireless. The listener looks for a specific frame with a specific SSID an RTS field that has been modified to suit our needs. The sender decodes the data (if it's been encoded), and displays or runs it.
Useful for funky exfiltration or command and control via non TCP/IP channel. Neither host need to be joined to a wireless network or anything else for that matter.
