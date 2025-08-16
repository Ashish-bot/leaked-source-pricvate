# leaked-source-pricvate


Have I Been Pwned (HIBP) 🔗 https://haveibeenpwned.com/

    Intelligence X (Free Tier) 🔗 https://intelx.io/

    DeHashed (Free & Paid) 🔗 https://www.dehashed.com/

    Leak-Lookup (Free for Basic Checks) 🔗 https://leak-lookup.com/

    Vigilante.pw (Free Breach Search) 🔗 https://vigilante.pw/

    BreachDirectory (Free Lookup) 🔗 https://breachdirectory.org/

    Pulsedive (Threat Intelligence Search) 🔗 https://pulsedive.com/

    Search on Pastebin-like Sites Manually check:

    https://pastebin.com/

    https://ghostbin.com/

    https://rentry.co/

    https://controlc.com/

    https://www.doxbin.org/

    Google Dorking

    intitle:"index of" "database.sql"
    → Finds raw SQL database dumps

    filetype:sql intext:"password"
    → SQL files containing passwords

    intitle:"index of" "backup.zip"
    → Exposed backup files

    filetype:env DB_USERNAME DB_PASSWORD
    → Exposed .env files (common in web apps)

    ext:ini intext:"api_key"
    → Configuration files with API keys

    intitle:"phpMyAdmin" "Welcome to"
    → Exposed phpMyAdmin panels

    intext:"@gmail.com" filetype:csv
    → CSV files with Gmail addresses

    intext:"username" AND intext:"password" filetype:log
    → Log files with credentials

    intitle:"login" inurl:/admin ext:txt
    → Plaintext admin login details

    "-----BEGIN RSA PRIVATE KEY-----"
    → Private encryption keys

    intext:"password" ext:txt | ext:log
    → Passwords in text/log files

    site:github.com "AWS_ACCESS_KEY_ID"
    → AWS keys in GitHub repos

    "api.googlemaps key" ext:env
    → Google Maps API keys

    site:pastebin.com "mongodb://"
    → MongoDB connection strings

    "firebaseio.com" ext:json
    → Firebase database URLs

    site:gitlab.com "SECRET_KEY"
    → GitLab secrets

    site:pastebin.com "companyname"
    → Checks Pastebin for leaks

    site:controlc.com "password list"
    → Finds password dumps

    site:justpaste.it intext:"breach"
    → Checks JustPaste.it for breaches

    site:rentry.co "leaked"
    → Searches Rentry.co for leaks

    intitle:"webcamXP 5"
    → Exposed WebcamXP dashboards

    inurl:/view.shtml
    → Live security camera feeds

    intitle:"printer" inurl:/cgi-bin/
    → Exposed printer admin panels

    intext:"Hikvision" intitle:"Login"
    → Hikvision camera logins
