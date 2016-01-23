# check_mk
```
wget -O /usr/lib/check_mk_agent/local/supernode https://raw.githubusercontent.com/freifunk-mk/check_mk/master/supernode && sudo chmod +X /usr/lib/check_mk_agent/local/supernode && wget -O /etc/fastd/fastd-statistics.py https://raw.githubusercontent.com/ffrl/ff-tools/ad0f6bef5da0bd75e650ce91565c0e208a8dbab1/fastd/fastd-statistics.py && chmod +X /etc/fastd/fastd-statistics.py
```
##Abhängigkeiten
fastd-statistics: https://github.com/ffrl/ff-tools/blob/ad0f6bef5da0bd75e650ce91565c0e208a8dbab1/fastd/fastd-statistics.py in /etc/fastd
