# kali-rolling-docker-install-guide
<b style='color:darkblue'>Install Kali Linux ( Docker Build )</b>

sudo docker network create pentest

sudo docker pull kalilinux/kali-rolling

sudo docker run --network=pentest -h attacker -it --rm --name kalibox kalilinux/kali-rolling

apt update && apt upgrade -y 

apt install kali-linux-headless -y
