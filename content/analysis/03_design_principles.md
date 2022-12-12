---
Title: Tillgänglighet och prestanda
Description: kmom06
Template: report
---

Tillgänglighet och prestanda
=======================

Denna rapport analyserar tre olika webbplatser inom gruppen personsidor (portfolio/me-sida/blogg eller liknande).

För dessa sidor försöker jag identifiera om de använder sig utav några designprinciper jag känner till, samt om jag finner något annat tongivande för designen i deras webbplats.

Jag gör även samma analys på min egen portfolio-sida och jämför vad det finns för skillnader mellan min egen sida och de undersökta.

Urval
-----------------------

Jag har valt att studera tre datorlegenders personliga webbsidor. Anledningen till att jag valde just dessa tre, är att de har uppfunnit ett  märkspråk och några programspråk som har behandlats under hösten i de två kurspaketen jag läser på BTH.

Dessutom borde ju tre riktigt stora datorlegender veta hur man kodar en webbsida...

De tre personsidorna är:

* [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/) -- uppfann World Wide Web (och HTML) anno 1989.

* [Guido van Rossum](https://gvanrossum.github.io/) -- uppfann Python anno 1991.

* [Brendan Eich](https://brendaneich.com/) -- uppfann JavaScript anno 1995.

Metod
-----------------------

Det enda "verktyget" jag har använt mig av är senaste versionen av **Firefox** för **Windows 10**. Förutom att "titta på och uppleva" personsidorna, "tittar" jag också på HTML-koden med hjälp av "View Page Source".

De enda designprinciper jag tror mig känna till hjälpligt är de 20 som beskrivs på [“Design Elements & Principles”](https://www.canva.com/learn/design-elements-principles/). Det är därför dessa 20 jag studerar.

Resultat
-----------------------

### [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/)

Sidan är skriven mer formellt än en typisk Wikipedia-artikel: "Sir Tim Berners-Lee invented" istället för "I invented".

Förutom en kort biografi, innehåller sidan också kontaktuppgifter. Troligen kan Sir Tim dra in bra med pengar genom att extraknäcka som keynote-speaker.

Webbsidans design är urtypen för en IT-legends webbsida. Enkel design, på gränsen till minimalistisk. Inga filmer eller musik som startar automatiskt. Inga färger, förutom standardfärger för länkar.

Det enda som inte är enkel, reserverad design är headern som består av tre kolumner. Headern är närmast bombastisk jämfört med resten av sidan. Headern är en **table** med "underliga" **th:s**. Detta gör att texten "Contents" i tabellen ser ut att sväva i luften.

CSS används väldigt sparsmakat.

Typsnittet är **serif** både för rubriker och brödtext.

**Linjer** används bara för att skilja fotnoten från huvudartikeln.

En stor del av sidan består av listor med länkar.

Det finns några "stora vita fält" med ojämn rytm mellan "textfälten".

Det finns förvånansvärt många döda länkar, t.ex: länkarna till "data", "(Longer biography)" och "disclaimer".

Sidan är inte responsiv.

På en mobil, blir det "pannkaka" av tabellen i headern. Annars ser det bra ut på mobilen.

På en bred skärm fyller brödtexten hela bredden. Även tabellen i headern fyller hela bredden.

Jag hittar inte några undersidor...

Jag skulle vilja påstå att den helt dominerande designprincipen är:

**Styla inte sidan!**
### [Guido van Rossum](https://gvanrossum.github.io/)

Sidan är skriven i en informell stil, inte alls som en Wikipedia-artikel. ("I am the author of the Python programming language.")

Det finns även plats för lite humor, t.ex.: "Who I Am"-länken.

Även denna webbsidas design är urtypen för en IT-legends webbsida. Enkel design, på gränsen till minimalistisk. Inga filmer eller musik som startar automatiskt. Inga färger, förutom standardfärger för länkar.

Liksom för Tim Berners-Lee:s sida består headern av tre kolumner. Men headern består av en vanlig **h1** med två inbäddade bilder.

I övrigt gäller samma kommentarer som för Tim Berners-Lee:s sida. Förutom:

Fler bilder: Tre istället för en.

Betydligt mindre "stora vita fält".

Headern med tre kolumner är responsiv. Men inte speciellt vackert responsiv.

Ingen CSS-fil används. Istället används &lt;BODY BGCOLOR="#FFFFFF" TEXT="#000000"&gt;.

Väldigt lättläst HTML, t.ex.: används ingen sluttagg för &lt;P&gt;.

Samma designprinciper har används för framsidan och undersidorna.

Även för denna sida är den helt dominerande designprincipen:

**Styla inte sidan!**

### [Brendan Eich](https://brendaneich.com/)

Nu gissar jag bara... Men jag tror att syftet med den personliga sidan var att få omvärlden att förstå att det var Brendan Eich som hade uppfunnit JavaScript. Det var inte alls självklart för 15 år sedan. Samt att markandsföra Mozilla. Sidan slutade uppdateras i slutet av 2017 -- "Mission accomplished".

Sidan är "Proudly powered by WordPress", vilket gör att Brendan Eich troligen inte har kodat HTML för att skapa den.

Troligen är CSS från en färdig CSS-mall.

Sidan synes inte innehålla någon JavaScript...

Helhetsintrycket är att sidan är en typisk bloggsida från tiden runt 2010, vilket gör att sidan känns betydligt modärnare än de två tidigare beskrivna sidorna.

Typsnittet är **sans-serif** både för rubriker och brödtext.

Linjer används betydligt mer än för de två tidigare beskrivna sidorna. Det saknas dock horisontella linjer mellan blogginläggen!

**Färg** används, t.ex. har headern en diskret bakgrundsfärg.

Blå färg används för rubriker!

Sidan är responsiv!

Den ser bra ut på både mobil och skrivbord.

På en bred skärm fyller brödtexten **inte** hela bredden, utan har en maxbredd.

För den här sidan är den troliga designprincipen:

**"Diskret är inte helt fel..."**

Analys
-----------------------

Det är Brendan Eich:s sida som står som inspiration för 96% av nedanstående förändringsarbete. (Detta kan bero på att jag inte är någon datorlegend...)

### Den här portfolio-sidan jämfört med de tre undersökta sidorna

Syftet med den här portfolio-sidan är att fungera som mall för framtida projekt. Efter att ha studerat de tre sidorna, ser jag direkt några lågt hängande frukter för att förbättra sidan:

1. Begränsa bredden på brödtexten vid breda skrivbord.
2. Använda linjer mer, men använda rundade hörn för att göra sidan mindre "fyrkantig".
3. Färga rubrikerna blå
4. Låta rubrikerna komma närmare tillhörande brödtext, för att åstadkomma bättre rytm.
5. Ha kvar sans-serif för rubriker, men ändra brödtexten till serif. Jag skjuter dock detta projekt på framtiden, eftersom jag behöver göra en utförlig usability-testning innan jag eventuellt byter.
6. Vänsterjustera brödtexten. För närvarande är den "text-align: justify", vilket jag inte har lagt märke till förut. Men nu när jag ser det, ser det inte alls bra ut.
7. Öka några utvalda vita mellanrums area för att försköna sidan.
8. Göra de olika undersidorna mer enhetliga.

<br>
Obs! Jag har nu implementerat punkterna ovan, förutom punkt 5.

Övrigt
-----------------------

Jag, Lars Johansson, jobbade enskilt.
