# Install Shadowsocks
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/3071874230718742/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

# Install BBR
wget --no-check-certificate https://raw.githubusercontent.com/3071874230718742/shadowsocks_install/master/bbr.sh
chmod +x bbr.sh
./bbr.sh
