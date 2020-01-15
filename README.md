# emailExtract
Simple script to extract emails and their attachments from PCAP files, written in bash for Linux analysis machines.

Written to automate the extraction of emails and attachments from trigger PCAPs containing possible malicious emails.

Uses tcpflow to extract emails and munpack to extract attachments.

Has built in dependancy checker which installs these tools if necessary.

Can be run against a single PCAP or a directory containing multiple PCAPS.

Just download the script and either drop it into your /usr/local/bin or add it to a custom script location and update /etc/environment with the location of your custom script directory. You may also need to give it execute permissions with sudo chmod +x emailExtract.

single pcap: emailExtract -f <pcap>

 multiple pcaps: emailExtract -d <dir>
