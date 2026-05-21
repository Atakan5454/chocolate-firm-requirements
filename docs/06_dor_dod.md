# 6. Definition of Ready en Definition of Done

# 6. Definition of Ready en Definition of Done

## 6.1 Definition of Ready

De Definition of Ready bepaalt wanneer een user story klaar is om opgepakt te worden door het ontwikkelteam. Een user story mag pas in een sprint worden opgenomen wanneer deze voldoende duidelijk, afgebakend en controleerbaar is.

### Een user story is Ready wanneer:

- De user story volledig is geschreven in de vorm:  
  **Als (rol) wil ik (functionaliteit) zodat (doel).**

- Het doel van de user story duidelijk is. Dit betekent dat zichtbaar is welke waarde de functionaliteit heeft voor de gebruiker of voor Chocolate Firm.

- Per user story minimaal drie acceptatiecriteria zijn opgesteld. Deze acceptatiecriteria moeten testbaar zijn, zodat gecontroleerd kan worden of ze behaald zijn.

- De user story klein genoeg is om binnen één sprint ontworpen, gebouwd en getest te worden. Wanneer een user story te groot is, wordt deze opgesplitst in kleinere user stories.

- Afhankelijkheden vooraf bekend zijn. Hierbij gaat het bijvoorbeeld om koppelingen met:
  - ERP
  - CRM
  - BI
  - AI-chatbot
  - externe databronnen

- Elke user story een inschatting heeft in:
  - S
  - M
  - L

  Hierdoor kan het ontwikkelteam bepalen hoeveel werk een story ongeveer kost.

- Voor user stories waarin een scherm voorkomt een passend wireframe beschikbaar is. Hierdoor weet het ontwikkelteam hoe de functionaliteit eruit moet zien.

- De prioriteit van de user story bepaald is, bijvoorbeeld:
  - Must
  - Should
  - Could
  - Won’t

- Duidelijk is welke stakeholder of key user verantwoordelijk is voor beoordeling en goedkeuring van de functionaliteit.

---

## 6.2 Definition of Done

De Definition of Done bepaalt wanneer een user story daadwerkelijk afgerond is. Een user story is pas Done wanneer de functionaliteit werkt volgens de acceptatiecriteria, getest is en geschikt is voor oplevering.

### Een user story is Done wanneer:

- De functionaliteit gerealiseerd is volgens de beschrijving van de user story.

- Alle acceptatiecriteria gecontroleerd en goedgekeurd zijn. Dit betekent dat elk criterium aantoonbaar behaald is.

- De functionaliteit functioneel getest is. Hierbij wordt gecontroleerd of de functionaliteit doet wat in de user story en acceptatiecriteria beschreven staat.

- De functionaliteit beoordeeld is door minimaal één key user of stakeholder. Hiermee wordt gecontroleerd of de oplossing aansluit op de behoefte van de gebruiker.

- Er geen openstaande bugs zijn met prioriteit **hoog** of **kritisch**. Kleine fouten mogen alleen open blijven staan wanneer zij geen invloed hebben op het gebruik van de functionaliteit.

- Foutmeldingen correct werken. Wanneer een gebruiker verkeerde gegevens invoert of een actie mislukt, moet een duidelijke foutmelding zichtbaar zijn.

- Wanneer een user story een scherm bevat, het gerealiseerde scherm overeenkomt met het bijbehorende wireframe.

- De navigatie correct werkt. De gebruiker moet logisch kunnen:
  - teruggaan
  - doorgaan
  - navigeren naar andere onderdelen van de applicatie

- Data correct wordt verwerkt. Ingevoerde of opgehaalde gegevens moeten correct worden:
  - opgeslagen
  - weergegeven
  - doorgestuurd naar gekoppelde systemen zoals ERP, CRM en BI

- De documentatie bijgewerkt is. Belangrijke keuzes, werking en testresultaten moeten vastgelegd zijn in het projectdocument.

---

## 6.3 Toepassing binnen dit project

Binnen de Chocolate Firm App worden de Definition of Ready en Definition of Done gebruikt om de kwaliteit van de user stories te bewaken. Hierdoor weet het ontwikkelteam vooraf wanneer een user story klaar is om gebouwd te worden en achteraf wanneer deze daadwerkelijk afgerond is.

### Voorbeeldtoepassing

De user story over het scannen van een QR-code is pas **Ready** wanneer:

- het doel duidelijk beschreven is
- acceptatiecriteria aanwezig zijn
- een wireframe beschikbaar is
- de afhankelijkheid met productdata bekend is

De user story is pas **Done** wanneer:

- de QR-code correct wordt herkend
- productinformatie zichtbaar wordt
- foutmeldingen correct functioneren
- de functionaliteit succesvol getest is door een gebruiker
[Vorige](05_user_stories.md) | [README](../README.md) | [Volgende](07_sitemap.md)
