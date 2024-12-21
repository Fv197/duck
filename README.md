# duck

A bash script for updating the IP address for a given domain at duckdns.org

## Desciption

* Verifies internet connectivity
* Retrives IP-address 
* If needed, updates IP-address
* Logs to given log

## Instructions

1. Update variables `domain`, `token` and `log_file` if needed
2. Place duck in a binary directory (`/usr/local/bin`)
3. Modify permissions with `sudo chmod 700 /usr/local/bin/duck`
4. Edit crontab with `sudo crontab -e` and add the line `*/5 * * * * /usr/local/bin/duck`

This will run the script every 5 minuttes
