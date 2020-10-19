# Steps to run

	- Open a terminal with and switch to root
		```shell
			$ sudo su
		```
	- Run following to watch udp packets
		```shell
			$ tcpdump -n -vv  udp port 8622 -w packet.pcap
		```
	- Open another terminal with sudo access and run the c program
		```shell
			$ ./udp
		```
*** Only work in Unix based OS environment
