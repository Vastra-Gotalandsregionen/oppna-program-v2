---
description: >-
 En PWA är en webbplats som ser ut och känns som en mobil app, men som körs direkt i webbläsaren. Den kombinerar det bästa av både webb och app, och erbjuder funktioner som offline-åtkomst, push-notiser och snabb laddningstid. 
---

# PWA (Progressive webapp)

#### Tekniska riktlinjer för PWA-utveckling:

- **Mnifestfil**
  - Skapa en manifestfil (manifest.json) som beskriver din PWA.
  - Inkludera information som appens namn, beskrivning, ikoner och start-URL.
  - Konfigurera display-läget (fullscreen, standalone, etc.) för att anpassa användarupplevelsen.
<br>

- **Service Worker**
  - Implementera en service worker för att möjliggöra offline-funktionalitet och push-notiser.
  - Cacheera viktiga resurser för att förbättra laddningstiderna.
  - Hantera nätverksförfrågningar och uppdateringar av cache.
<br>

- **Responsiv design**
  - Se till att din PWA fungerar smidigt på alla enheter och skärmstorlekar.
  - Använd responsiva layouttekniker (CSS Media Queries, flexbox, grid) för att anpassa innehållet.
<br>

- **Prestanda**
  - Optimera bilder och andra resurser för att minska laddningstiderna.
  - Minimera HTTP-förfrågningar.
  - Använd lazy loading för att bara ladda in resurser när de behövs.
<br>

- **Användarupplevelse**
  - Fokusera på en intuitiv och användarvänlig design.
  - Gör det enkelt för användare att navigera och hitta information.
  - Implementera progressiva förbättringar, så att användare som inte har stöd för PWA-funktioner ändå kan använda din webbplats.
<br>

- **Tillgänglighet**
  - Följ WCAG-riktlinjerna för att göra din PWA tillgänglig för alla användare, inklusive personer med funktionsnedsättningar.
<br>

- **Säkerhet**
  - Använd HTTPS för att skydda användardata.
  - Skydda mot vanliga webbsäkerhetshot som XSS och CSRF.
<br>

- **Uppdateringar**
  - Implementera en strategi för att uppdatera din PWA utan att störa användarna.
  - Använd service worker för att hantera uppdateringar och cache.
<br>

- **Framework**
  - **Lighthouse**  Lighthouse för att utvärdera prestanda, tillgänglighet, progressiva webbfunktioner och SEO för din PWA.
<br>

- **Exempel på funktioner som kan läggas till i en PWA**
<br>

- **Push-notiser:** Skicka notiser till användare även när de inte är aktiva på webbplatsen.
- **Offline-åtkomst:** Låt användare komma åt delar av webbplatsen även utan internetanslutning.
- **Hemskärmsinstallation:** Gör det enkelt för användare att installera din PWA på sin hemskärm.
- **Bakgrundsuppdateringar:** Uppdatera innehåll i bakgrunden för att ge användarna den senaste informationen.

