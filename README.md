# holidaze
Innlogging til admin siden:
Brukernavn: kirsebom
Passord: pokemon1

Nettsiden fungerer optimalt i alle browsere bortsett fra Google Chrome, dette er grunnen:

Det er noen cache controll problemer i google chrome, google chrome ignorer cache kontrollen jeg har lagt inn i .htaccess filen min
Når du legger til ett nytt produkt på nettsiden gjør du en POST request dette fører til at chrome ignorerer cache kontrollen jeg har satt
som går ut på at bilder og filer ikke blir lagret i browseren.
Så for å se det nye produktet du har lagt til på nettsiden må du slette "buffrede bilder og filer" fra loggen og oppdatere fanen.
