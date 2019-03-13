# ip-monitor
A quick script for IP address monitoring, email notifications and DNS updates

To install:
 - Drop both of the bash scripts here into ~/bin
 - make a ~/.wanip folder and add a `ddns.conf` file, configured with any DNS entries you want updated similar to the example
 - add a crontab entry similar to the example

This assumes that you already have your local email server and mutt configured to send emails however you like.
The DNS record update method and url are specific to domains using namecheap.com as a DNS service. It's probably reasonably easy to revise for most other DNS servers and their particular protocols.
