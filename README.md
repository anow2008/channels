wget -O /tmp/channels.tar.gz https://raw.githubusercontent.com/anow2008/channels/main/channels.tar.gz

wget -O /tmp/channels.tar.gz https://raw.githubusercontent.com/anow2008/channels/main/channels.tar.gz && tar -xzf /tmp/channels.tar.gz -C /tmp && cp -r /tmp/* /etc/enigma2/ && init 4 && sleep 2 && init 3
