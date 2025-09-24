---
title: Audience Agent
description: Lär dig hur du använder Audience Agent för att skapa målgrupper, visa förändringar av målgrupper, identifiera dubblerade målgrupper och visa målgruppsinsikter.
source-git-commit: d91aac948a6fef36949218004dc0481dc8f5cf7f
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Audience Agent

>[!AVAILABILITY]
>
>Audience Agent är tillgängligt för alla kunder som har tillgång till AI Assistant. Du behöver dock följande behörigheter för att kunna använda Audience Agent-funktionerna fullt ut.
>
>**Visa segment**: Med den här behörigheten kan du använda Audience Agent för att visa insikter om målgrupperna direkt i AI Assistant.
>&#x200B;>**Hantera segment**: Med behörigheten Till kan du använda Audience Agent för att skapa nya målgrupper direkt i AI Assistant.

Med Audience Agent kan ni visa insikter om målgrupper, inklusive att identifiera betydande förändringar i målgruppsstorlek, identifiera dubblerade målgrupper, utforska era målgruppslager och hämta era målgruppers storlek.

## Användningsexempel som stöds

Audience Agent i AI Assistant stöder följande användningsområden:

- Hitta målgruppens storlek och upptäcka betydande förändringar i målgruppens storlek
   - På så sätt kan ni hitta målgrupper som plötsligt har växt eller krympt, så att ni bättre kan analysera potentiella marknadsförändringar
- Identifiera duplicerade målgrupper
   - På så sätt kan ni minska redundansen hos era målgrupper
- Hitta målgrupper baserat på fullständiga eller partiella attribut
   - På så sätt kan ni enklare navigera i ert målgruppslager
- Upptäck XDM-fält som du kan använda för att definiera en målgrupp
   - Med den här kompetensen kan ni enklare identifiera rätt fält att använda i er målgrupp baserat på sammanhang och relevans

Audience Agent stöder för närvarande inte **för** följande funktioner:

- Kunskapsbaserad målgruppsproduktion
   - Kunskapsbaserade målgrupper skapar en målgrupp baserat på angivna attribut och händelser
   - Dessutom kan ni uppskatta målgruppens potentiella storlek innan ni skapar målgrupper. På så sätt kan ni snabbt iterera på den mest effektiva målgruppen innan den är redo att aktiveras
   - Stöd för den här funktionen kommer snart
- Målbaserad målgruppsundersökning
   - Målbaserad målgruppsundersökning gör att ni kan identifiera relevanta datauppsättningar och profiler som anpassats till ett affärsmål genom att tillämpa maskininlärningsmodeller som benägenhet att köpa eller konvertera.

När du använder Audience Agent bör du dessutom tänka på följande begränsningar:

- Audience Agent behöver minst 24 timmar för att bearbeta dina data
   - Du **kan till exempel inte** ha en fråga som söker efter data inom de senaste 24 timmarna. Du måste titta inom de senaste 48 timmarna, åtminstone.
- Audience Agent stöder bara **personer**-baserade målgrupper som utvärderas med gruppsegmentering

## Exempeluppmaningar

I följande exempel visas exempelfrågor och svar för Audience Agent.

### Utforska konversationsmålgrupper

Visa fält för välbärgade köpare.

+++ Svar

![AI-assistenten visar en tabell med fält som är relevanta för välbärgade köpare.](./images/audience/affluent-buyers.png)

+++

Vilka målgrupper har inte aktiverats eller använts i någon kampanj de senaste 30 dagarna?

+++ Svar

![AI-assistenten visar en tabell som visar målgrupper som inte har aktiverats eller använts i kampanjer de senaste 30 dagarna.](./images/audience/not-activated.png)

+++

Lista alla målgrupper som har mappats till nya mål de senaste tre månaderna.

+++ Svar

![AI-assistenten visar en målgrupp som har mappats till ett nytt mål under de senaste tre månaderna.](./images/audience/new-destination.png)

+++

### Identifiera duplicerade målgrupper

Har jag någon publik med identiska eller liknande beskrivningar?

+++ Svar

![AI-assistenten visar en tabell som innehåller segmentdefinitionen och namnen på målgrupperna med samma segmentdefinitioner.](./images/audience/similar-descriptions.png)

+++

Identifiera målgrupper som har samma regler men olika namn.

+++ Svar

![AI-assistenten visar en tabell som innehåller namnen på målgrupper som delar samma målgruppsregler.](./images/audience/same-rules-different-names.png)

+++

Visa alla målgrupper som har samma regler men olika aktiveringsmål.

+++ Svar

![AI-assistenten visar att det inte finns några segmentdefinitioner som är dubblerade till olika mål.](./images/audience/same-rules-different-destinations.png)

+++

### Hämta målgruppsstorlek

Vilken är den nuvarande storleken på min publik&quot;Gold-star Members in California_f153e1&quot;?

+++ Svar

![AI-assistenten anger den aktuella storleken på den målgrupp som har tillfrågats om.](./images/audience/current-size.png)

+++

Vilken är min största publik?

+++ Svar

![AI-assistenten ger information om den målgrupp som har flest profiler, inklusive namn och målgrupps-ID.](./images/audience/largest-audience.png)

+++

### Upptäck betydande förändringar i målgruppens storlek

Vilka målgrupper har ökat med över 20 % under den senaste veckan?

+++ Svar

![AI-assistenten visar en tabell med namnen på alla målgrupper som matchar frågan. Den visar också den procentuella ökningen, den aktuella målgruppens storlek samt den tidigare målgruppens storlek.](./images/audience/increase-past-week.png)

+++

Vilka målgrupper har minskat med över 10 % den senaste månaden?

+++ Svar

![AI-assistenten visar en tabell med namnen på alla målgrupper som matchar frågan. Den visar också den aktuella målgruppsstorleken, den tidigare målgruppsstorleken samt datumet för den gamla målgruppsstorleken.](./images/audience/decrease-month.png)

+++

Vilken är min snabbast växande publik?

+++ Svar

![AI-assistenten anger namnet på den snabbast växande publiken, liksom den aktuella storleken och tillväxtprocenten.](./images/audience/fastest-growing.png)

+++

## Nästa steg

När du har läst den här guiden bör du få en bättre förståelse för Audience Agent och vilka funktioner den stöder. Mer information om agenter i Adobe Experience Platform finns i [Agent Orchestrator-översikten](./agent-orchestrator.md).
