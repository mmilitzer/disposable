## High fraud-risk email domains

A collection of domains for disposable email services like [10MinuteMail](http://10minutemail.com) and [GuerrillaMail](https://www.guerrillamail.com) or anonymous/low-security freemailers that are known to be commonly used by spammers and scammers (like e.g. the domains belonging to the [mail.com](https://www.mail.com) email service). Also, some 🛠 to make your life easier.

### Why?

Use it to validate email addresses on sign up, or just to see how many real email addresses you have in your system.

### Usage

* list

A [file](https://raw.githubusercontent.com/mmilitzer/disposable/master/domains.txt)
containing a sorted list of domains, one per line.

```
curl https://raw.githubusercontent.com/mmilitzer/disposable/master/domains.txt
```

* JSON array

A [file](https://raw.githubusercontent.com/mmilitzer/disposable/master/domains.json)
containing a sorted array of domains, in JSON format.

```
curl https://raw.githubusercontent.com/mmilitzer/disposable/master/domains.json
```

### Update the list of domains

To update the list of domains run `.generate` (requires `python3`), and optionally submit a PR.

```lang=bash
$ ./.generate
Fetched 1110 domains
 - 312 domain(s) added
 - 110 domain(s) removed
```

### Credits

-	https://github.com/adamloving
-	https://github.com/michenriksen
-	https://github.com/ivolo
-       https://github.com/martenson

