---
description: >-
  Här beskrivs information kring Docker Desktop
---

# Docker Desktop

### Få en paketerad docker desktop som inte kräver KA-konto: 

Docker Desktop beställer man i Plexus, under IT > Förfrågan > Övriga supporttjänster [Övriga supporttjänster - VGR serviceportal](https://plexus-prod.vgregion.se/sp?id=sc_cat_item&sys_id=3337d9e0db569b84934af3d31d9619e9). 

Här anger man:
* Kort beskrivning, Beskrivning, Datornamn, Programvara (”Docker Desktop”), Beställd till (dig själv) och Telefonnummer (till dig själv)

Efter några timmar kan man sedan märka av att en installation påbörjas i bakgrunden och du kan jobba på som vanligt. När installationen är klar dyker en ruta upp som uppmanar till två åtgärder:
1. Lägg till din egna användare (vgrid) till Windows-gruppen: docker-users. För detta behöver man KA, lokal admin eller hjälp från supporten då det kräver lite högre rättigheter än vad man normalt arbetar med
2. Starta om datorn
(3) Det kan stå något om att man skall kontrollera så att Hyper-V är påslaget men det har det varit automatiskt i alla installationer hittills så detta kan vi se som en eventuell felsökningsåtgärd om något inte fungerar som det skall

När dator har starts om så hittar man Docker Desktop i Start-menyn och då är det bara att använda programmet

En test för att se så allt fungerar kan vara att i Docker Desktop söka fram Apache httpd, starta den med port satt till 8080 (både in som ut) och öppna en webbläsare med adressen: http://localhost:8080 - står det "It works!" så fungerar det

### För att få licens på Docker Desktop
Be din chef maila  till vgr.licenser@vgregion.se   
