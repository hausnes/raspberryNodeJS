# raspberryNodeJS
Samling med program som benyttar Node JS for å styre GPIO.

NB: Når du skal installere Node JS må du sjå til at du har ein oppdatert versjon. Per 11. mars 2021 så var anbefalt versjon 12.

Framgangsmåte:
- curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
- sudo apt-get install -y nodejs
- node -v (for å kontrollere om det har blitt installert rett versjon)
- npm install onoff (GPIO-bibliotek)

Etter dette skal du kunne køyre eksempelfilene som ligg i dette 'repository' ved å skrive 'node filnavn.js'. Du endrar sjølvsagt 'filnavn' til det navnet du har på fila di.
