---
title: Reseanalys - Översikt över kompetens och användarhandbok för agent
description: Omfattande guide till Journey Agent Analyze-kunskaper som gör det möjligt för användare att analysera marknadsföringsresor, upptäcka problem, identifiera insikter och optimera kundengagemanget.
solution: Journey Optimizer
product: journey optimizer
role: Admin,User,Developer,Leader
source-git-commit: 4bb6da3fe1abee98446df62c94730274e0931493
workflow-type: tm+mt
source-wordcount: '986'
ht-degree: 0%

---


# Reseanalysagent: Kompetensöversikt och användarhandbok

## Översikt

Med Journey Agent kan Journey Optimizer-användare analysera och optimera resor med ett naturligt språkgränssnitt. Med Journey Agent kan man snabbt hitta och lösa scheman- och/eller målgruppskonflikter, upptäcka när man överger en resa och ge insikter eller rekommendationer. Det ger praktikanterna möjlighet att fatta datadrivna beslut, förbättra kundengagemanget och effektivisera resesamordning.

>[!AVAILABILITY]
>
>Journey Agent är tillgängligt för alla kunder som har tillgång till AI Assistant. Du behöver dock följande behörigheter för att kunna använda Journey Agent-funktionerna fullt ut.
>
>**Visa resor**: Med den här behörigheten kan du använda Journey Agent för att visa insikter om resan direkt i AI Assistant.
>
>**Hantera resor**: Med behörigheten Till kan du använda Journey Agent för att skapa nya resor direkt i AI Assistant.
>
>**Visa segment**: Med den här behörigheten kan du använda Journey Agent för att visa insikter om målgrupperna direkt i AI Assistant.
>
>**Hantera segment**: Med behörigheten kan du använda Journey Agent för att skapa nya målgrupper direkt i AI Assistant.

![Exempel för AJO Agent](./images/ajo-agent/ajo-agent-sample.png)

## Användningsexempel

### Viktiga användningsexempel för Journey Agent Analytics

Journey Agent Analyze erbjuder en rad funktioner som kan utnyttjas för att optimera marknadsföringen:

1. **Resebortfallsanalys**

   - Identifiera var och varför kunderna faller bort under en resa.
   - Upptäck mönster i kundbeteenden som leder till bortfall.
   - Använd insikter för att förfina resedesignen och förbättra kundlojaliteten.

1. **Analys av kundtjänstöverlappning**

   - Analysera hur olika målgrupper överlappar olika resor.
   - Förhindra målgruppsutmattning orsakad av överdrivet målinriktad marknadsföring.
   - Optimera segmenteringen för att säkerställa ett balanserat engagemang.

1. **Överlappningsanalys för transportschema**

   - Identifiera tidskonflikter mellan schemalagda resor för samma målgrupp.
   - Undvik överkommunikation och förbättra effektiviteten i planeringen.
   - Maximera publikens påverkan genom att säkerställa att resorna går som de ska vid optimala tidpunkter.

1. **Driftsinsikter**

   - Promptbaserade reseinsikter - få operativa insikter om resor, dvs.&quot;visa mig alla resor live&quot;.

För var och en av dessa analyser identifierar agenten inte bara problem utan tillhandahåller även **användbara rekommendationer för att åtgärda dem**.


## Kompetens inom och utanför omfång

### **I scope**

Följande funktioner stöds av Journey Agent Analyze:

- **Reaktiva frågor**: Tillåter användare att ställa specifika frågor om reseprestanda, målgruppsanvändning och schemaläggningskonflikter.
- **Integrering med andra agenter**: Samarbetar med Audience Agent och Data Insights Agent för djupgående analyser.
- **Åtgärdsstruktur för agentsvar**: resonemang (förklara logiken), analyssammanfattning (framhäv viktiga punkter), felinformation (beskriv problemet) och rekommendation (föreslå nästa steg).

### **Odefinierat**

Följande funktioner stöds för närvarande inte:

- **Automatiserad reseskapande**
- **Analysidentifiering i realtid**
- **Kanalerna överlappar**
- **Resepostanalys**
- **Analys av tekniska problem**
- **Trötthetsanalys**

## Exempelfrågor/Exempelfrågor

### Vanliga frågor om reseanalys

Här är exempel på användbara tips som användare kan använda för att utforska, övervaka och felsöka sina resor.

### Frågor om reselivscykel

- &quot;När publicerades [Resensnamn]?&quot;
- &quot;När stoppades [Resensnamn]?&quot;
- &quot;Visa alla resor som för närvarande är i testläge&quot;

### Resursfrågor för resa

