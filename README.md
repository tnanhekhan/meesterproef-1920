# Meesterproef @cmda-minor-web 1920
Broncode: https://github.com/tnanhekhan/vocab

## Table of Contents
- [Week 1](#week-1)
## Week 1
### Debriefing
VOCAB is een concept voor een voice user interface die helpt om jonge kinderen te leren lezen met behulp van visuele feedback en auditieve feedback. Het concept voor VOCAB is ontworpen door studenten van HvA CMD.

Om VOCAB te kunnen testen en verbeteren, moet er een werkend prototype geleverd worden. Design documentatie voor Vocab wordt geleverd door de studenten van HvA CMD en aan de hand van deze design documentatie moet er een werkend prototype gebouwd worden.

#### Doelgroep
Oorspronkelijk was VOCAB ontworpen voor het NT2 onderwijs. Dat is onderwijs speciaal voor leerlingen tussen de 6 en 11 jaar die het Nederlands als tweede taal spreken. Wegens de coronacrisis is de opdracht verruimd en nu is de doelgroep van VOCAB alle thuislerende leerlingen.

#### Product
VOCAB bestaat uit meerdere onderdelen:
- Content Management System (CMS)
- Voice Interface
- Image Generator

De voorwaarde van success voor deze opdracht is dat er tenminste een gebruiksvriendelijke CMS geleverd wordt.

##### Content Management System (CMS)
VOCAB gebruikt lijsten van woorden die door docenten aangepast kunnen worden. Deze woorden moeten worden beheerd door middel van een CMS. Naast het beheren van de woordenlijsten kunnen ook lijsten van klassen en lijst van leerlingen beheerd worden. 

Naast beheren heeft de CMS ook een rapportage functionaliteit waarbij de vooruitgang per leerling gezien kan worden. Ook is er sprake van een chat functionaliteit tussen Docenten.

##### Voice Interface
De Voice Interface is het gedeelte dat gebruikt wordt door de leerlingen. Hier krijgen de leerlingen een woord te zien met een gerelateerde afbeelding. De leerlingen moeten dan het woord uitspreken. De Voice Interface geeft dan aan of het woord correct of incorrect is.

##### Image Generator
Op basis van het woord moet er door middel van Machine Learning en Artificial Intelligence een afbeelding gegenereerd worden dat te herkennen is door de doelgroep. De Image Generator moet zodanig problemen met copyright voorkomen. De implementatie van een Image Generator wordt waarschijnlijk niet gerealiseerd wegens de moeilijkheidsgraad van dit onderdeel. Hier moet nog wat meer onderzoek naar gedaan worden.

#### Product Stack
Voor de CMS wordt een [Node Express app](https://expressjs.com/) met daarbij een [Firebase Back-end](https://firebase.google.com/) om alle data op te slaan. MongoDB o 

Voor de Voice Interface wordt er gebruik gemaakt van [Google Conversation Actions](https://developers.google.com/assistant/conversational).

Hoe de Image Generator geimplementeerd wordt is nog onduidelijk. Er kan gekeken worden naar een implementatie met behulp van [Google Vision AI](https://cloud.google.com/vision?hl=nl) 

#### Proces
Dit project heeft een scrum-achtige opzet. Er zijn vijf sprints die ieder een week duren. Elke maandag is er een soort sprint planning en elke vrijdag is er een soort sprint review waarbij de vooruitgang van de week wordt gepresenteerd. Aan het eind van elke week wordt er dus een Minimum Viable Product (MVP) verwacht. Yuri Westplat is hier de product owner van dit project.

##### Team
VOCAB wordt gemaakt in samenwerking met OBA en studenten van de HvA. Hier zijn alle deelnemers van dit project:

- Yuri Westplat (Product Owner)
- Vasilis van Gemert (Coach)
- Studenten HvA CMD (Design Team)
- Heralt Levant (Developer)
- Tabish Nanhekhan (Developer)