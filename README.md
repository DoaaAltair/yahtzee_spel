Yahtzee Spel 🎲
Dit is een interactief Yahtzee-spel dat ik heb gebouwd met React als onderdeel van mijn opleiding Media Design. Het doel was om te oefenen met frontend development, componenten te leren opbouwen en een werkende gebruikersinterface te maken. In het spel kun je inloggen, dobbelen, scores bekijken en de voortgang lokaal opslaan.

Functionaliteiten
🔐 Inloggen
Gebruikers voeren een e-mailadres en wachtwoord in. De naam wordt opgeslagen in LocalStorage en gebruikt in het spel en op de scorepagina.

🏠 Homepagina
Na inloggen kom je op de homepagina waar je kunt kiezen om een nieuw spel te starten of je huidige spel te hervatten.

🎲 Spelpagina
Je speelt het spel door op "Gooien" te klikken. Er worden vijf dobbelstenen weergegeven. De waarden worden willekeurig bepaald en opgeslagen in LocalStorage.

📊 Scores bekijken
Na een worp kun je je score bekijken. De score wordt automatisch berekend op basis van de gegooide dobbelstenen en weergegeven per categorie (zoals 1-en, Yahtzee, Full House, etc.).

🎨 Ontwerp
De kleuren zwart, rood, lichtgrijs en wit zijn gekozen op basis van veelgebruikte kleuren in spelletjes, waarbij rood vaak opvalt en spanning toevoegt. De UI is ontworpen in Figma en de afbeeldingen (zoals voor de inlogpagina) zijn gemaakt in Canva.

Bestandenstructuur
App.js – Hoofdcomponent met routing en inlogfunctionaliteit

Home.js – Welkomstpagina na inloggen

Game.js – Spelpagina met dobbelstenen en acties

Scores.js – Scorepagina (nog toevoegen of koppelen)

Home.css / Game.css / Login.css – Styling per pagina
