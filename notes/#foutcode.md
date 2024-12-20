---
attachments: [CTF_templatearchitectuur.ctd]
tags: ['#Publicatie platform: https:/open.brabant.nl']
title: '#foutcode'
created: '2024-12-20T08:54:49.943Z'
modified: '2024-12-20T09:07:28.383Z'
---

#foutcode

#foutcode PR_CONNECT_RESET_ERROR

vergunningmodule https://voi.brabant.nl/handlers/vergunningenmodule/downloaddocument.ashx?id=105768

GET /handlers/vergunningenmodule/downloaddocument.ashx?id=105768 undefined
Host: voi.brabant.nl
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:133.0) Gecko/20100101 Firefox/133.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: nl,en-US;q=0.7,en;q=0.3
Accept-Encoding: gzip, deflate, br, zstd
Referer: https://www.google.com/
Connection: keep-alive
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: cross-site
Sec-Fetch-User: ?1
Priority: u=0, i

curl 'https://voi.brabant.nl/handlers/vergunningenmodule/downloaddocument.ashx?id=105768' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:133.0) Gecko/20100101 Firefox/133.0' -H 'Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8' -H 'Accept-Language: nl,en-US;q=0.7,en;q=0.3' -H 'Accept-Encoding: gzip, deflate, br, zstd' -H 'Referer: https://www.google.com/' -H 'Connection: keep-alive' -H 'Upgrade-Insecure-Requests: 1' -H 'Sec-Fetch-Dest: document' -H 'Sec-Fetch-Mode: navigate' -H 'Sec-Fetch-Site: cross-site' -H 'Sec-Fetch-User: ?1' -H 'Priority: u=0, i'


fetch("https://voi.brabant.nl/handlers/vergunningenmodule/downloaddocument.ashx?id=105768", {
    "credentials": "omit",
    "headers": {
        "User-Agent": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:133.0) Gecko/20100101 Firefox/133.0",
        "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8",
        "Accept-Language": "nl,en-US;q=0.7,en;q=0.3",
        "Upgrade-Insecure-Requests": "1",
        "Sec-Fetch-Dest": "document",
        "Sec-Fetch-Mode": "navigate",
        "Sec-Fetch-Site": "cross-site",
        "Sec-Fetch-User": "?1",
        "Priority": "u=0, i"
    },
    "referrer": "https://www.google.com/",
    "method": "GET",
    "mode": "cors"
});

https://voi.brabant.nl/handlers/vergunningenmodule/downloaddocument.ashx?id=105768

https://learn.microsoft.com/en-us/troubleshoot/developer/webapps/aspnet/development/http-modules-handlers

https://learn.microsoft.com/en-us/troubleshoot/


De foutmelding PR_CONNECT_RESET_ERROR betekent meestal dat de verbinding tussen jouw apparaat en de server werd onderbroken. Dit kan gebeuren door verschillende oorzaken, zoals netwerkproblemen, firewalls of browserinstellingen. Hier zijn enkele stappen om dit probleem op te lossen:
1. Controleer je internetverbinding

    Zorg ervoor dat je een stabiele internetverbinding hebt.
    Probeer andere websites te bezoeken om te zien of het probleem alleen bij deze specifieke site optreedt.

2. Wis je browsercache en cookies

    Ga naar de instellingen van je browser.
    Zoek de optie om cache en cookies te wissen.
    Herstart je browser en probeer de website opnieuw.

3. Controleer je firewall en antivirusinstellingen

    Soms blokkeren firewalls of antivirusprogramma's de verbinding.
    Zet je antivirussoftware tijdelijk uit om te zien of dat het probleem oplost.
    Voeg de website toe aan de lijst van vertrouwde websites als dat mogelijk is.

4. Probeer een andere browser

    Test de website in een andere browser, zoals Google Chrome, Microsoft Edge, of Firefox.
    Als de website in een andere browser werkt, kan het een probleem zijn met je standaardbrowser.

5. Gebruik een VPN of proxy

    Als de verbinding wordt gereset door jouw netwerk of de serverlocatie, kan een VPN of proxy helpen.

6. Controleer de status van de website

    Het kan zijn dat de server zelf offline is of problemen heeft. Controleer of de website beschikbaar is via een service zoals DownDetector.

7. Contacteer de websitebeheerder

    Als de bovenstaande stappen niet werken, neem dan contact op met de eigenaren van de website. Ze kunnen je mogelijk meer informatie geven over wat er misgaat.
