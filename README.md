nagios-checks
=============

Various Nagios check scripts

check_haproxy
-------------

checks haproxy stats and reports errors if any of the servers for a proxy are down

    Usage: check_haproxy.rb [options]

    Specific options:
	-u, --url URL                    csv-formatted stats URL to check (http://demo.1wt.eu/;csv
    -p, --proxies [PROXIES]          Only check these proxies (eg proxy1,proxy2,proxylive)
    -U, --user [USER]                basic auth USER to login as
    -P, --password [PASSWORD]        basic auth PASSWORD
    -d, --[no-]debug                 include debug output


License
-------

GPL https://www.gnu.org/licenses/gpl.html
