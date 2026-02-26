---
title: Adobe Experience Platform Agent Orchestrator
description: Läs om Adobe Experience Platform Agent Orchestrator.
source-git-commit: 3f5276ffe26a25367e6ac125475bb63a98a1b338
workflow-type: tm+mt
source-wordcount: '839'
ht-degree: 8%

---

# Adobe Experience Platform Agent Orchestrator

Adobe Experience Platform Agent Orchestrator är det nya agentiska lagret i Adobe Experience Platform. Experience Platform Agent Orchestrator är utformat för att utnyttja Experience Platform omfattande data och kundupplevelser och driver intelligensen och resonemanget bakom specialbyggda Adobe Experience Platform Agents, vilket gör det möjligt för dem att fatta komplexa beslut och lösa problem snabbt och i stor skala - allt med mänsklig tillsyn. När du ställer frågor eller begär hjälp via ett naturligt språk i ett konversationsgränssnitt som AI-assistenten, uppmanar Agent Orchestrator automatiskt våra specialistrepresentanter att ge dig rätt svar. Agent Orchestrator kommer ihåg er konversationshistorik, vilket gör att ni kan bygga vidare på tidigare frågor på ett naturligt sätt utan att behöva upprepa sammanhanget, och kombinerar insikter från olika agenter för att ge er tydliga, enhetliga svar.

Du kan slutföra komplicerade kompletta arbetsflöden genom ett intuitivt konversationsgränssnitt utan att behöva veta vilka agenter som arbetar bakom kulisserna. Systemet förstår era mål, skapar stegvisa planer och anpassar strategin efter behov utifrån din feedback. I ditt samtal i AI Assistant kan du utforska Agent Orchestrator resonemangspanel för att se hur tankeprocessen går steg för steg och förstå hur dina förfrågningar hanteras.

>[!SLIDE](agent-orchestrator-overview)

Läs det här dokumentet om du vill veta mer om Agent Orchestrator.

## Komponenter i Agent Orchestrator {#components}

Agent Orchestrator består av flera nyckelkomponenter, bland annat AI Assistant-gränssnittet, en resonemangsmotor för beslutsfattande och planering, specialiserade Adobe Experience Platform-agenter och en kunskapsbas som ger tillgång till relevant information.

![Marknadsföringsarkitekturen för Agent Orchestrator.](./images/agent-orchestrator/agentic-architecture.png)

### AI Assistant - konversationsgränssnitt {#ai-assistant}

