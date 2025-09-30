# Capture-and-Analyze-Network-Traffic-Using-Wireshark
Capture live network traffic, identify different protocols, export the capture, and summarize the findings.

## Steps Performed


Started Packet Capture
Opened Wireshark and began capturing on the active network interface.

Generated Network Traffic
Traffic was created by browsing/pinging during the capture window.

Stopped Capture After ~1 Minute
The capture was manually stopped after approximately one minute.

Filtered Packets by Protocol
Filters were applied using the Wireshark filter bar:

tcp
icmp
tls


Identified Protocols
At least three different protocols were observed in the capture:

TCP

ICMP

TLS

Exported the Capture File
The capture was saved as a .pcapng file:

task5.pcapng


## Summary of Findings

The capture contained packets generated from browsing/pinging activity.

TCP was used for transport and connections.

ICMP appeared due to ping requests/replies.

TLS packets were present due to encrypted HTTPS traffic.

The .pcapng file contains all recorded packets for further analysis.

Outcome

This task provided hands-on experience with packet capturing and improved protocol awareness using Wireshark.
