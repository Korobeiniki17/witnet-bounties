# witnet-bounties

Total Number of Vulnerabilities Detected: 12 in witnet host, but I believe there are many more vulnerabilities that cloudflare is blocking to run, anyway if you want a complete scan of your platform I will need you to disable cloudflare or create a clone of the website for me to do penetration tests.

I WILL SEND ON EMAIL


Name: Andriel Coelho
Github: https://github.com/Korobeiniki17/witnet-bounties
Vulnerability Definition:
        As the target is lacking this header, older browsers will be prone to Reflected XSS attacks
Level: Medium
Scenario Explain: https://www.youtube.com/watchv=yJSnggHSH1U
List of the components affected: Site structure, data steal, machine access etc ...
How to reproduce the bug or attack: First we have to detect if it is vulnerable to xss reflected then we will make a request on the website and check if the X-XSS-Protection header is present, if so that website can execute xss payloads to get full access to the website.
Other details: This is just not to run any xss reflected on the website because if it is disabled the company website is at risk if a server file is found with xss reflected, but either way, it is better to be safe than sorry ; )
