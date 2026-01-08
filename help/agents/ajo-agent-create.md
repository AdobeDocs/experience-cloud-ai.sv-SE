---
title: Resa - skapa agent - Kompetensöversikt
description: Lär dig hur du använder Journey Agent Create för att skapa marknadsföringsresor med hjälp av naturliga språkfrågor i Journey Optimizer.
solution: Journey Optimizer
product: journey optimizer
role: Admin,User,Developer
feature: AI Assistant
topic: Administration
level: Beginner
source-git-commit: 864002185f3745ca76180af192f616d1e5da0791
workflow-type: tm+mt
source-wordcount: '1068'
ht-degree: 0%

---


# Resa - Skapa agent: Kompetensöversikt och användarhandbok

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

