---
title: Journey Agent Översikt och användarhandbok
description: En omfattande guide till Journey Agent som gör det möjligt att skapa, analysera och optimera marknadsföringsresor med ett naturligt språkgränssnitt i Journey Optimizer.
solution: Journey Optimizer
product: journey optimizer
role: Admin,User,Developer,Leader
source-git-commit: 229d349d971ffaba3f2f2fb989e363d96a8d7a70
workflow-type: tm+mt
source-wordcount: '2147'
ht-degree: 0%

---


# Journey Agent: Översikt och användarhandbok

## Introduktion till Journey Agent i Adobe Journey Optimizer

Med Journey Agent kan Journey Optimizer-användare skapa, analysera och optimera marknadsföringsresor med ett naturligt språkgränssnitt. Med Journey Agent kan yrkesutövare snabbt skapa resor, upptäcka och lösa schemaläggnings- eller målgruppskonflikter, analysera prestanda och bortfall samt identifiera högpresterande resor som kan återskapas för framtida kampanjer. Det ger yrkesutövare möjlighet att fatta datadrivna beslut, förbättra kundengagemanget och effektivisera resesamordning.

Journey Agent har två huvudfärdigheter:
- **Resa - skapa agent**: Bygg och konfigurera marknadsföringsresor med hjälp av meddelanden på naturligt språk
- **Reseanalysagent**: Analysera resor, identifiera problem, identifiera insikter och optimera kundengagemang

## Resa - Skapa agent: Kompetensöversikt och användarhandbok

## Översikt

Med Journey Create Agent kan Journey Optimizer-användare skapa och konfigurera marknadsföringsresor med ett naturligt språkgränssnitt. Med Journey Create Agent kan man snabbt skapa resor genom att beskriva kraven i samtal. Agenten effektiviserar framtagningen av resor så att marknadsförarna kan fokusera på strategi istället för teknisk konfiguration.

>[!AVAILABILITY]
>
>Journey Create Agent är tillgänglig för alla kunder som har tillgång till AI Assistant. Du måste dock ha följande behörigheter för att kunna använda funktionerna för Create Agent på resan till fullo:
>
>**Hantera resor**: Med den här behörigheten kan du skapa nya resor direkt i AI Assistant.
>
>**Visa resehändelser, datakällor och åtgärder**: Med den här behörigheten kan AI-assistenten söka genom resehändelser och anpassade åtgärder.
>
>**Visa segment**: Med den här behörigheten kan AI Assistant söka efter målgruppssegment när en resa skapas.
>
>**Hantera segment**: Med den här behörigheten kan du skapa nya målgrupper direkt i AI Assistant.

## Användningsfall

### Viktiga användningsexempel för agenten för att skapa resa

Resans Create Agent-kunskaper erbjuder funktioner som kan utnyttjas för att snabba upp marknadsföringen:

1. **Händelseutlöst skapande av resa**

   - Skapa resor som aktiveras baserat på specifika kundhändelser.
   - Designa automatiska svar på kundaktiviteter i realtid.
   - Bygg skräddarsydda kommunikationsflöden baserat på kundbeteende.

1. **Målgruppsanpassad reseskapande**

   - Bygg resor för specifika målgruppssegment.
   - Designa kommunikationssekvenser i flera steg med strategisk timing.

1. **Affärshändelse utlöste skapandet av en resa**

   - Skapa resor som aktiveras baserat på en viss affärshändelse och rikta sig till en viss målgrupp (t.ex. produkten tillbaka i stock- eller spelpoängsändring)
   - Bygg skräddarsydda kommunikationsflöden baserat på kundbeteende.

1. **Skapa målgruppskompetensresa**

   - Skapa resor som aktiverar som profiler anger eller avslutar en målgruppsdefinition.
   - Bygg skräddarsydda kommunikationsflöden baserat på kundbeteende.

1. **Villkorliga transportflöden**

   - Skapa beslutsgrenar baserat på kundattribut.
   - Designa delade banor som anpassar sig efter kundernas önskemål.

För vart och ett av dessa användningsområden översätter agenten de naturliga språkkraven till strukturerade resekonfigurationer.

## Kompetens inom och utanför omfånget

### **I omfång**

Följande funktioner stöds av Journey Create Agent:

- **Skapa naturliga språkresor**: Används för att beskriva reseflödet på konversationsspråk.
- **Händelsebaserade och målgruppsbaserade resor**: Stöder både utlösarbaserade och schemalagda resetyper, även affärshändelser och målgruppskvalifikationer.
- **Villkorlig logik**: Hanterar beslutsdelning och förgreningar baserat på kundattribut.
- **Flerkanalsmeddelanden**: Stöder push-meddelanden, e-post och SMS-kanaler.
- **Reseplanering**: Konfigurerar startdatum och tidpunkter för schemalagda resor.

### **Odefinierat**

Följande funktioner stöds för närvarande inte:

- **Avancerad reseanalys**
- **Realtidsändringar för resan**
- **Korsresssamordning**
- **A/B-testningskonfiguration**
- **Komplexa dataomvandlingar**
- **Skapa innehållsmeddelande**

## Exempeluppmaningar

### Vanliga uppmaningar för att skapa resor

Här är några exempel på användbara uppmaningar som användare kan använda för att skapa resor.

### Händelseutlösta reseuppmaningar

**Butiksbesöksresa:**

&quot;Skapa en resa som börjar när en användare kommer till min butiksplats. Skicka ett push-meddelande till välkomstanvändare i butiken. Vänta i två dagar och kontrollera om användaren har en giltig e-postadress. Om användaren har en giltig e-postadress skickar du en e-postenkät för att fråga om deras butiksupplevelse. Om användaren inte har en giltig e-postadress skickar du ett push-meddelande för att fråga om registrering.&quot;

