---
title: AI i Experience Cloud-program
description: Läs om hur Experience Cloud-program använder generativ AI (GenAI), AI Assistant och agentisk AI.
source-git-commit: 58cce845f525e7762f32379a8db5791b677ae54f
workflow-type: tm+mt
source-wordcount: '645'
ht-degree: 0%

---

# AI i Experience Cloud

Välkommen till den omfattande guiden för AI-funktioner i olika Adobe Experience Cloud-program. Dokumentationen beskriver hur generativa AI-, AI Assistant- och Adobe-agenter integreras i dina Experience Cloud-arbetsflöden för att öka produktiviteten och förbättra beslutsfattandet.

## Vad ingår i den här guiden

### AI Assistant

[AI Assistant](./ai-assistant/ai-assistant-ui.md) är ett intelligent, generativt AI-verktyg för konversationer som ökar produktiviteten och omdefinierar arbetet i Adobe Experience Platform-baserade program. Användarna kan få produktkunskaper, felsöka problem och hitta driftsinsikter via naturliga språktips. Du kan också använda AI Assistant för att komma åt Adobe Experience Platform Agents och andra AI-funktioner.

**Viktiga funktioner:**

- **Konversationsgränssnitt**: Alternativ för helskärms- och rälsvy för olika arbetsflödesinställningar
- **Identifieringsfrågor**: Förkonfigurerade uppmaningar ordnade efter kategori (Lär dig, Analysera, Optimera)
- **Kontextinställning**: Konfigurera inställningar för program, sandlåda och datavy för riktade svar
- **Datavisualisering**: Interaktiva diagram och diagram för datainsikter
- **Svarsverifiering**: Source-citat, resonemangsförklaringar och feedbackmekanismer

### Agent Orchestrator

[Adobe Experience Platform Agent Orchestrator](./agents/agent-orchestrator.md) är det nya officiella lagret i Adobe Experience Platform. Experience Platform Agent Orchestrator är utformat för att utnyttja plattformens omfattande data och kundupplevelser och driver intelligens och resonemang bakom specialbyggda Adobe Experience Platform-agenter som gör det möjligt för dem att fatta komplexa beslut och lösa problem snabbt och i stor skala - allt med mänsklig tillsyn. När du ställer frågor eller begär hjälp via ett naturligt språk i ett konversationsgränssnitt som AI Assistant, uppmanar Agent Orchestrator automatiskt våra specialistrepresentanter att ge dig rätt svar. Agent Orchestrator kommer ihåg er konversationshistorik, vilket gör att ni kan bygga vidare på tidigare frågor på ett naturligt sätt utan att behöva upprepa sammanhanget, och kombinerar insikter från olika agenter för att ge er tydliga, enhetliga svar.

**Kärnkomponenter:**

- **Reasoning-motor**: Skapar stegvisa planer och justerar strategier efter behov
- **Specialiserade agenter**: Specialbyggda agenter för specifika uppgifter och domäner
- **Knowledge Base**: Säker åtkomst till affärsinformation och -dokumentation

### Specialiserade agenter

#### Audience Agent

Ger insikter om målgrupper, bland annat:

- Identifiera stora förändringar i målgruppens storlek
- Identifiera duplicerade målgrupper
- Utforska målgruppslager
- Hämtar målgruppsstorlek

#### Data Insights Agent

Finns i Customer Journey Analytics:

- Svara på frågor om dina data på ditt naturliga språk
- Bygger relevanta visualiseringar i Analysis Workspace
- Använder komponenter från din datavy och faktiska data

#### Journey Agent

Gör att Journey Optimizer-användare kan:

- Analysera och optimera resorna med det naturliga språket
- Upptäck och lös schemaläggnings- eller målgruppskonflikter
- Analysera prestanda och bortfallspunkter

#### Produktsupportagent

Självbetjänad felsökning och felsökning:

- Felsöka Adobe Experience Platform funktioner utan att behöva lämna arbetsflöden
- Skapa supportärenden i kontext från AI Assistant-interaktioner
- Kontrollera biljettuppdateringar via AI Assistant

## Komma igång

### Åtkomstkrav

Om du vill använda AI Assistant och Experience Platform Agents måste din Adobe-administratör ställa in rätt behörigheter:

- **Real-Time CDP och Adobe Journey Optimizer**: Kräver behörigheten Aktivera AI-assistenten och behörigheten Visa driftsinsikter för operativa frågor
- **Customer Journey Analytics**: Åtkomst via Customer Journey Analytics Access Control för frågor om produktkunskap och datainsikter
- **Adobe Experience Manager**: Åtkomst via Adobe Admin Console

### Integritet och säkerhet

AI Assistant har tagits fram med sekretess, säkerhet och styrning i framkanten:

- Inga personuppgifter används för utbildning
- Alla befintliga åtkomstkontrollprinciper respekteras
- HIPAA-förberedd vid användning med Adobe Experience Platform Healthcare Shield
- 30-dagars bevarandeprincip för interaktionsloggar
- Sandlådespecifik dataisolering

## God praxis

- **Var specifik** i dina uppmaningar för att få riktade insikter
- **Verifiera svar** med källcitat och förklaringar
- **Använd kontextinställning** för att säkerställa relevanta datakällor
- **Ge feedback** för att förbättra prestanda för AI Assistant
- **Kombinera insikter** från flera agenter för omfattande analys

## Juridiska överväganden

- AI Assistant stöder för närvarande endast engelska
- Verifiera alltid svar eftersom språkmodeller kan göra misstag
- Granska de åtgärder och förklaringar som lämnats
- Skicka feedback vid eventuella problem eller felaktigheter

Den här guiden innehåller allt du behöver för att effektivt använda AI-funktionerna i alla dina Experience Cloud-program, från grundläggande interaktioner till avancerad agentsamordning och specialiserade arbetsflöden.

