# RaspberryPI


# Install updated nodejs on Raspbian
apt-get remove --purge node* npm*
curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
apt-get install nodejs -y
