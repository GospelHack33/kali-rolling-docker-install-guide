# kali-rolling-docker-install-guide
Install Kali Linux ( Docker Build )

sudo docker pull kalilinux/kali-rolling

sudo docker run --network=pentest -h attacker -it --rm --name kalibox kalilinux/kali-rolling

apt update && apt upgrade -y 

apt install kali-linux-headless -y
