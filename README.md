## wlanscan

Scan for wireless networks and print the results in JSON format. Uses go-wireless to scan for networks. This is a simple tool to help with debugging and development and research reasons. I am using it to scan and send parsed results to influxdb for quality metrics.

I needed a universal interface to the scan which `iw <iface> scan` does not provide.s


### Usage
```
./wlanscan
```
