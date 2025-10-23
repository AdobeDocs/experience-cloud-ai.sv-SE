---
title: AI i Experience Cloud-program
description: Läs om hur Experience Cloud-program använder generativ AI (GenAI), AI Assistant och agentisk AI.
source-git-commit: a19c891d1a17c9112aff3d9a52daa94ad162a553
workflow-type: tm+mt
source-wordcount: '802'
ht-degree: 11%

---

# AI i Experience Cloud

Välkommen till den omfattande guiden för AI-funktioner i olika Adobe Experience Cloud-program. Dokumentationen beskriver hur generativa AI-, AI Assistant- och Adobe-agenter integreras i dina Experience Cloud-arbetsflöden för att öka produktiviteten och förbättra beslutsfattandet.

## Vad ingår i den här guiden

### AI-assistenten

[AI Assistant](./ai-assistant/ai-assistant-ui.md) är ett intelligent, generativt AI-verktyg för konversationer som ökar produktiviteten och omdefinierar arbetet i Adobe Experience Platform-baserade program. Användarna kan få produktkunskaper, felsöka problem och hitta driftsinsikter via naturliga språktips. Du kan också använda AI Assistant för att komma åt Adobe Experience Platform Agents och andra AI-funktioner.

**Viktiga funktioner:**

- **Konversationsgränssnitt**: Du kan välja mellan ett helskärmsgränssnitt och ett rälsvy som passar dina arbetsflödesinställningar.
- **Identifieringsfrågor**: AI Assistant tillhandahåller förkonfigurerade frågor som är ordnade efter kategorier som Lär dig, Analysera och Optimera.
- **Kontextinställning**: Du kan konfigurera inställningarna för programmet, sandlådan och datavyn så att du kan ta emot svar som är anpassade efter dina behov.
- **Datavisualisering**: Verktyget innehåller interaktiva diagram och diagram som gör att du kan få insikter från dina data.
- **Svarsverifiering**: Alla svar innehåller källcitat, förklaringar till AI-resonemang och mekanismer för att ge feedback.


### Agent Orchestrator

[Adobe Experience Platform Agent Orchestrator](./agents/agent-orchestrator.md) är det nya officiella lagret i Adobe Experience Platform. Experience Platform Agent Orchestrator är utformat för att utnyttja plattformens omfattande data och kundupplevelser. Den driver intelligens och resonemang bakom specialbyggda Adobe Experience Platform-agenter, vilket möjliggör för dem att fatta komplexa beslut och lösa problem snabbt och i stor skala – allt med mänsklig tillsyn. När du ställer frågor eller begär hjälp via ett naturligt språk i ett konversationsgränssnitt som AI-assistenten, uppmanar Agent Orchestrator automatiskt våra specialistrepresentanter att ge dig rätt svar. Agent Orchestrator kommer ihåg er konversationshistorik, vilket gör att ni kan bygga vidare på tidigare frågor på ett naturligt sätt utan att behöva upprepa sammanhanget, och kombinerar insikter från olika agenter för att ge er tydliga, enhetliga svar.

**Kärnkomponenter:**

- **Reasoning-motor**: Skapar stegvisa planer och justerar strategier efter behov
- **Specialiserade agenter**: Specialbyggda agenter för specifika uppgifter och domäner
- **Knowledge Base**: Säker åtkomst till affärsinformation och -dokumentation

### Specialiserade agenter

#### Audience-agent

Audience Agent ger insikter om målgrupper:

- Identifiera stora förändringar i målgruppens storlek.
- Identifiera duplicerade målgrupper.
- Utforska målgruppslager.
- Hämtar publikstorlekar.

#### Data Insights Agent

Finns i Customer Journey Analytics, Data Insights Agent:

- Svar på frågor om era data på ett naturligt språk.
- Bygger relevanta visualiseringar i Analysis Workspace.
- Använder komponenter från datavyn och faktiska data.

#### Journey Agent

Med Journey Agent kan man

- Analysera och optimera resorna med det naturliga språket.
- Upptäck och lös schemaläggnings- eller målgruppskonflikter.
- Analysera prestanda och bortfallspunkter.

#### Produktsupportagent

Använd Product Support Agent för felsökning och felsökning:

- Felsök Adobe Experience Platform funktioner utan att behöva lämna arbetsflödena.
- Skapa supportärenden med hjälp av AI Assistant-interaktioner.
- Kontrollera biljettuppdateringar via AI Assistant.

## Komma igång

### Åtkomstkrav

Om du vill använda AI Assistant och Experience Platform Agents måste din Adobe-administratör ställa in rätt behörigheter:

- Om du vill använda AI Assistant i Real-Time CDP och Adobe Journey Optimizer behöver du behörigheten&quot;Aktivera AI Assistant&quot; samt behörigheten&quot;Visa driftsinsikter&quot; för att få tillgång till operativa frågor.
- Åtkomsten till AI Assistant i Customer Journey Analytics hanteras via Customer Journey Analytics Access Control, som gör att du kan ställa frågor om både produktkunskap och datainsikter.
- För Adobe Experience Manager kan du komma åt AI Assistant via behörigheter som anges i Adobe Admin Console.

### Integritet och säkerhet

AI Assistant har tagits fram med sekretess, säkerhet och styrning i framkanten:

- Inga personuppgifter används för utbildning.
- Alla befintliga åtkomstkontrollprinciper respekteras.
- HIPAA-förberedd när den används tillsammans med Adobe Experience Platform Healthcare Shield.
- 30-dagars bevarandeprincip för interaktionsloggar.
- Sandlådespecifik dataisolering.

## Bästa praxis

Följ dessa riktlinjer för att få ut så mycket som möjligt av din AI Assistant-upplevelse:

- **Var specifik** i dina uppmaningar för att få målinriktade och relevanta insikter från AI-assistenten.
- **Verifiera svar** genom att granska källcitaten och de förklaringar som tillhandahålls av AI-assistenten.
- **Använd kontextinställning** för att kontrollera att de mest relevanta datakällorna används för dina frågor.
- **Ge feedback** för att förbättra AI-assistentens prestanda och exakthet över tid.
- **Kombinera insikter** från flera agenter för att få en mer omfattande och detaljerad analys.

## Juridiska överväganden

När du använder AI Assistant är det viktigt att du är medveten om viktiga juridiska och praktiska överväganden. För närvarande stöder AI Assistant endast svar på engelska. Var alltid försiktig med att verifiera informationen som tillhandahålls, eftersom språkmodeller ibland kan göra misstag. Använd de resonanssteg och förklaringar som ingår i svaren för att få en bättre förståelse för de svar ni får. Om du stöter på problem eller felaktigheter ska du skicka feedback för att hjälpa till att förbättra AI Assistant över tid.
