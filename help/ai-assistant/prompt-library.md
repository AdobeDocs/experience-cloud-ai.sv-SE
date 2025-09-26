---
title: AI Assistant Prompt Library
description: Lär dig mer om de olika typer av uppmaningar och uppmaningsmönster som du kan använda när du frågar i AI Assistant.
source-git-commit: 4bb6da3fe1abee98446df62c94730274e0931493
workflow-type: tm+mt
source-wordcount: '811'
ht-degree: 0%

---

# AI Assistant Prompt Library

Läs den här guiden för olika typer av frågor som du kan använda i AI Assistant.

## Audience Agent

I följande avsnitt visas exempeluppmaningar som du kan använda med Audience Agent för att utforska och analysera dina målgrupper. Det handlar om olika sätt att undersöka målgruppsegenskaper, upptäcka dubbletter av målgrupper, hämta målgruppsstorlekar och övervaka betydande förändringar i målgruppens storlek över tid. Använd dessa tips för att få djupare insikter och upprätthålla kvaliteten på era målgruppsdata.

### Utforska konversationsmålgrupper

- &quot;Visa mig fält för välbärgade köpare.&quot;
- &quot;Vilka målgrupper har inte aktiverats eller använts i någon kampanj de senaste 30 dagarna?&quot;
- &quot;Ange alla målgrupper som har mappats till nya destinationer de senaste tre månaderna.&quot;

### Identifiera duplicerade målgrupper

- &quot;Har jag någon publik med identiska eller liknande beskrivningar?&quot;
- &quot;Identifiera målgrupper som har samma regler men olika namn.&quot;
- &quot;Visa alla målgrupper som har samma regler men olika aktiveringsmål.&quot;

### Hämta målgruppsstorlek

- &quot;Vilken är den nuvarande storleken på min publik &quot;Gold-star Members in California_f153e1&quot;?&quot;
- &quot;Vad är min största publik?&quot;

### Upptäck betydande förändringar i målgruppens storlek

- &quot;Vilka målgrupper har ökat i storlek med över 20 % den senaste veckan?&quot;
- &quot;Vilka målgrupper har minskat med över 15 % den senaste månaden?&quot;
- &quot;Vilken är min snabbast växande publik?&quot;

## Data Insights Agent

Följande exempeluppmaningar kan användas tillsammans med Data Insights Agent för att analysera dina data, identifiera trender och identifiera åtgärdbara insikter.

### Datavisualisering

- &quot;Visa mig vinst i september.&quot;
- &quot;Trendbeställningar i september.&quot;
- &quot;Visa intäkter per region i september.&quot;
- &quot;Inkomstens andel per produktkategori.&quot;
- &quot;Beställningar per veckodag, från januari till maj.&quot;
- &quot;Visa order efter kön, från mars till juni.&quot;
- &quot;Vad är vinsten för SKU:er från februari till maj.&quot;
- &quot;Intäkter efter butiksnamn i september.&quot;
- &quot;Vad var mina tio största SKU:er med vinst i september?&quot;
- &quot;Andel inköp per månad på året.&quot;
- &quot;Total vinst i september.&quot;

## Journey Agent

Följande exempeluppmaningar kan användas tillsammans med Journey Agent för att hjälpa dig att analysera resans livscykler, hantera reseresurser, få insikter om målgrupps- och reseförhållanden och upptäcka konflikter mellan resor. Använd de här anvisningarna för att optimera er resesamordning och lösa problem effektivt.

### Frågor om reselivscykel

- &quot;När publicerades {JOURNEY_NAME}?&quot;
- &quot;När stoppades {JOURNEY_NAME}?&quot;
- &quot;Visa alla resor som för närvarande är i testläge&quot;

### Resursfrågor för resa

- &quot;Hur många direktresor har jag?&quot;
- &quot;Ge mig en lista över alla schemalagda återkommande resor och deras förväntade körtider.&quot;

### Målgrupps- och reseinsikter

- &quot;Vilka målgrupper används i fler än X resor?&quot;
- &quot;Visa alla resor som använder målgruppen {AUDIENCE_NAME}.&quot;

### Fråga om konfliktanalys

