Server configuration disclosure



Hi,

I found some dangerous urls on your servers that reveal important informations about the servers configuration themself and that are very interesting from a hacker point of view.


## Urls

https://xxx.xxxxxxxxxxxx.xxx/.........


## PoC

{}


## Risk

While this does not represent a real security issue, this reveal important informations about your system and could be used by a malicious user for a future attack.
A hacker could retrieve the modules installed on the server with their version number and then find a corresponding exploit on the Internet. 
The full path is mandatory for a file upload attack.



## Remediation

- Disable that kind of function on production server
- Protect them with strong credentials
- Use ip restriction





Best regards,

Gwen

