# UI/UX login flow opgave

Du skal lave et login flow som består af i alt fire skærmbilleder.

* Et "splash screen" som viser muligheden for at logge ind eller registrere sig som bruger
* En formular til at logge ind med
* En formular til at registrere sig som bruger med
* Forsiden på applikationen når brugeren er logget ind.

### Beskrivelse af funktionalitet:
Hvis brugeren er logget ind vises forsiden på applikationen.
Hvis brugeren ikke er logget ind **redirectes** brugeren til applikationens "splash screen"
Herfra kan brugeren vælge imellem at logge ind eller registrere sig som bruger.

### Krav til opgaven
Opgavens formål er at simulere et login flow og bygge front-end oplevelsen i selve login flowet.
Selve "login-delen" løses ved at lave en sessionstorage, sådan at man får login-oplevelsen hver gang man starter applikationen.
Du skal selv finde på, hvordan forsiden af applikationen skal se ud. 

### Prioritering af opgavens elementer
Fokuser føst og fremmest på, at få selve flowet (javascript-delen) til at virke.
Modularisér herefter din javascript fil i det omfang det giver mening (husk at linke til hovedfilen med type="module" i html.
Tilføj herefter css til dine skærmbilleder.
Fokus ligger således på funktionalitet frem for eye candy...
_Make it work - make it pretty_