**Efterköpsresa:**

&quot;Skapa en resa som börjar när en kund gör ett köp online. Skicka ett push-meddelande som tackar dem för deras köp. Kontrollera sedan om de är lojalitetsmedlemmar. Om användaren är lojalitetsmedlem skickar du ett andra push-meddelande med en rabattkod på 10 %. Om användaren inte är en lojalitetsmedlem skickar du en push-inbjudan om att registrera sig för lojalitetsprogrammet. Vänta i två dagar och skicka en uppföljningspush med en enkät om deras köpupplevelse.&quot;

**Händelsebaserad befordran:**

&quot;Skapa en resa som utlöses när spelpoängen når 50. Skicka ett SMS-meddelande till lojalitetsbelöningsmedlemmar som säger att de är berättigade till ett kostnadsfritt pizzabit från partnersponsorn.&quot;

### Målgruppsanpassade kundkampanjer

**Säsongskampanj:**

&quot;Jag vill skapa en resa som riktar sig mot en publik som arbetar daghem. Jag vill skicka ett mejl som varnar den här publiken för min kommande semesterförsäljning som innehåller en mängd olika viktiga tips. Vänta 3 dagar efter att du skickat det första e-postmeddelandet och skicka ett andra e-postmeddelande med 15 % kupong med fri frakt. Vänta en vecka och skicka sedan ett tredje e-postmeddelande för att visa vår nya sovsäck och tältsamling. Schemalägg resan så att den börjar 20/12.&quot;

**Förmånsuppskattning:**

&quot;Bygg en kundvärvningsresa för SUV-ägare, inklusive ett push-meddelande med ett kostnadsfritt cartvätt-erbjudande och en påminnelse om push-uppdatering om det första meddelandet inte interagerar med inom en dag.&quot;

### Öppna meddelanden

För användare som inte har en viss resa i åtanke:

- &quot;Jag skulle vilja skapa en resa&quot;
- &quot;Hjälp mig att skapa en resa&quot;
- &quot;Skapa en resa åt mig&quot;

Medarbetaren ger vägledning och exempel som hjälper dig att definiera dina resebehov.

## Bästa praxis

### Uppmana till bästa praxis

Så här maximerar du effekten av Journey Create Agent:

1. **Var specifik**: Ange tydliga detaljer om dina resemål, målgrupper och önskade åtgärder. Inkludera information om kanaler, tidsinställningar och villkor.
1. **Ange timing**: Ange tydligt väntetider mellan åtgärder och när resan ska påbörjas.
1. **Definiera villkor**: När du använder villkorslogik kan du förklara villkoren för varje grensökväg.
1. **Inkludera kanaler**: Ange vilka kommunikationskanaler du vill använda (push, email, SMS).
1. **Omnämnande av schemaläggning**: Ange önskat startdatum och önskad starttid för schemalagda resor.
1. **Anpassade åtgärder**: Om du använder anpassade åtgärder i arbetsflödet måste du ange att du använder en anpassad åtgärd tillsammans med det exakta namnet på den anpassade åtgärden. Exempel:
När en användare kommer till min butiksplats skickar du ett välkomstmeddelande med den anpassade åtgärden ExternalPush. Vänta i två dagar och skicka sedan ett uppföljningsmeddelande med egen åtgärd ExternalEmail med en enkät vid besöket.
1. **Validera uttryck**: Kontrollera och validera alla uttryck som skapas i Journey Agent för att se till att rätt fält och värden används.

### Konfigurera bästa praxis

- **Definiera tydliga mål**: Innan du skapar resor måste du fastställa tydliga mål (förbättra kundlojalitet, öka konverteringsgraden, öka engagemanget).
- **Förbered målgrupper**: Kontrollera att målgrupperna redan har skapats och segmenterats korrekt.
- **Planera meddelandeinnehåll**: Ha din meddelandestrategi definierad innan resan skapas.
- **Fundera på kundupplevelsen**: Designreseflöden som respekterar kundernas preferenser och undviker överkommunikation.

## Reseanalysagent: Kompetensöversikt och användarhandbok

## Översikt

Med Journey Agent kan Journey Optimizer-användare analysera och optimera resor med ett naturligt språkgränssnitt. Med Journey Agent kan man snabbt hitta och lösa scheman- och/eller målgruppskonflikter, upptäcka när man överger en resa och ge insikter eller rekommendationer. Det ger praktikanterna möjlighet att fatta datadrivna beslut, förbättra kundengagemanget och effektivisera resesamordning.

Läs mer och upptäck agenten i den här [översikten](https://experienceleague.adobe.com/en/slides/journey-agent-overview).

>[!AVAILABILITY]
>
>Journey Agent är tillgängligt för alla kunder som har tillgång till AI Assistant. Du måste dock ha följande behörigheter för att kunna använda Journey Agent funktioner fullt ut:
>
>**Visa resor**: Med den här behörigheten kan du visa insikter om resan direkt i AI Assistant.
>
>**Hantera resor**: Med behörighet kan du skapa nya resor direkt i AI Assistant.
>
>**Visa segment**: Med den här behörigheten kan du visa insikter om målgrupperna direkt i AI Assistant.
>
>**Hantera segment**: Med behörighet kan du skapa nya målgrupper direkt i AI Assistant.

![Exempel för AJO Agent](./images/ajo-agent/ajo-agent-sample.png)

## Användningsfall

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

## Presentationer och bilder

>[!NOTE]
>
>Bilder och presentationsmaterial för Journey Agent finns här. Kom tillbaka snart för uppdateringar.
