# linux-one-liners
Extremely useful linux one liners. Use [Explainshell](https://explainshell.com/) if you do not understand these commands. Made and tested on AlmaLinux 8.6 (Sky Tiger).

# Apache 10 top visitors
Find the 10 most IP-addresses making requests to your apache webserver <br />
`awk '{ print $1}' /var/log/httpd/access_log | sort | uniq -c | sort -n` <br />
