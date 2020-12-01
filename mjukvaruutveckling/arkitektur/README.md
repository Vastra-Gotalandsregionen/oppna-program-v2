# Arkitektur

### Syfte

1. **Oberoende av ramverk**. Ramverk används som verktyg och får inte utgöra en begränsande faktor på systemet.
2. **Testbart**. Affärsregler kan testas oberoende av gränssnitt, databas, webbserver och övriga externa beroenden.
3. **Oberoende av gränssnitt**. Gränssnittet kan förändras utan att övriga systemet behöver förändras. Ett webbgränssnitt kan bytas ut mot ett konsolgränssnitt utan att affärsregler förändras, till exempel.
4. **Oberoende av databas**. Affärsregler är inte knutna till databasen och skall gå att byta ut.
5. **Oberoende av externa faktorer**. Affärsreglerna vet ingenting om omvärlden utom det som är av nytta för systemet.

### Historik

Alistair Cockburn var en av de 17 personer som skrev det agila manifestet 2001, där han var känd för sina lättviktiga varianter av annars ganska tungrodda processer i en metodik han kallade Crystal, där bland annat "lightweight use cases".

2005 presenterade han första gången Hexagonal Architecture \(även kallat Ports & Adapters\) som en lösning på problem med lagring och coupling. 

Motivationen löd:

> _Allow an application to equally be driven by users, programs, automated test or batch scripts, and to be developed and tested in isolation from its eventual run-time devices and databases._

![](../../.gitbook/assets/image%20%289%29.png)