AI Assistant är en intelligent, naturlig konverteringsupplevelse som gör det möjligt för användare som använder aktiverade Experience Cloud-program att utnyttja GenAI- och Agentic AI-funktioner, vars bredd är beroende av vilka Experience Cloud-program som licensieras av kunderna. Läs [guiden om åtkomst till AI Assistant](https://experienceleague.adobe.com/en/docs/experience-platform/ai-assistant/access) om du vill låsa upp åtkomst.

Mer information finns i [Gränssnittsguiden för AI-assistenten](../ai-assistant/ai-assistant-ui.md).

### Reassionsmotor {#reasoning-engine}

Reasonmotorn tolkar era mål baserat på era naturliga språkinställningar, kontrollerar begränsningar eller krav och skapar stegvisa planer som hjälper er att nå era mål. Till skillnad från enkla fråge- och svarssystem kan de justera sina planer allt eftersom de förändras och gå tillbaka och testa olika strategier om det behövs. Planerna som skapas visas i AI Assistant-gränssnittet så att du kan se och följa processen samt ingripa om det behövs.

### Adobe Experience Platform Agents {#agents}

Adobe Experience Platform Agents är en specialbyggd gruppering av AI-agenter som är skickliga på att leverera vanliga jobb över kundupplevelsedomäner. Nedan finns en lista över Adobe Experience Platform Agents som för närvarande är tillgängliga i Experience Cloud-program:

| Agent | Information | Program som stöds |
| --- | --- | --- |
| [Audience Agent](audience.md) | Med Audience Agent kan ni visa insikter om målgrupper, inklusive att identifiera betydande förändringar av målgruppsstorlek, identifiera duplicerade målgrupper, utforska ert målgruppslager och ta fram era målgruppers storlek. | <ul><li>Real-Time CDP</li><li>Adobe Journey Optimizer</li></ul> |
| [Agenten för datainsikter](https://experienceleague.adobe.com/en/docs/analytics-platform/using/cja-overview/cja-b2c-overview/data-analysis-ai) | Data Insights Agent, som är tillgängligt från AI Assistant i Customer Journey Analytics, är en generativ AI-konversationsagent som snabbt och effektivt besvarar frågor om dina data. Det bygger upp relevanta visualiseringar i Analysis Workspace med komponenter från datavyn och med era faktiska data. | Customer Journey Analytics |
| [Experimenteringsagent](./agent-experiment.md) | Experimentation Agent hjälper teamen att lära sig snabbare genom att analysera experimentresultat, förutsäga påverkan och föreslå nya experiment. Det centraliserar gamla och aktiva experiment så att ni kan bygga vidare på det ni redan lärt er, hitta luckor och prioritera vad som ska testas härnäst. | Adobe Journey Optimizer Experimentation Accelerator |
| [Journey Agent](./ajo-agent.md) | Med Journey Agent kan Adobe Journey Optimizer-användare skapa, analysera och optimera resor med ett naturligt språkgränssnitt. Med Journey Agent kan ni snabbt skapa resor, upptäcka och lösa schemaläggnings- eller målgruppskonflikter, analysera prestanda och bortfall samt identifiera högpresterande resor som kan återskapas för framtida kampanjer. Det hjälper er att fatta datadrivna beslut, förbättra kundengagemanget och effektivisera resesamordning. | Adobe Journey Optimizer |
| [Produktsupportagent](product-support.md) | Product Support Agent är en självbetjäningsfunktion för felsökning och felsökning som hjälper dig att felsöka Adobe Experience Platform funktioner och program utan att behöva lämna arbetsflödena. Supportadministratörer kan skapa kundsupportbiljetter i sitt sammanhang utifrån dina AI Assistant-interaktioner och du kan kontrollera biljettuppdateringar via AI Assistant. | <ul><li>Adobe Experience Platform</li><li>Real-Time CDP</li><li>Adobe Journey Optimizer</li><li>Adobe Journey Optimizer B2B edition</li><li>Customer Journey Analytics</li><li>Adobe Experience Manager</li></ul> |

Mer information om tillgängligheten av agenter i Experience Cloud-program finns i [AI-dokumentationen för agenter i Experience Cloud ](https://experienceleague.adobe.com/en/docs/core-services/interface/features/agentic-ai).

### Kunskapsbas {#knowledge-base}

Kunskapsbasen ger agenterna säker tillgång till kundanalys via strukturerade och ostrukturerade datakällor, inklusive Adobe produktdokumentation, kundmetadata om affärsobjekt och analysdata.

## Åtkomst {#access}

Alla användare har tillgång till AI Assistant och tillhörande Experience Platform-agenter.

* **Adobe Experience Manager**: Din administratör måste ge dig behörighet att komma åt AI Assistant via [Adobe Admin Console](https://helpx.adobe.com/se/enterprise/using/admin-console.html).

* **Customer Journey Analytics**: Din administratör måste ge dig behörighet att komma åt AI Assistant via [Customer Journey Analytics Access Control](https://experienceleague.adobe.com/en/docs/analytics-platform/using/technotes/access-control). På så sätt kan du ställa frågor om produktkunskap och datainsikter.

>[!NOTE]
>
>Frågor om driftsinsikter är inte tillgängliga för Customer Journey Analytics och därför gäller inga ytterligare behörigheter.
