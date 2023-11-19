# UPDATE UNTUK DEBIAN
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot

# UPDATE UNTUK UBUNTU
apt update && apt upgrade -y && update-grub && sleep 2 && reboot

### Link Install 
<pre><code>apt install -y wget screen && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/wingshope/Newbie/main/setup.sh && chmod +x setup.sh && screen -S install ./setup.sh</code></pre>

### ATAU
<pre><code>wget --no-check-certificate https://raw.githubusercontent.com/wingshope/Newbie/main/setup.sh && chmod +x setup.sh && ./setup.sh</code></pre>
