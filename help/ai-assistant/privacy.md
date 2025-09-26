---
title: Integritet, säkerhet och styrning i AI Assistant
description: Läs mer om sekretess-, säkerhets- och styrningsrutiner för AI Assistant.
source-git-commit: 4bb6da3fe1abee98446df62c94730274e0931493
workflow-type: tm+mt
source-wordcount: '298'
ht-degree: 0%

---

# Integritet, säkerhet och styrning i AI Assistant

AI Assistant i Adobe Experience Platform har tagits fram med sekretess, säkerhet och styrning i framkanten.

Läs det här dokumentet om du vill veta mer om funktioner som är inriktade på kundförtroende och som du kan förvänta dig av AI Assistant:

* Inga personuppgifter används av AI Assistant idag, inte ens i utbildningssyfte.
* AI Assistant känner inte till konsumentdata.
* Alla befintliga [åtkomstkontrollprinciper](https://experienceleague.adobe.com/en/docs/experience-platform/access-control/home) respekteras av AI Assistant.

   * Alla nya attributbaserade åtkomstkontrollprinciper återspeglas i AI Assistant efter högst 24 timmar&amp;stämpel;ast;

* Du måste ha explicit behörighet att interagera med AI Assistant.

   * Du kan ange behörigheter på olika sätt för Experience Platform och Journey Optimizer med [behörighetsgränssnittet](https://experienceleague.adobe.com/en/docs/experience-platform/access-control/abac/permissions-ui/browse) och du kan använda [Admin Console](https://experienceleague.adobe.com/en/docs/experience-platform/access-control/ui/browse) för att tilldela behörigheter för Customer Journey Analytics.
   * Behörigheterna är detaljerade och din sandlådeadministratör kan konfigurera vilka av dina användare som kan ställa olika frågekategorier (produktkunskapsbaserade frågor med AI Assistant eller frågor om driftsinsikter).

* AI Assistant är en HIPAA-klar funktion när den används i kombination med Adobe Experience Platform Healthcare Shield.
* Du kan visa en logg över dina tidigare interaktioner med AI Assistant med en 30-dagars bevarandeprincip.
* AI-assistenten omges av sandlådespecifika data och offentlig Adobe-dokumentation när användaren besvarar uppmaningar. Data delas inte över sandlådor.
* Frågar som du anger för AI Assistant delas inte med andra kunder.

&amp;ast; *Det innebär att om nya etiketter läggs till i fält och objekt eller om nya profiler skapas, tar det upp till 24 timmar för AI Assistant att efterleva dem. Under dessa 24 timmar har användare med nyligen begränsad åtkomst fortfarande åtkomst till dessa fält och objekt.*
