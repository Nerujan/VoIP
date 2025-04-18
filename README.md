# VoIP
VoIP System using Asterisk and Linphone
This project sets up a basic VoIP system with internal calling, a conference room, and SIP-based messaging between users using Asterisk and Linphone.

Install Asterisk:
<pre>sudo apt update
sudo apt install asterisk -y</pre>  

Copy project config files:
<pre>sudo cp sip.conf /etc/asterisk/
sudo cp extensions.conf /etc/asterisk/</pre>
* you can add the users in sip.conf file & add extentions to extensions.conf also

Reload Asterisk:
<pre>sudo systemctl restart asterisk </pre>

Start Asterisk in CLI: 
<pre>sudo asterisk -rvv </pre>

