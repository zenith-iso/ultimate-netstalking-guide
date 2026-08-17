Questions about Network Scanning === Q: **Why is mass scanning of IP addresses undesirable and prohibited by most hosting providers?**

A: With some providers (for example, [Linode](https://www.linode.com/)), you can scan quite freely until the first abuse reports. But the issue of further reactions to these actions is closely related to blacklists, for example, the organization [Spamhaus](https://www.spamhaus.org/), whose blacklists are used by many large corporations.

The essence is that when spam, hacking attempts, and so on are detected, your address is added to a blacklist. Next, escalation begins (essentially, racketeering at the institutional level) at the provider level - if the provider does not eliminate the cause of the block, the provider's range is blocked, and Spamhaus starts contacting the provider's higher level.

In the end, a large subnet or even an AS (autonomous system) may be blocked, and the provider may have to pay a large sum to have it removed from the lists.

Of course, it's more beneficial for the provider to block you immediately rather than deal with various Spamhaus and USEProtect, pay fines, and watch regular users leave who encountered the block (email blocking and so on).

Q: **Which scan is easier for the provider to detect?**

A: The easiest to detect is a mass address scan, hands down. A scan of random addresses is much harder to detect, while a scan of a single address (or, for example, a slow brute-force attack) can blend in with regular traffic (example: just sitting on VK, the browser makes a huge number of requests to download photos, audio, and other stuff).
