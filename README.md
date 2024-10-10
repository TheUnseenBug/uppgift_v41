# uppgift_v41

Hur du öppnar projektet:
Du öppnar projektet genom att öppna upp index.html i vscode eller annan kodeditor där du har en extension som heter live server. Du högerklickar på koden i index.html och klickar på open with liveserver så kommer applikationen öppnas i en webbläsare tab.

Teknisk beskrivning:
HTML koden är semantisk och använder element som nav, main, section, footer, article för att förklara innehållet. Flexbox används på flera platser men bland annat i header genom klassen nav-list för att centrera knapparna. Grid används i link-container när skärmen är mindre än 768px för att sätta alla fake länkar i två olika columner istället för en lång rad. Clamp används för att kontrollera textstorleken i hela appen. alt attribut finns för alla bilder och beskriver vad som sker på bilden, rubriksstrukturen är tydligen en h1, sen h2, h3 beroende på hur viktigt elementet är på sidan. Färgkontrasten fick godkänt av lighthouse, majoriteten av sidan är vit text på mörkblå bakgrund. Knapparna i header har arialabels för att beskriva vad dem är. Jag har använt chrome-devtools för att felsöka problem med bland annat footer jag haft och använda den för lighthouse testning. Git har använts för hela projektet och undersidan about hade en separat branch under utveckling av den.
