# Källkodshantering

Git är utpekad standard för versionshantering av kod.

### Branchhantering

![](../../.gitbook/assets/image%20%2811%29.png)

{% embed url="https://trunkbaseddevelopment.com/" %}



| Team | Källkodshantering | CI/CD |
| :--- | :--- | :--- |
| Tandvårdsteamet | GitHub \(privat repo\) | Jenkins \(egen installation\) |
| VEP | Azure DevOps \(build-ersattning.vgregion.se\) | Azure Pipelines |
| Integration | GitLab | Jenkins |
| MTMIS | GitLab | Ej bestämt |
| VGPV | TFS | Jenkins \(vgdb0832.vgregion.se\) |
| Privera | TFS | ? |
| E-Arkiv/Pandora | TFS | X |
| TEARS | TFS | Jenkins \(vgas1973.vgregion.se\) |
| Köpt Vård/IVard | TFS | ? |

### Centraliserade instanser

TFS - vgrtfs.vgregion.se - Bör fasas ut till fördel för GitLab. Frågetecken för hur svårt det är att migrera byggen.

Jenkins - jenkins.vgregion.se - Är en över ett år gammal installation med en hel del säkerhetsproblematik som inte uppdaterats. ICC har idag gått ifrån Jenkins och kör enbart GitLab Runners, ICC är också de som tidigare har förvaltat produkten. Idag verkar det vara "flytande".

GitLab - git.vgregion.se - Har pratat med Cristian Engström \(ICC\) som arbetat en del med det och Luke Simmons som installerat runners åt ICC. Ivan K som varit drivande på att ta in GitLab och gjort initialt arbete med det har slutat. Produktägare eller förvaltare för GitLab är Valon Hysenaj.

### Frågor

* Hur beställer man ett projekt i Jenkins \(jenkins.vgregion.se\)?
* GitLab kan man skapa upp själv med AD-inloggning. Hur sätter man upp byggagenter och pipelines
* Är build-ersattning.vgregion.se gemensam för flera team?

