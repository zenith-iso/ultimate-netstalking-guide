Scanning ranges

IP Ranges by Country ---- You can find lists of IP addresses by country on the internet. For example:

> http://www.nirsoft.net/countryip/ - the very first link on Google, ranges in table format

> http://www.ip2location.com/free/visitor-blocker - you can download CIDR lists in a text file

But these ranges are often not up to date. There's a chance that you'll be scanning something completely different from what you wanted.

There is another way to obtain good, valid IP ranges by country.

For this, visit any website with free proxies that filters proxies by country (http://hidemyass.com/, http://spys.ru).
Find the necessary proxies (for example, Chinese ones), and check the **whois** information for these IPs.

> $ whois 121.18.213.236

The information we need is written in the inetnum, CIDR, or route lines.

> inetnum: 121.16.0.0 - 121.23.255.255

> ruta: 121.16.0.0/13

Thus, you can find the freshest ranges, but it takes more time.

IP Ranges by Organizations ---- If you want to find the IPs of specific organizations, providers, companies, or universities, it will be somewhat more complicated.

To begin with, you need to clarify the name of the organization. There is a special search for IP ranges by organizations at http://bgp.he.net/, but you need to enter the name correctly, otherwise you won't find anything!

In addition, you can try to find the IP thru the organization's websites.
Most likely, the main website will be hosted on an external server, but the subdomains www2, admin, and login may lead to the company's internal servers.
To identify hidden subdomains of companies, you can use an AXFR attack on DNS, brute force, or simple Googling.
Be inventive!

Dangerous ranges ----
There is a list of IP ranges on the internet that are recommended not to be scanned.
It can be easily Googled with the words **do not scan ip addresses**.
It includes the IP addresses of U.S. government organizations - military, scientific, and classified organizations.
For those who do not live in the USA, these addresses are the most desirable for research and hacking.

There is a belief that this list is long outdated.
