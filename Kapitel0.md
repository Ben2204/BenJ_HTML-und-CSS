Kapitel 0 (Einführung):

Aufgabe 1: Vermutungen (Beispiel)

• Ablauf: Mein Browser sendet eine Anfrage über das Internet an den Schul-Server. Dieser schickt die Webseitendaten zurück und mein Browser zeigt sie an.
• Begriffe: Browser, Router, Server, URL, IP-Adresse, HTML, HTTPS.

Aufgabe 2: URLs zerlegen

• http://beispiel.de
	• Protokoll: http:// | Domain: www.beispiel.de | Pfad: /bilder/tux.png

•https://w3.org
	• Protokoll: https:// | Domain: www.w3.org | Pfad: /standards/

• https://selfhtml.org
	• Protokoll: https:// | Domain: wiki.selfhtml.org | Pfad: /wiki/HTML

Aufgabe 3: DNS abfragen

• Ergebnis: Beide Adressen liefern exakt dieselben IP-Adressen.
• Unterschied: ://example.com ist eine Subdomain von example.com, verweist aber auf denselben Server.

Aufgabe 4: Richtige Reihenfolge (Rückblick)

1. Name auflösen: Der Browser fragt beim DNS die IP-Adresse zum Domain-Namen ab.
2. Anfragen: Der Browser (Client) schickt eine HTTPS-Anfrage an diese IP-Adresse des Webservers.
3. Antworten: Der Webserver sucht die Datei und sendet sie zurück.
4. Anzeigen: Der Browser liest das HTML-Dokument und baut die Webseite auf.


Kapitel 0 (Vertiefung):

Aufgabe 1: URLs zerlegen

• http://www.beispiel.de/bilder/tux.png
	• Protokoll: http
	• Domain-Name: www.beispiel.de
	• Pfad: /bilder/tux.png

• https://www.w3.org/standards/
	• Protokoll: https
	• Domain-Name: www.w3.org
	• Pfad: /standards/

• https://www.gymnasium-hueckelhoven.de/
	• Protokoll: https
	• Domain-Name: www.gymnasium-hueckelhoven.de
	• Pfad: /

Aufgabe 2: Der Weg einer Anfrage

Die richtige Reihenfolge lautet: B – E – D – A – F – C (oder je nach Sichtweise C und F getauscht, da der Browser oft erst das Grundgerüst aufbaut und Bilder nachlädt – B, E, D, A am Anfang ist aber zwingend).
1. B: Der Browser fragt das DNS nach der IP-Adresse zum Domain-Namen.
2. E: Das DNS liefert die passende IP-Adresse.
3. D: Der Browser schickt eine HTTP-Anfrage an die IP-Adresse.
4. A: Der Webserver sucht die Datei und sendet sie zurück.
5. F: Fehlen Bilder oder Stylesheets, fordert der Browser sie in weiteren Anfragen nach.
6. C: Der Browser baut die Ansicht der Webseite auf.

Aufgabe 3: WWW gleich Internet?

Nein, Lucas hat nicht recht. Das Internet ist die weltweite technische Infrastruktur aus miteinander verbundenen Rechnern und Netzwerken. Das World Wide Web (WWW) ist hingegen nur einer von vielen Diensten (neben z. B. E-Mail oder Chats), der über das Internet läuft und Webseiten bereitstellt.

Aufgabe 4: Eine IP, mehrere Namen

• Ergebnis: Ja, beide Adressen liefern in der Regel dieselben IP-Adressen (verweisen auf denselben Server-Verbund).
• Bedeutung: Ein einzelner Webserver (eine IP) kann mehrere verschiedene Webseiten unter unterschiedlichen Domain-Namen bereitstellen.

Aufgabe 5: EVA und Datensicherheit

• EVA-Zuordnung:
	• Eingabe: URL eingeben
	• Verarbeitung: DNS-Auflösung und Anfrage verarbeiten
	• Ausgabe: Webseite anzeigen
• Datensicherheit (Beispiele):
	• Vertraulichkeit: Passwörter werden per HTTPS verschlüsselt übertragen, damit niemand mitliest.
	• Integrität: Webseiteninhalte oder Downloads werden unterwegs nicht unbemerkt verändert.
	• Verfügbarkeit: Die Webseite ist dauerhaft erreichbar und stürzt nicht ab.
• HTTPS & Vertrauen: HTTPS verschlüsselt nur den Transportweg, garantiert aber nicht, dass der Betreiber seriös ist (auch Fake-Shops nutzen HTTPS).

Aufgabe 6: Chancen und Risiken (Beispiel: Handel)

• Chance: Bequemes Einkaufen rund um die Uhr und einfacher Preisvergleich.
• Risiko: Betrug durch Fake-Shops oder Missbrauch von Zahlungsdaten.
• Auswirkung auf die Arbeit: Weniger Verkäufer im lokalen Einzelhandel, dafür mehr Jobs in Logistik, Lager und IT.