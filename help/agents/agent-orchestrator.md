---
title: Adobe Experience Platform Agent Orchestrator
description: Läs om Adobe Experience Platform Agent Orchestrator.
source-git-commit: c9909616697ef319a307b5c8a1ee135204347844
workflow-type: tm+mt
source-wordcount: '916'
ht-degree: 0%

---

# Adobe Experience Platform Agent Orchestrator

Adobe Experience Platform Agent Orchestrator är det nya agakta lagret i Adobe Experience Platform. Experience Platform Agent Orchestrator är utformat för att utnyttja plattformens omfattande data och kundupplevelser och driver intelligens och resonemang bakom specialbyggda Adobe Experience Platform-agenter som gör det möjligt för dem att fatta komplexa beslut och lösa problem snabbt och i stor skala - allt med mänsklig tillsyn. När du ställer frågor eller begär hjälp via ett naturligt språk i ett konversationsgränssnitt som AI Assistant, uppmanar Agent Orchestrator automatiskt våra specialistrepresentanter att ge dig rätt svar. Agent Orchestrator kommer ihåg er konversationshistorik, vilket gör att ni kan bygga vidare på tidigare frågor på ett naturligt sätt utan att behöva upprepa sammanhanget, och kombinerar insikter från olika agenter för att ge er tydliga, enhetliga svar.

Du kan slutföra komplicerade kompletta arbetsflöden genom ett intuitivt konversationsgränssnitt utan att behöva veta vilka agenter som arbetar bakom kulisserna. Systemet förstår era mål, skapar stegvisa planer och anpassar strategin efter behov utifrån din feedback. Du kan utforska tankepanelen för att se hur tankeprocessen går steg för steg och bättre förstå hur dina förfrågningar hanteras. Med Agent Orchestrator kan ni hantera komplexa arbetsflöden och optimera strategier för alla Adobe Experience Cloud-program.

Läs det här dokumentet om du vill veta mer om Agent Orchestrator.

## Komponenter i Agent Orchestrator {#components}

Agent Orchestrator består av flera huvuddelar, bland annat AI Assistant-gränssnittet, en resonemangsmotor för beslutsfattande och planering, specialiserade Adobe Experience Platform-agenter och en kunskapsbas som ger tillgång till relevant information.

![Marknadsföringsarkitekturen för Agent Orchestrator.](./images/agent-orchestrator/agentic-architecture.png)

### AI Assistant - konversationsgränssnitt {#ai-assistant}

AI Assistant är en konversationsupplevelse som du kan använda för att snabba upp arbetsflödena i Adobe-program. Du kan använda AI Assistant för att få en bättre förståelse för produktkunskaper, felsöka problem eller söka i information och hitta operativa insikter. AI Assistant stöder Experience Platform, Real-Time Customer Data Platform, Adobe Journey Optimizer och Customer Journey Analytics. Du kan använda AI Assistant för att komma åt Experience Platform Agents och andra AI-funktioner.

Mer information finns i [gränssnittsguiden för AI-assistenten](../ai-assistant/ai-assistant-ui.md).

### Reassionsmotor {#reasoning-engine}

Reasonmotorn tolkar era mål baserat på era naturliga språkinställningar, kontrollerar begränsningar eller krav och skapar stegvisa planer som hjälper er att nå era mål. Till skillnad från enkla fråge- och svarssystem kan de justera sina planer allt eftersom de förändras och gå tillbaka och testa olika strategier om det behövs. Planerna som skapas visas i AI Assistant-gränssnittet så att du kan se och följa processen samt ingripa om det behövs.

### Adobe Experience Platform Agents {#agents}

