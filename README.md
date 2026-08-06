# Min kodplugg till Radioddity GD-73

## Copyright

© 2026 by SM0RGM Stefan Helander

Filerna är tillgängliga under [GPLv3](https://github.com/sm0rgm/gd-73/blob/master/LICENSE).

## Syfte

Det här är min kodplugg till min Radioddity GD-73. Den är testad med både GD-73A och GD-73E. Jag använder CPS version 1.05 och firmware 1.06. Huvudsyftet med publiceringen av filerna här på GitHub är att förenkla för mig själv när det gäller uppdateringar. Jag har inget emot att dela med mig av filerna så att andra kan nyttja dem under förutsättning att de som återanvänder mina filer följer licensvillkoren i [GPLv3](https://github.com/sm0rgm/gd-73/blob/master/LICENSE).

Om du vill bidra med något så är du naturligtvis välkommen att göra så antingen genom att skapa en Pull Request (kräver en del kunskap om hur GitHub funkar) eller genom att skapa ett [issue](https://github.com/sm0rgm/gd-73/issues).

## Vad ingår i filerna?

Zoner för PMR, DPMR (PMR med DMR), SRBR, DPMR med kryptering/scrambling samt en zon för hotspot (amatörradio).

## Digitala kontaktlistan

Den digitala kontaktlistan innehåller call från SM för att få ner storleken på den så att den med säkerhet får plats. Vill du ha en kontaktlista med fler länder kan du skapa ett konto på [radioid.net](https://radioid.net) och generera kontaklistor med exakt de länder du vill ha med.

### Vilka filer ska du hämta?

Jag rekommenderar att du hämtar filerna som jag har packat ihop i en [release](https://github.com/sm0rgm/gd-73/releases) istället för att hämta mina arbetsfiler!

### När filerna är hämtade... 

Om du snabbt och enkelt vill starta en ny kodplugg eller koda upp en ny radio så finns det en färdig fil med alla inställningar gjorda som heter N0CALL.rdt.  
Starta CPS-programmet och välj Öppna fil och välj N0CALL.rdt. Gå till fliken General Settings och ändra Your Name från "N0CALL Name" till ditt call och namn. 
För Radio ID ändrar du från 1234567 till ditt eget DMR ID. Radion hanterar bara ett id så detta kommer att användas för både DPMR, Crypto och HS-zonernai. 
Vill du använda de krypterade kanalerna är det lämpligt att du byter till egna nycklar under Encrypt i CPS.
Sedan är det bara att skjuta i kodpluggen i din radio.

### FAQ 

* GD-73 kan bara hantera förprogrammerade talgrupper via Contacts. Man kan inte fritt knappa in talgrupp på radion. Vill du ha tillgång till andra talgrupper än dem som redan finns måste du lägga till dem under Digital Contact.
* Zonen HS (för hotspots) har snabbvalskanaler med de vanliga svenska talgrupperna. Dessa tar enbart emot trafik i den talgrupp som kanalen motsvarar. Vill du ha radion öppen för mottagning på alla talgrupper ställer du den på kanalen "HS Select TG/ID". Trycker du på PTT inom hangtime (15 sekunder) från senaste mottagning kommer du att sända i den talgrupp du hörde trafiken.
* Via menyvalet Contact så kan du på kanalen "HS Select TD/ID" välja valfri talgrupp eller kontakt ur listan att sända i.

73's de SM0RGM Stefan

2026-08-06
