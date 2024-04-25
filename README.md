### Mirte applicatie gebouwd met Laravel, Vue.js, Tailwind.css en Inertia.js met Stripe 

#### Installatie

Zorg ervoor dat je omgeving correct is ingesteld. Je hebt MySQL, PHP 8.1, Node.js en Composer nodig.

#### Installeer Laravel Website + API

1. Download het project 
2. Kopieer .env.example naar .env en configureer database referenties
3. Navigeer naar de hoofdmap van het project via de terminal
4. Voer `composer install` uit
5. Stel de encryptiesleutel in door `php artisan key:generate` uit te voeren
6. Voer migraties uit `php artisan migrate --seed`
7. Voer gegevens seeder uit om te testen ``` php artisan db:seed AdminSeeder``` en en andere db seeder bestanden die je kunt vinden onder database/seeders
8. Start de lokale server door `npm install --save-dev vite` uit te voeren
9. Open een nieuwe terminal en navigeer naar de hoofdmap van het project
   Voer `npm install` uit
10. Voer `npm run dev` uit om de vite-server te starten voor de Laravel-frontend
11. Voor de Stripe API-sleutel, ga naar het .env-bestand en vervang de api-sleutel voor deze variabele ```STRIPE_KEY="VERVANG HIER MET JE STRIP API-SLEUTEL"```

### IamMirte Webshop Casus 4
De casus zit ook in het Project.
Dit is de officiële repository voor de IamMirte-webshop, een non-profitinitiatief van de TU Delft om wetenschap en techniek te verspreiden onder jongeren via de MIRTE-robot.

## Doel

Het doel van deze webshop is om MIRTE-robotpakketten en bijbehorend lesmateriaal beschikbaar te maken voor scholen en particulieren. De winst die wordt gegenereerd uit de verkoop van deze pakketten wordt gebruikt om workshops te organiseren voor scholen in kansarme gebieden.

## Functionaliteiten

- Mogelijkheid om MIRTE-robotpakketten te bestellen (Basic en Pioneer).
- Ondersteuning voor iDeal-betalingen voor een naadloze transactie-ervaring.
- Optie om de website naar het Engels te vertalen.
- Informatie over workshops voor scholen in kansarme gebieden.
- Nadruk op een inclusieve leveranciersketen en naleving van ANBI-eisen.

## Bijdragen

We verwelkomen bijdragen van ontwikkelaars die willen helpen bij het verbeteren en uitbreiden van de webshopfunctionaliteit, vertalingen naar andere talen, het oplossen van problemen en meer. Bekijk de bijdragegids en de openstaande problemen om te beginnen.

## Licentie

Dit project wordt vrijgegeven onder MBORijnland.

## Contact

Voor vragen, suggesties of feedback kunt u contact met ons opnemen of een probleem indienen in de repository.
