wget -O /tmp/channels.tar.gz https://raw.githubusercontent.com/anow2008/channels/main/channels.tar.gz && tar -xzf /tmp/channels.tar.gz --strip-components=1 -C / && wget -qO - http://127.0.0.1/web/servicelistreload?mode=0 && rm -f /tmp/channels.tar.gz

wget --no-check-certificate -O /tmp/channels.tar.gz https://raw.githubusercontent.com/anow2008/channels/main/channels.tar.gz && \
rm -rf /etc/enigma2/userbouquet.* && rm -rf /etc/enigma2/lamedb && \
tar -xzf /tmp/channels.tar.gz -C /tmp && \
cp -rf /tmp/etc/enigma2/* /etc/enigma2/ && \
wget -qO - http://127.0.0.1/web/servicelistreload?mode=0 && \
rm -f /tmp/channels.tar.gz && rm -rf /tmp/etc && echo "Done! Channels Updated Like AJPanel"
