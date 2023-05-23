Git används främst för versionhantering av källkod inom programutveckling. Git an
vänds för bland annat: versionhantering, samarbete, grenar samt sammanfogning och fjärrrepository. Git kan också användas för säkerhetskopiering och återställning.

I git finns det tre olika steg som en fil kan befinna sig i. Dessa steg kallas för git-filens livscykeln eller de tre git-stadierna. Dessa tre steg består av: 

Untracked: I denna steget är filen inte spårad av Git. Det innebär att git inte är kopplad/medveten om filens existens eller ändringar som görs i den. När en ny fil skapas i ett Git-repositorium är den initialt ospårad. Ospårad filer visas inte i gits versionshistorik, och Git kommer inte inkludera dem i commitar eller andra operationer om det inte uttryckligen anges. 

Staged: när en fil är i denna steget innebär det att Git är medveten om filens närvaro och de ändringar som gjorts i den. Filen har markerats för att inkludera följande commitar. Genom att stage en fil signalerar du till Git att du vill inkludera dessa ändringar. 

Commited: När en fil är commited har dessa ändringar sparats permanent i Git-repositoriet. Filen ingår nu i Git's versionhistorik, och dess ändringar kan spåras över tiden. Commitade filer kan återställas till tidigare tillstånd eller jämföras med andra versioner av filen. 
Genom att förstå dessa tre steg kan du hantera filernas status i ditt Git-repositorium och kontrollera vilka ändringar som inkluderas i dina commitar. 

Fastnat på steg 14 