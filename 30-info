#!/bin/bash

echo  "Public IP: `curl ifconfig.me`"
echo -n  "Latency to Google:`ping -W 1 -i 0.2 -c 2 8.8.8.8 -q | grep round | cut -d "=" -f 2 | cut -d "/" -f 1`"
echo -n -e "\t"
echo -n -e  "Latency to H-network.nl:`ping -W 1 -i 0.2 -c 2 h-network.nl -q | grep round | cut -d "=" -f 2 | cut -d "/" -f 1`"
echo -n -e "\t"
echo -n -e  "Latency to HB-L.nl:`ping -W 1 -i 0.2 -c 2 hb-l.nl -q | grep round | cut -d "=" -f 2 | cut -d "/" -f 1`"
echo ""