- &quot;Hur många direktresor har jag?&quot;
- &quot;Ge mig en lista över alla schemalagda återkommande resor och deras förväntade körtider.&quot;

### Målgrupps- och reseinsikter

- &quot;Vilka målgrupper används i fler än X resor?&quot;
- &quot;Visa alla resor som använder målgruppen [målgruppsnamn].&quot;

### Bortfallsanalys

- &quot;Jag vill analysera bortfallet per nod för den fjärde resan i juli-kampanjen.&quot;
- &quot;Utför en falloutanalys för resa Fjärde juli-kampanjen.&quot;
- &quot;Vad är förlust av profiler under resan Fjärde juli-kampanjen?&quot;
- &quot;Visa var användarna faller bort på resa Fjärde juli-kampanjen.&quot;

### Fråga om konfliktanalys

Använd dessa uppmaningar för att analysera potentiella konflikter mellan resor, inklusive schemaläggning och målgruppsöverlappningar:

- &quot;Kan du göra en omfattande analys av konflikter för vår resa [Resensnamn] med konflikttypsinformation (schemaläggning/målgrupp) med live/pågående resor?&quot;
- &quot;Gör en schemaläggningskonfliktanalys för resan [Resursnamn] med konflikttypsinformation.&quot;
- &quot;Gör en publiköverlappningsanalys för resan [Resursnamn] med konflikttypsinformation.&quot;
- &quot;Finns det några schemaläggningskonflikter för resan [Resensnamn]?&quot;
- &quot;Visa att målgruppen överlappar konflikter för resan [Resensnamn].&quot;
- &quot;Analysera alla konflikter för resan [Resensnamn] med andra direktresor.&quot;
- &quot;Vilka är de aktuella konflikterna för resan [Resensnamn]?&quot;
- &quot;Kontrollera om resan [Resensnamn] har en målgruppskonflikt med andra resor.&quot;
- &quot;Kontrollera om det finns schemaläggningskonflikter för resan [Resensnamn].&quot;
- &quot;Jag vill veta mer om alla resekonflikter för [resenamn].&quot;
- &quot;Finns det några resor som är i konflikt med [Resensnamn] efter schema eller målgrupp?&quot;
- &quot;Identifiera konflikttyper för resan [Resensnamn] jämfört med pågående resor.&quot;
- &quot;Visa överlappande målgrupper för resan [Resensnamn] och andra resor.&quot;
- &quot;Högdagerplaneringen överlappar mellan resan [Resensnamn] och direktresor.&quot;
- &quot;Körs resan [Resensnamn] i konflikt med någon annan resa?&quot;
- &quot;Identifiera och visa konflikter för [resenamn].&quot;
- &quot;Rapportera alla typer av konflikter för resan [Resensnamn].&quot;
- &quot;Ge mig en konfliktuppdelning (schemaläggning och målgrupp) för [resenamn].&quot;
- &quot;Har [Resensnamn] några konflikter som kan påverka prestanda?&quot;
- &quot;Finns det några aktiva konflikter som påverkar [Resensnamn]?&quot;
- &quot;Visa resor i konflikt med [Resensnamn] efter schema eller målgrupp.&quot;
- &quot;Har resan [Resensnamn] utlöst några varningsmeddelanden om konflikter?&quot;
- &quot;Hitta potentiella målgruppskonflikter för resan [Resensnamn].&quot;
- &quot;Analysera konfliktrisken för resan [Resensnamn].&quot;
- &quot;Ange konfliktdiagnostik för [Resensnamn].&quot;

## Bästa praxis

### Fråga efter bästa praxis

Så här maximerar du effektiviteten i Journey Agent Analyze:

1. **Var specifik**: Använd tydliga och koncisa uppmaningar för att få riktade insikter. I stället för att fråga&quot;Vad är mina resor?&quot; anger du&quot;Lista alla resor som skapades den senaste månaden&quot;.
1. **Kombinera insikter**: Integrera insikter från Audience Agent och Data Insights Agent för en helhetsbild av kundresan.
1. **Interaktiv förfining**: Använd bortfalls- och överlappningsanalys för att iterativt förfina reseutformning och planering.

### Konfigurera bästa praxis

- **Definiera tydliga mål**: Innan du analyserar resor måste du fastställa tydliga mål (t.ex. förbättra kundlojalitet, öka konverteringarna).
- **Övervaka regelbundet**: Schemalägg regelbundna granskningar av reseprestanda för att identifiera trender och avvikelser.
- **Optimera segmentering**: Kontrollera att målgruppssegmenteringen är balanserad för att undvika trötthet och maximera engagemanget.

