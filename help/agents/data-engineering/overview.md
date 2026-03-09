---
title: Data Engineering Agent
description: Läs om hur du kan använda Data Engineering Agent.
hide: true
hidefromtoc: true
source-git-commit: 12c61f88b358fc8c357ec4fa373493d6b70d5a06
workflow-type: tm+mt
source-wordcount: '333'
ht-degree: 0%

---

# Data Engineering Agent

&lt;!— DETTA ÄR ETT UTKAST —>

Data Engineering Agent är en Agent Orchestrator-baserad AI-baserad kompilator för datateam i Adobe Experience Platform. Agenten är utformad för att hantera grovjobbet under hela datalängden: datamodellering, onboarding, förberedelse av SQL-data, styrning och livscykelhantering. Med Data Engineering Agent kan ingenjörer och arkitekter arbeta snabbare med högre datakvalitet och mindre manuellt arbete.

Data Engineering Agent är indelat i färdigheter som du kan använda för att optimera dina arbetsflöden.

| Data Engineering Agent färdighet | Beskrivning |
| --- | --- |
| Datainhämtning | <strong>Datakonboarding</strong> stöder batchkällor som S3, Marketo och DLZ (Data Landing Zone). Funktionerna är följande: <ul><li>Ansluta till olika datakällor, bland annat S3, Data Landing Zone och Marketo.</li><li>Profilera källdata (t.ex. distinkta värden, null-värden, dubbletter och grundläggande kvalitetsmått).</li><li>Justera källfält till både standard-XDM-fältgrupper och anpassade fält.</li><li>Föreslå och bygga dataflöden för dataöverföring (t.ex. flytta data från S3 eller Marketo till RTCDP/CJA).</li></ul> |
| Automatiserad datakvalitet och semantisk anrikning | <ul><li>Utför omfattande kvalitetskontroller av data, inklusive att identifiera avvikelser och rapportera giltiga/ogiltiga antal poster.</li><li>Rekommenderar kvalitetsförbättringar som typnormalisering, valutaformatering och ID-borttagning.</li><li>Tillämpar semantisk berikning på scheman baserat på datainsamling och intelligent identifiering av namngivningsmönster.</li><li>Engagerar användare för att bekräfta föreslagna berikningar, vilket säkerställer slutförda och godkända dataändringar.</li></ul> |
| Data Distiller | |
| Datainsamling | |
| Dataverifiering | |

Med Data Engineering Agent kan du säkerställa:

- **Snabbare introduktion**: Minska tiden från veckor med manuell schemamappning och pipeline-konfiguration till timmar med guidad, konversationskonfiguration.
- **Högre datakvalitet**: Färre ogiltiga poster och produktionsincidenter på grund av inbyggd datakvalitetsanalys och semantiska kontroller.
- **Förbättrad styrning och efterlevnad**: Styrningsprinciper bifogas vid designtillfället (etiketter, TTL, identitetshantering) i stället för som en eftertanke.
- **Mer produktiva datateam**: Upprepande SQL-/dataflödesarbete automatiseras så att ingenjörer kan fokusera på design och optimering av högre värden.
- **Bredare självbetjäning**: intressenter som inte är experter kan på ett säkert sätt självbetjäna vanliga förberedelseåtgärder för data med skyddsräcken.