# git-uppgift

## Frågor:

**Fråga 1: Versionshantering vs vanliga filer:**
Vanliga sparknappen skriver bara över gammla filen och minns inget. Versionshantering sparar alla "sparningar" (commits) som frysta minnen så du kan se varje version av ett projekt ifall du råkar radera nåt eller ha sönder något därav namnet "versionshantering". Att jag kan gå tillbacka och se alla "TODO" betyder att git funkar som det ska och sparar alla versioner även om min lokala fil bara skriver över innehållet helt.

**Fråga 2: Arbetsytan, Staging och Commits:**
"git status" kollar om du är up to date med branchen tex. "git add" väljer vilka filer som ska läggas till som tex git add index.html stagar bara index filen men git add . stagar hela mappen man är i. "git commit" sparar ner ändringarna i historiken som ett fryst minne. Arbetsytan är mitt kladdpapper på skrivbordet, staging är ett kuvert där jag stoppar ner papperet, och commit är när jag förseglar kuvertet och lägger det i arkivet. Får jag "no changes added to commit" försöker jag arkivera ett tomt kuvert eftersom jag glömt lägga i filen med "git add".

**Fråga 3: Lådan hemma vs Montern på GitHub:**
"git push" flyttar dom från mitt lokala minne till ett arkiv så dom är sparade på riktigt (dator -> github). Min lokala mapp är min privata "låda" där jag bygger historiken, medan GitHub är en publik "glasmonter". Får jag "Everything up-to-date" trots att jag ändrat i koden beror det på att push bara skickar upp just färdiga commits. Har jag inte kört add och commit först så ser GitHub inga nya ändringar.