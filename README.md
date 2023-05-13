# MSCTUD_DNS-over-TLS_Dataset

Dataset part of research project to detect DNS tunnelling over a DoT encrypted link using Machine Learning Algorthms.

![Network Topology](https://github.com/heff09/MSCTUD_DNS-over-TLS/assets/41806354/878bb0fc-f3d6-4b4a-bd3f-6dc2aef7052e)

Iodine, DNSteal and PowerDNS DNS tunnelling tools used to establish connections to a malicious server hosted in 
the cloud, transmitting web traffic, Data exfiltration and datainfiltration through a DNS-over-TLS encrypted tunnel to Google Public DNS resolver.

Flows extracted using Tranalyzer2 and CICFlowmeter feature extraction tools from multiple network captures defined by scenarios being investigated.

Dataset comprises:
==================
Tranalyzer2 extracted flows and statistical information, 101 raw features saved to each csv file.

CICFlowmeter extracted flows and statistical information, 84 raw features saved to each csv file.

Original PCAP files with TCP port 853 TLS traffic
