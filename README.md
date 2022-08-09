# Request Header Parser Microservice

I created this app as a requirement for my freeCodeCamp APIs and Microservices Certification, using Node.js and Express. The above front end API test also uses Bootstrap, jQuery, and highlight.js. The API fulfills the following user story:

I can get the IP address, preferred languages (from header Accept-Language) and system infos (from header User-Agent) for my device.
Example usage:
[base url]/api/whoami
Example output:
{"ipaddress": "::ffff:159.20.14.100", "language": "en-US,en;q=0.5", "software": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}

