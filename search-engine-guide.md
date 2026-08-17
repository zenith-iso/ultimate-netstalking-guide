Netstalking and search engines

Search Engines (hereinafter SE) index everything they can reach.
This plays into the hands of those who want to find all sorts of unusual things on the internet, that is, us!
To search for and find exactly what you need, you need to know how to use its query syntax.

Stalker, **remember**: search engines index data thru links.
This means that all the cameras or documents that Google knows about have likely been posted by someone on forums in the form of links.

Google ---- The leader among search engines, this giant will find everything you desire.
There is even a special discipline among amateur hackers called "google hacking" - the process of finding vulnerabilities and valuable information thru Google.

[Search Syntax](https://support.google.com/websearch/answer/136861?hl=en).

The query in Google that helps find the necessary information is called a **google dork**.
Examples of the simplest dorks:

SQL server errors: > site:gov "error in your sql syntax"

"Secret" materials: > filetype:pdf site:gov "top secret"

All sorts of backups: > intitle:"index of /backup/"

Searching on pastebin.com will reveal a lot of new things for you: > site:pastebin.com password @gmail.com

Searching for Google dorks on Google: > site:pastebin.com dorks

The dork database is [here](http://www.exploit-db.com/google-dorks/).
Requests for searching IP cameras [here](http://www.google.com/search?q=site:pastebin.com+camera+dork).

Yandex has a different search syntax, more tailored to the Russian user.
It's easier to find all sorts of artifacts and fossils in the RuNet with it.

Shodan ---- [Shodan](http://shodan.io/) - a special search engine that looks for devices connected to the internet.
You can find everything from routers to industrial automation systems.
Searching beyond the first page is available after registration, and if you want full access, you'll have to pay the creator.

Censys ---- [Censys](http://censys.io/) - a search engine similar to Shodan, created as an interface to vast archives of full internet scans (https://scans.io/). Updates are made daily using scans thru ZMap and ZGrab. Free, but registration is required for more than 5 searches per day. Supported by Google.

robots.txt ---- robots.txt is a special file in the root folder of a website that webmasters use to restrict access to search engines. Sometimes, the webmaster hides what should be kept from our curious eyes: the admin panel, the log folder, backups, etc.
