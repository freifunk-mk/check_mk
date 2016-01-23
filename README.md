# check_mk
```
sudo wget -O /usr/lib/check_mk_agent/local/supernode https://raw.githubusercontent.com/freifunk-mk/check_mk/master/supernode
sudo chmod +X /usr/lib/check_mk_agent/local/supernode
```
##Abhängigkeiten
fastd-statistics: https://github.com/ffrl/ff-tools/blob/ad0f6bef5da0bd75e650ce91565c0e208a8dbab1/fastd/fastd-statistics.py in /etc/fastd
```
sudo wget -O /etc/fastd/fastd-statistics.py https://raw.githubusercontent.com/ffrl/ff-tools/ad0f6bef5da0bd75e650ce91565c0e208a8dbab1/fastd/fastd-statistics.py
sudo chmod +X /etc/fastd/fastd-statistics.py
```

Komplettlösung mit rootrechten:
```
wget -O ~/cmi https://raw.githubusercontent.com/freifunk-mk/check_mk/master/installscript && chmod +X ~/cmi && ~/cmi
```
