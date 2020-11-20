---
Title: Kmom03
Description: Report for Kmom03
Template: kmom
---

Kmom03
==================

Det har gått bra att jobba med CSS-Grid och flexbox. Jag har jobbat en del med de teknikerna tidigare men det kändes enklare den här gången och jag tror att det är för att jag har en större föreståelse för hur CSS fungerar den här gången. Jag har delat upp stylen i olika moduler och för de sidor som har en egen layout, till exempel rapportlandningssidan och kursmoments-sidan så har jag lagt det som är speciellt för de sidorna i egna moduler. Förutom de uppdelningen så har jag delat upp stylen till den generella stylen i olika moduler. Extra skönt är det att ha särskilda moduler för navbaren och responsiviteten för det är ganska mycket kod som jag inte behöver röra när jag håller på med andra delar.

Det svåraste med det här kursmomentet var att göra mobilmenyn. Först försökte jag efterlikna mobilmenyn för hela sidan och återanända kod men sedan gjorde jag en ny från grunden enligt en bra guide på youtube. Jag förstod vad jag gjorde och jag blev nöjd med slutresultatet.

Jag har haft en del problem med npm run lint. Den har inkluderat filer från fontawesome som inte ska komma med. Tidigare raderade jag innehållet från ".stylelintrc" och kopierade in det på nytt från artikeln från kursmoment 2 för att försöka lösa problemet. Då validerade den färre filer från fontawesome men felet kvarstod på filer som innehöll ett "_" i början av filnamnet. Nu har jag raderat filen ".stylelintrc" och lagt till en ny fil med samma namn och samma innehåll, och det fungerar för mig nu. Mycket märkligt, men jag är glad att det fungerar!

Mitt TIL för det här kursmomentet är hur användbart det kan vara med "inspect element" i webläsaren. Jag började med att använda det för att förstå hur CSS grid fungerade men sedan hade jag mycket hjälp av att stänga a CSS regler direkt i webläsaren när jag felsökte min mobilmeny som inte fungerade. Nu när det börjar bli många olika moduler i SASS så är det också användbart att se alla olika regler från alla moduler som är för ett specifikt element samlade.
