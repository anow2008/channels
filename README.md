wget -O /tmp/channels.tar.gz https://raw.githubusercontent.com/anow2008/channels/main/channels.tar.gz

wget -O /tmp/channels.tar.gz https://raw.githubusercontent.com/anow2008/channels/main/channels.tar.gz && tar -xzf /tmp/channels.tar.gz --strip-components=1 -C / && wget -qO - http://127.0.0.1/web/servicelistreload?mode=0 && rm -f /tmp/channels.tar.gz
