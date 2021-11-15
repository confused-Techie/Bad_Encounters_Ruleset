# Reasoning for these blocked Ips

## Malicious IP Likely Word Press Exploits SID: 800010000

Collection of IP's attempting to take advantage of Word Press Vulnerabilities of Public Resources

IP: 172.70.143.44 || Source-Port: 59650 || https_url: //wordpress/xp-includes/wlwmanifest.xml

IP: 172.70.142.145 || Source-Port: 16592 || https_url: //wordpress/wp-includes/wlwmanifest.xml

IP: 52.162.241.82 || Source-Port: na || https_url: na 

## Malicious IP Likely Request Hidden Environment Info SID: 800020000

Collection of IP's scanning public resources in an attempt to request hidden environment files.

IP: 104.248.125.15 || Source-Port: 36014 || https_url: ./env

IP: 108.162.215.165 || Source-Port: 43428 || https_url: ./env  

IP: 172.69.34.231 || Source-Port: 41946 || https_url: ./env  

IP: 172.69.62.197 || Source-Port: 33094 || https_url: /.env

IP: 172.70.34.169 || Source-Port: 32996 || https_url: /.env

IP: 172.70.98.157 || Source-Port: 46044 || https_url: /.env

IP: 172.70.98.169 || Source-Port: 42464 || https_url: /.env

IP: 185.254.31.134 || Source-Port: 49144 || https_url: /.env


## Malicious IP Likely Attempted Information Leak SID: 800030000

Collection of IP's attempting to obtain information they shouldn't from public resources.

IP: 165.227.144.245 || Source-Port: 22656 || https_url: /_ignition/execute-solution || user_agent: python-requests/2.26.0

IP: 172.69.62.102 || Source-Port: 62472 || https_url: /vendor/phpunit/phpunit/src/Util/PHP/666.php || user_agent: python-requests/2.26.0

IP: 172.69.62.197 || Source-Port: 33094 || https_url: /.env || user_agent: python-requests/2.26.0 || ALERT: This IP is also listed in SID 800020000 so is not within this rule. But based on User Agent should also be noted.

IP: 172.70.134.103 || Source-Port: 46540 || https_url: /vendor/phpunit/phpunit/src/Util/PHP/666.php || user_agent: python-requests/2.26.0

IP: 172.70.34.169 || Source-Port: 41232 || https_url: /vendor/phpunit/phpunit/src/Util/PHP/666.php || user_agent: python-requests/2.26.0 || ALERT: This IP is also listed in SID 800020000 so is not within this rule. But also does apply.

IP: 172.70.34.173 || Source-Port: 59276 || https_url: /vendor/phpunit/phpunit/src/Util/PHP/666.php || user_agent: python-requests/2.26.0

## Malicious IP Likely Shell Command Execution SID: 80040000

Collection of IP's attempting to execute Shell Command Attack

IP: 45.146.164.110 || Source-Port: 52144 || https_url: /cgi-bin/.%2e/.%2e/.%2e/.%2e/bin/sh
