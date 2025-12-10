---
title: Audience-agent
description: Lär dig hur du använder Audience Agent för att skapa målgrupper, visa förändringar av målgrupper, identifiera dubblerade målgrupper och visa målgruppsinsikter.
source-git-commit: ca3766477459fb13170d176057a3ea9fbb791b29
workflow-type: tm+mt
source-wordcount: '1203'
ht-degree: 0%

---


# Audience-agent

>[!AVAILABILITY]
>
>Audience Agent är tillgängligt för alla kunder som har tillgång till AI Assistant. Du behöver dock följande behörigheter för att kunna använda Audience Agent-funktionerna fullt ut.
>
>**Visa segment**: Med den här behörigheten kan du använda Audience Agent för att visa insikter om målgrupperna direkt i AI Assistant.
>
>**Hantera segment**: Med behörigheten kan du använda Audience Agent för att skapa nya målgrupper direkt i AI Assistant.

Med Audience Agent kan ni visa insikter om målgrupper, inklusive att identifiera betydande förändringar i målgruppsstorlek, identifiera dubblerade målgrupper, utforska era målgruppslager och hämta era målgruppers storlek.

>[!SLIDE](audience-agent-overview)

## Användningsexempel som stöds

Audience Agent i AI Assistant stöder följande användningsområden:

- Utforska er målgrupp konversationellt
   - Hitta målgruppsstorlekar för befintliga målgrupper
   - Sök efter målgrupper baserat på fullständiga eller partiella attribut
   - Identifiera duplicerade målgrupper
   - Upptäck XDM-fält som du kan använda för att definiera en målgrupp
- Upptäck betydande förändringar i målgruppens storlek
   - På så sätt kan ni hitta målgrupper som plötsligt har växt eller krympt, så att ni bättre kan analysera potentiella marknadsförändringar
- Skapa målgrupper
   - Med den här kompetensen kan du skapa en målgrupp baserat på angivna attribut och händelser
   - Med den här kompetensen kan ni dessutom uppskatta en målgrupps potentiella storlek innan ni skapar målgruppen, så att ni snabbt kan iterera på den mest effektiva målgruppen innan den är redo att aktiveras

<!-- - Find your audience size and detect significant changes in audience size
  - This lets you find audiences that have suddenly grown or shrunk, letting you better analyze potential market changes
- Detect duplicate audiences
  - This lets you reduce redundancies with your created audiences
- Find audiences based on full or partial attributes named
  - This lets you more easily navigate through your audience inventory
- Discover XDM fields you can use to define an audience
  - This skill lets you more easily identify the right fields to use in your audience based on context and relevance -->

Audience Agent stöder för närvarande inte **för** följande funktion:

- Målbaserad målgruppsundersökning
   - Målbaserad målgruppsundersökning gör att ni kan identifiera relevanta datauppsättningar och profiler som anpassats till ett affärsmål genom att tillämpa maskininlärningsmodeller som benägenhet att köpa eller konvertera.

När du använder Audience Agent bör du dessutom tänka på följande begränsningar:

- Audience Agent behöver minst 24 timmar för att bearbeta dina data
   - Du **kan till exempel inte** ha en fråga som söker efter data inom de senaste 24 timmarna. Du måste titta inom de senaste 48 timmarna, åtminstone.
- Audience Agent stöder endast följande målgruppstyper:
   - **Personbaserade** målgrupper som utvärderas med gruppsegmentering
   - **Kontobaserade** målgrupper för följande användningsområden:
      - Utforska målgrupper i konversationen
      - Duplicera målgruppsidentifiering

## Exempeluppmaningar

I följande exempel visas exempelfrågor och svar för Audience Agent.

### Utforska målgrupper i konversationen

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

Vilken kontopublik har den största målgruppen och hur stor är den?

+++ Svar

![AI-assistenten visar en tabell med de största målgrupperna.](./images/audience/largest-account-audience.png)

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

Identifiera målgrupper som har samma regler men olika namn.

+++ Svar

![AI-assistenten visar en tabell som innehåller namn och ID:n för kontomålgrupper som delar samma målgruppsregler.](./images/audience/duplicate-account-audience.png)

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

### Skapa en målgrupp

När du skapar en målgrupp med Audience Agent guidar AI Assistant dig genom en plan. Du kan till exempel be om att&quot;Skapa en publik bestående av personer som bor i Kalifornien&quot;. AI Assistant anger sedan den plan som ska ingå för att skapa målgruppen.

+++ Svar

![AI-assistenten visar planen att skapa en målgrupp.](./images/audience/audience-create-plan.png)

+++

Denna plan består av tre steg:

1. [Identifiera målgruppsegenskaper](#identify)
2. [Beräkna målgruppens storlek](#estimate)
3. [Skapa och bevara en ny publik](#create)

#### Identifiera målgruppsegenskaper {#identify}

![Steg 1 av planen, som är att identifiera målgruppsegenskaper.](./images/audience/plan-step-1.png){align="center" width="80%"}

När du har godkänt planen hämtar AI Assistant målgruppens egenskaper baserat på din första fråga.

+++ Svar

![Målgruppsdefinitionen baseras på användarfrågan.](./images/audience/audience-create-definition.png)

AI Assistant genererar den relevanta Profile Query Language (PQL) som ska användas av personer i Kalifornien. I det här fallet ser PQL-frågan ut så här:

```sql
homeAddress.state.equals("California", false)
```

Mer information om PQL finns i [PQL-översikten](https://experienceleague.adobe.com/en/docs/experience-platform/segmentation/pql/overview).

+++

Om målgruppsdefinitionen för AI-assistenten är korrekt kan du godkänna och gå vidare till nästa steg.

#### Beräkna målgruppens storlek {#estimate}

![Steg 2 av planen, som är att uppskatta den potentiella målgruppens storlek.](./images/audience/plan-step-2.png){align="center" width="80%"}

När de identifierade publikegenskaperna har godkänts beräknas storleken på den potentiella publiken och målgruppsdefinitionsinformationen av AI Assistant.

+++ Svar

![Exempeluppskattningen för den potentiella målgruppen visas. Den uppskattade storleken och segmentdefinitionen visas.](./images/audience/audience-create-estimate.png)

+++

Om den beräknade storleken är korrekt kan du godkänna och gå vidare till nästa steg.

#### Skapa och bevara nya målgrupper {#create}

![Steg 3 av planen, som är att slutföra målgruppen.](./images/audience/plan-step-3.png){align="center" width="80%"}

Slutligen, om egenskaperna och målgruppens storlek ser bra ut, kan du godkänna eller avvisa målgruppens arbete.

+++ Svar

Först kan ni granska den föreslagna målgruppen via det datarutnät som tillhandahålls.

![Granskningsskärmen visas.](./images/audience/audience-create-review.png)

Om målgruppen ser korrekt ut kan du acceptera förslaget genom att välja **[!UICONTROL Create]** för att slutföra målgruppen.

![Det fullständiga förslaget för målgruppen visas.](./images/audience/audience-create-proposal.png)

+++

Publiken är nu skapad.

![Målgruppsförslaget accepterades och målgruppen skapades.](./images/audience/audience-finish-create.png){align="center" width="80%"}

## Nästa steg

När du har läst den här guiden bör du få en bättre förståelse för Audience Agent och vilka funktioner den stöder. Mer information om agenter i Adobe Experience Platform finns i [Agent Orchestrator-översikten](./agent-orchestrator.md).

