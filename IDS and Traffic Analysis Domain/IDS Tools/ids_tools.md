# Analyze Traffic

## tcpdump Cheat Sheet

* http://packetlife.net/media/library/12/tcpdump.pdf

## Analyze Traffic w/ Wireshark

* Introduction to Wireshark: Sample Traffic Analysis - Book 1, Page 49

### Loading Wireshark

```
wireshark
wireshark [pcap file]
```

### Profiling a pcap

Wireshark's "Statistics" menu items serve as a great starting point when jumping into a pcap.  

```
Statistics > Protocol Hierarchy
```

![Protocol Hierarchy](/analyze-traffic-wireshark-statistics.PNG?raw=true "Protocol Hierarchy")

### Finding a packet

```
Edit > Find Packet ... (or Ctrl + F)
```

It's a good idea to select the radio button "Packet bytes" in order to search for the string or hex value within the payload.

![Find Packet](/analyze-traffic-find-packet.PNG?raw=true "Find Packet")

Change...