# MSCTUD_DNS-over-TLS_Dataset
![My Image](images/Network Topology.png)
Dataset part of Research project to Detect tunnelling over DoT-encrypted links using Machine learning Algorthms.

Iodine, DNSteal and PowerDNS DNS tunnelling tools used to establish connections to a malicious server hosted in 
the cloud, transmitting  through a Dns-over-TLS encrypted tunnel to Google Public DNS resolver.

Flows extracted using Tranalyzer2 and CICFlowmeter feature extraction tools from multiple network captures defined by scenarios being investigated.

Dataset comprises:
==================
Original PCAP files with TCP port 853 TLS traffic

Tranalyzer2 extracted Flow and statistical information, 101 features saved to each csv file.

CICFlowmeter extracted Flows and statistical information, 84 features saved to each csv file.
