# emailExtract
Simple script to extract emails and their attachments from PCAP files, written in bash.

Written to automate the extraction of emails and attachments form trigger PCAPs containing possible malicious emails.

Uses tcpflow to extract emails and munpack to extract attachments.

Has built in dependancy checker which installs these tools if necessary.

Can be run against a single PCAP or a directory containing multiple PCAPS.

