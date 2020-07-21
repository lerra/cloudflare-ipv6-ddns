# cloudflare-ipv6-ddns
## Use case
My dyndns client did not support to update cloudflare AAAA (ipv6) records at cloudflare. I found a script that did not work on my ubuntu 18.04 setup so I modified it to work, its also been tested on ubuntu 20.04

## How to use it
Check config parameters in the top of the update-v6-cloudflare file, change them and make it executable (chmod +x update-v6-cloudflare) and put it in a prefered path (eg /usr/local/bin) and then put it to your crontab. 


## Creds
https://github.com/billkit/cloudflare-DDNS/blob/bc67f68f09abcecb56ef1cbbb087bd993a7244d9/cloudflare-v6.sh
