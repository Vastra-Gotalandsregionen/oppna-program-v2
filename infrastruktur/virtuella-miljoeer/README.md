# Virtuella miljöer

Att tänka på:

* ServerAccess-konto behövs för att komma åt servrar via Remote Desktop. [SA-konto beställs](https://plexus-prod.vgregion.se/sp?id=sc\_cat\_item\&sys\_id=3337d9e0db569b84934af3d31d9619e9\&sysparm\_category=0cd4dd45db27db08ed36384c7c9619c5) för respektive användare mot en server, från en specifik dator.
* Om servern skall vara åtkomlig från internet behöver en [brandväggsöppning ](https://plexus-prod.vgregion.se/sp?id=sc\_cat\_item\&sys\_id=a0309ad81bbd1450c63c31d8cd4bcba9)beställas alternativt en [applikationspublicering genom ADC](https://plexus-prod.vgregion.se/sp?id=sc\_cat\_item\&sys\_id=4ddb4776478195549e2a21ebd36d4302).
* Om exempelvis en webbserver skall kommunicera med en databas behöver ett TjänsteKonto beställas. Ett alternativ är att [beställa direktaccess till databasen](https://bariumapp.vgregion.se/Instances/Create?externalInteractionID=9dc5ae33-cd4a-44b0-8e35-072c4567d36a\&hideGui=False\&hideToolbar=False), den är då åtkomlig genom ett vanligt SQL-konto.
