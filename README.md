# CNT5106C_Peer_To_Peer_File_Sharing_System
Computer Networks (CNT5106C UF) Course Project - Fall 2020

Build a P2P file-sharing application similar to BitTorrent protocol in Java.
File distribution with choking and unchoking mechanism among peers using TCP (reliable transport layer protocol).
Group Number: 12
Group members: (i) Kratika Singhal, UF ID:6953-5971 (ii) Suprith Reddy Gurudu, UF ID:9961-2134 (iii) Akshay Kumar, UF ID:4679-9946
How to execute the project:

open the terminal (in lin114-00 to lin114-08 lab servers)
change the directory to the project folder
run the 'make' command as shown below (compiles java files and creates class files)
make

run the below command to start the remote peers
java RemotePeerInitiator

Note: If the above command does not work, i.e., unable to start peers, we need to start the peers manually each in separate terminal as shown below

java peerProcess PeerID

PeerID ranges from 1001 to 1009 in this context of configuration files

Please find the log files in the 'logs' folder.