| Agent | Information | Program som stöds |
| --- | --- | --- |
| [Audience Agent](audience.md) | Med Audience Agent kan ni visa insikter om målgrupper, inklusive att identifiera betydande förändringar av målgruppsstorlek, identifiera duplicerade målgrupper, utforska ert målgruppslager och ta fram era målgruppers storlek. | <ul><li>Real-Time CDP</li><li>Adobe Journey Optimizer</li></ul> |
| [Agenten för datainsikter](https://experienceleague.adobe.com/en/docs/analytics-platform/using/cja-overview/cja-b2c-overview/data-analysis-ai) | Data Insights Agent, som är tillgängligt från AI Assistant i Customer Journey Analytics, är en generativ AI-konversationsagent som snabbt och effektivt besvarar frågor om dina data. Det bygger upp relevanta visualiseringar i Analysis Workspace med komponenter från datavyn och med era faktiska data. | Customer Journey Analytics |
| Experimentationsagent | Experimentationsagenten hjälper team att lära sig snabbare genom att analysera experimentresultat, förutse påverkan och föreslå nya experiment. Det centraliserar gamla och aktiva experiment så att ni kan bygga vidare på det ni redan lärt er, hitta luckor och prioritera vad som ska testas härnäst. | Adobe Journey Optimizer Experimentation Accelerator |
| [Journey Agent](./ajo-agent-analyze.md) | Med Journey Agent kan Adobe Journey Optimizer-användare skapa, analysera och optimera resor med ett naturligt språkgränssnitt. Med Journey Agent kan ni snabbt skapa resor, upptäcka och lösa schemaläggnings- eller målgruppskonflikter, analysera prestanda och bortfall samt identifiera högpresterande resor som kan återskapas för framtida kampanjer. Det hjälper er att fatta datadrivna beslut, förbättra kundengagemanget och effektivisera resesamordning. | Adobe Journey Optimizer |
| [Produktsupportagent](https://experienceleague.adobe.com/en/docs/experience-platform/ai-assistant/new-features/customer-support) | Product Support Agent är en självbetjäningsfunktion för felsökning och felsökning som hjälper dig att felsöka Adobe Experience Platform funktioner och program utan att behöva lämna arbetsflödena. Supportadministratörer kan skapa kundsupportbiljetter i sitt sammanhang utifrån dina AI Assistant-interaktioner och du kan kontrollera biljettuppdateringar via AI Assistant. | <ul><li>Adobe Experience Platform</li><li>Real-Time CDP</li><li>Adobe Journey Optimizer</li><li>Adobe Journey Optimizer B2B edition</li><li>Customer Journey Analytics</li><li>Adobe Experience Manager</li></ul> |

### Kunskapsbas {#knowledge-base}

Kunskapsbasen ger agenterna säker tillgång till kundanalys via strukturerade och ostrukturerade datakällor, inklusive Adobe produktdokumentation, kundmetadata om affärsobjekt och analysdata.

## Åtkomst {#access}

AI Assistant-begäranden autentiseras med Adobe Identity Management Services. Behörigheterna regleras av Adobe Experience Platform Access Control och Customer Journey Analytics Access Control.

För att få tillgång till konversationsgränssnittet i AI Assistant och använda en eller flera Experience Platform-agenter måste Adobe-administratören ge dig de behörigheter som krävs i användargränssnittet för behörigheter eller i Adobe Admin Console:

* **Real-Time CDP** och **Adobe Journey Optimizer**: Din administratör måste ge dig behörighet **Aktivera AI-assistenten** så att du kan komma åt AI-assistenten. Din administratör måste också ge dig behörighet **Visa användningsinformation** så att du kan ställa frågor om driftsinsikter i AI Assistant. Båda behörigheterna anges av administratören i användargränssnittet för behörigheter.

* **Customer Journey Analytics**: Din administratör måste ge dig behörighet att komma åt AI Assistant via [Customer Journey Analytics Access Control](https://experienceleague.adobe.com/en/docs/analytics-platform/using/technotes/access-control). På så sätt kan du ställa frågor om produktkunskap och datainsikter.

>[!NOTE]
>
>Frågor om driftsinsikter är inte tillgängliga för Customer Journey Analytics och därför gäller inga ytterligare behörigheter.

* **Adobe Experience Manager**: Din administratör måste ge dig behörighet att komma åt AI Assistant via [Adobe Admin Console](https://helpx.adobe.com/enterprise/using/admin-console.html).
