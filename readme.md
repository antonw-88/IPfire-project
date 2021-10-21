Project for setting up an IPfire system in front of internal network, and to add private backupserver etc.

Structure of servers:
#IPfire proxy - Elitebook 2560p
-Suricata IDS
-Tripwire signature database
-DNSSEC
-Firewall config - tbd

#Backup server - Elitebook 2560p  
-Only ssh open on custom port(2022?)  
-Tripwire signature database  
-SElinux  
-CEPH single node cluster(for learning purposes...)  
https://technologyrss.com/how-to-install-ceph-cluster-on-centos-7-using-single-server/
