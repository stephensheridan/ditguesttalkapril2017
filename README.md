# ditguesttalkapril2017
Guest talk on DNS-based covert channels - DIT April 3rd 2017

In order to setup and DNS covert channel you will need to:

1. Setup a server with a public IP (check out okeanos-global.grnet.gr). This server will run the server side of the IODINE software.
2. Setup DNS records using something like freedns. You will need to setup an A and NS record. Check out the IODINE docs
3. Install IODINE on you client and server machine.
4. Run the IODINE server and client.
5. Proxy web traffic throug the DNS tunnel or just FTP data out over the connect.
6. :-)