Använd dessa uppmaningar för att analysera potentiella konflikter mellan resor, inklusive schemaläggning och målgruppsöverlappningar:

+++Välj om du vill visa listan

- &quot;Kan du göra en omfattande analys av konflikter för vår resa {JOURNEY_NAME} med konflikttypsinformation (schemaläggning/målgrupp) med live-/pågående resor?&quot;
- &quot;Gör en schemaläggningskonfliktanalys för resan {JOURNEY_NAME} med konflikttypsinformation.&quot;
- &quot;Gör en publiköverlappningsanalys för resan {JOURNEY_NAME} med konflikttypsinformation.&quot;
- &quot;Finns det några schemaläggningskonflikter för resan {JOURNEY_NAME}?&quot;
- &quot;Visa mig att målgruppen överlappar konflikter för resan {JOURNEY_NAME}.&quot;
- &quot;Analysera alla konflikter för resan {JOURNEY_NAME} med andra direktresor.&quot;
- &quot;Vilka är de aktuella konflikterna för resan {JOURNEY_NAME}?&quot;
- &quot;Kontrollera om resan {JOURNEY_NAME} har en målgruppskonflikt med andra resor.&quot;
- &quot;Kontrollera om det finns schemaläggningskonflikter för resan {JOURNEY_NAME}.&quot;
- &quot;Jag vill veta mer om alla resekonflikter för {JOURNEY_NAME}.&quot;
- &quot;Finns det några resor som är i konflikt med {JOURNEY_NAME} efter schema eller målgrupp?&quot;
- &quot;Identifiera konflikttyper för resan {JOURNEY_NAME} jämfört med pågående resor.&quot;
- &quot;Visa överlappande målgrupper för resan {JOURNEY_NAME} och andra resor.&quot;
- &quot;Högdagerplaneringen överlappar mellan resan {JOURNEY_NAME} och direktresorna.&quot;
- &quot;Körs resan {JOURNEY_NAME} i konflikt med någon annan resa?&quot;
- &quot;Identifiera och visa konflikter för {JOURNEY_NAME}.&quot;
- &quot;Rapportera alla typer av konflikter för resan {JOURNEY_NAME}.&quot;
- &quot;Ge mig en konfliktuppdelning (schemaläggning och målgrupp) för {JOURNEY_NAME}.&quot;
- &quot;Har {JOURNEY_NAME} några konflikter som kan påverka prestanda?&quot;
- &quot;Finns det några aktiva konflikter som påverkar {JOURNEY_NAME}?&quot;
- &quot;Visa resor i konflikt med {JOURNEY_NAME} efter schema eller målgrupp.&quot;
- &quot;Har resan {JOURNEY_NAME} utlöst några konfliktvarningar?&quot;
- &quot;Hitta potentiella målgruppskonflikter för resan {JOURNEY_NAME}.&quot;
- &quot;Analysera konfliktrisken för resan {JOURNEY_NAME}.&quot;
- &quot;Ange konfliktdiagnostik för {JOURNEY_NAME}.&quot;

+++

## Produktsupportagent

Produktsupportagenten hjälper dig att felsöka problem, skapa supportärenden och spåra status för dina supportärenden. Använd följande exempeluppmaningar för att få hjälp.

### Felsökningshjälp

- &quot;Varför skiljer sig antalet profiler på kontrollpanelen för licensanvändning och Experience Platform hemsida?&quot;
- &quot;Vilka är orsakerna till att en resa inte triggas?&quot;
- &quot;Hur skapar Adobe Experience Platform realtidsupplevelser?&quot;
- &quot;Hur konfigurerar och använder man varningar i Adobe Experience Platform?&quot;
- &quot;Vad är gränsen för batchsegmenteringsjobb i Adobe Experience Platform Activation?&quot;
- &quot;Vad är den genomsnittliga gränsen för detaljrikedom i Adobe Experience Platform Activation?&quot;

### Skapa supportärenden

- &quot;Skapa en supportanmälan.&quot;
- &quot;Kan du hjälpa mig att skapa en supportbiljett?&quot;

### Spåra ärendestatus

- &quot;Vad är det senaste i mitt ärende E-12345?&quot;
- &quot;Vad är uppdateringen av biljett E-67890?&quot;

