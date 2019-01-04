# Noip_installation
Font: https://www.noip.com/support/knowledgebase/installing-the-linux-dynamic-update-client-on-ubuntu/
User: Vincenzo Pinto
Date: 04-01-2019
#########################

1.  Create an account on https://www.noip.com/
2.  Create an hostname with his public address
3.  Enter on your machine
4.  Work as "root"
5.  cd /usr/local/src/
6.  wget http://www.no-ip.com/client/linux/noip-duc-linux.tar.gz
7.  tar xf noip-duc-linux.tar.gz
8.  cd noip-2.1.9-1/
9.  make install
10. /usr/local/bin/noip2 -C
11. /usr/local/bin/noip2
12. nano /etc/hosts (insert the hostname of noip)
13. nano /etc/hostname (insert the hostname of noip)
14. reboot

Now, you can access into the machine from his noip-hostname.
