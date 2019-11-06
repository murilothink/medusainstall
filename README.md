############## Esses são os pacotes para a instalação do Medusa, caso dê erro, tire alguns pacotes. ############

sudo apt-get install build-essential make patch subversion openssl libssl-dev libncp-dev libpq-dev libgcrypt11-dev libgnutls-dev libsvn-dev zlib1g-dev libssh2-1-dev libnl-dev gettext autoconf tcl8.5 libpcap0.8-dev python-scapy python-dev cracklib-runtime macchanger-gtk tshark ethtool

############# Agora Faça o Download ##############

tar -xvf [nome do arquivo]

./configure
make
make install 

http://foofus.net/goons/jmk/medusa/medusa.html

######### Em caso de erro baixe diretamente ############3

sudo apt-get install medusa 


