---
description: >-
  På Västra Götalandsregionen bedrivs många former av utveckling där
  användargränssnitt behövs, nedan finns förslag och riktlinjer på hur det bäst
  görs för webbutveckling.
---

# Webbutveckling

Webbutveckling en viktig del i att skapa tillgängliga digitala tjänster till våra invånare. 
Webbutveckling omfattar flera aspekter, inklusive frontend- och backend-utveckling, responsiv design, tillgänglighet och webbdesign. För att bedriva effektiv webbutveckling i en modern organisation bör man förstå användarbehov, implementera säkerhetsåtgärder och hålla sig uppdaterad om de senaste trenderna och teknikerna.
Genom att följa nedan riktlinjer kan du skapa webbplatser som är både tekniskt robusta och användarvänliga. 

Om inte andra behov föreligger så rekommenderas webbutveckling att utvecklas som en Single Page Application (SPA), det innebär att sidan laddas om dynamiskt utan att hela sidomladdningar görs.

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption><p>Översikt Single Page Application</p></figcaption></figure>

#### Ramverk

För backendutveckling används primärt .NET mjukvaruramverk, alternativt [Java](java/java.md)


För utveckling i frontend använder vi [Angular](https://angular.io/) alternativt [React](https://react.dev/). Valet mellan dessa görs bäst baserat på den kompetens man besitter i teamet och vilken övrig utvecklingsteknik man har i sin portfölj.

På Västra Götalandsregionens [GitHub](https://github.com/Vastra-Gotalandsregionen/komponentkartan) finns ett utvecklat komponentbibliotek att använda i det fall man använder sig av Angular.
<br>

#### Tillgänglighet
Offentliga aktörers webbplatser och mobila applikationer ska vara tillgängliga. Kravet finns i lagen om tillgänglighet till digital offentlig service. På [Webbriktlinjer | Digg](https://www.digg.se/webbriktlinjer) hittar du vad du måste göra för att applikationen ska leva upp till lagen.
- Följ WCAG 2.1-riktlinjerna för att säkerställa att din webbplats är tillgänglig för alla användare, oavsett funktionsnedsättning.
- Använd meningsfulla alt-texter för bilder.
- Se till att webbplatsen är responsiv och fungerar bra på olika skärmstorlekar.
- Undvik att använda färger eler bilder som enda sätt att förmedla information.
<br>

#### Tekniska riktlinjer


- **Säkerhet**
  - Använd alltid HTTPS för att skydda känslig data.
  - Håll dina beroende och bibliotek uppdaterade.
  - Skydda mot vanliga sårbarheter som SQL-injektion och cross-site scripting (XSS).
  - Implementera inte lösenord, personuppgifter eller arkitekturella detaljer i kod  
  <br>
  
- **Kodkvalitet**
  - Följ en konsekvent kodningsstandard. Nedan hittar du exempel på olika kodningsstandarder
    - C# - [Microsoft Coding Conventions](https://learn.microsoft.com/sv-se/dotnet/csharp/fundamentals/coding-style/coding-conventions)
    - Java [Google's coding standards](https://google.github.io/styleguide/javaguide.html)
    - Angular [Angular coding style guide
](https://angular.dev/style-guide)
    - React [https://handsonreact.com/docs/code-organization-conventions](https://handsonreact.com/docs/code-organization-conventions)
  - Utför regelbundna kodgranskningar.
  - Använd med fördel VGR's instans av [SonarQube CE](https://sonarqube.vgregion.se/)
  - Använd Code analyzers för att upprätthålla kodstandarder. Dessa finns inbyggda i Visual Studio och andra IDE:er för att identifiera potentiella problem.
<br>

- **Prestanda**
  - Optimera bilder för webben.
  - Minifiera HTML, CSS och JavaScript.
  - Använd caching för att minska laddningstider.
  - Undvik onödiga omdirigeringar.
<br>

- **Responsiv design**
  - Se till att din webbplats anpassar sig till olika skärmstorlekar och enheter.
  - Använd media queries för att styra layouten.
  - Testa din webbplats på olika enheter och webbläsare.
<br>

#### Riktlinjer kring design och grafiskt gränssnitt
Västra Götalandsregionens designsystem för grafiska gränssnitt är till för dig som jobbar med design, utveckling eller annan form av digital produktion på VGR. Dokumentationen skapas och förvaltas av enheten Design & Användarupplevelse.
Mer information hittar du här [VGR Designsystem](https://design.vgregion.se/) 

#### Kontakta oss

För mer information eller frågor om webbutveckling kontakta oss på enheten för systemutveckling på [systemutveckling.ksd@vgregion.se](systemutveckling.ksd@vgregion.se)

#### Länkar

[Webbriktlinjer | Digg](https://www.digg.se/webbriktlinjer)

[Webbhandbok riktlinjer - VGR](https://www.vgregion.se/webbhandboken/riktlinjer/)

[VGR Komponentkarta](https://github.com/Vastra-Gotalandsregionen/komponentkartan) - [Demo](https://vastra-gotalandsregionen.github.io/komponentkartan-demo/start)

[VGR Designsystem](https://design.vgregion.se/) 
