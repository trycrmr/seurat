# SEURAT 
( pronounced "sue-rot" after this artist and his work https://en.wikipedia.org/wiki/Georges_Seurat )

Artistically depicting network traffic.

No working releases yet.

## CONTRIBUTE
1) Install the randpkt utility. This might require building wireshark from source (https://www.wireshark.org/docs/wsug_html_chunked/ChBuildInstallUnixBuild.html). This utility is used to generate fake network traffic to use to iterate over developing visualizations stored as pcap files. 
2) Install the [tshark utility](https://www.wireshark.org/docs/man-pages/tshark.html). This will be used to convert pcap output and files to json. 
3) Run the following command (well, technically two commands) to create a pcap file and convert it to json: `randpkt -r fake-packets.pcap && tshark -r fake-packets.pcap -T json >> fake-packets.json` This is how we will generate some fake network packets to visualize. Note that the goal with Seurat is to visualize live network traffic, however, these instructions presume capturing packets on your network for development purposes would be inappropriate.
...to be continued.

## INSTALL
TBD
