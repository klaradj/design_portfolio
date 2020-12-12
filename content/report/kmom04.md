---
Title: Kmom04
Description: Report for Kmom04
Template: kmom
---

Kmom04
==================
Arbetet med skrivuppgiften gjorde att jag fick nya insikter om organisationerna och deras webbsidor. När jag började med skrivuppgiften tyckte jag att Operation Smiles hemsida var rörig och oprofessionell och tyckte att det var konstigt att de inte hade en "bättre" hemsida. Men när jag hade analyserat färdigt och tänkt igenom det ordentligt så tror jag ändå att de kanske lyckas kommunicera det som de vill kommunicera med sin hemsida, den ger ju ett intryck av att det är mycket som händer och full fart.

Jag valde att fortsatta med den mörkgröna färgen från gräsmattan i bilden i headern. Som accentfärg valde jag att använda komplement-färgen till den. Jag använde sass funktionen complement().

När jag skulle göra mitt mörka tema så gjorde jag en kopia av min vanliga style-fil. men jag passade också på att flytta ut lite mer kod från den för att slippa ha så mycket duplicerad kod. style.scss och style-dark.scss importerar olika variabler, men fungerar annars på samma sätt. Den mesta koden kan man ändra i båda versioner av temat samtidigt eftersom style och style-dark importerar från samma filer (förutom variablerna då). Dock finns lite kod kvar i style eftersom jag inte tyckte att den tillhörde någon uppenbar annan fil och jag vill att det ska vara lätt att hitta bland mina sass-filer.

Min TIL för detta kursmoment är att det finns många smidiga sass-funktioner som man kan utnyttja när man håller på med färger. Till exenmpel complement() och filter för bilder. Jag använde filtret grayscale() för att göra så att min header-bild skulle passa in bättre i det mörka temat.
