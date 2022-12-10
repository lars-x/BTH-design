---
Title: Bilder
Description: kmom05
Template: report
---

Bilder: laddningstid och användbarhet
=======================

Den här rapporten utvärderar tre sidor på var och en av tre webbplatser med avseende på hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag ville främst analysera laddningstiden för bilders olika storlekar. Jag valde därför att jämföra "Galleriet" (A1 nedan) på den här webbplatsen (kallas A nedan) med en extrasida "Galleri XL" (A2). Skillnaden är att det är betydligt större bilder som laddas på "Galleri XL"-sidan.

Dessutom valde jag att jämföra med "Galleriet" (B1 nedan) för mitt projekt för den tidigare kursen Webbteknologier (B).

Som tredje webbplats valde jag mina github-pages (C). Jag konvertade projektets galleri (B1) till en statisk sida (C1).

På github-pages valde jag också att mäta laddningstiden för en stor tabell (C2) och en mycket stor tabell (C3).

Slutligen fyllde jag ut med några små sidor som "baseline" (A3), (B2) och (B3).
#### Sammanställning av de nio sidorna på de tre webbplatserna A, B & C:

<div class="kmom05">
    <table>
        <tr>
            <th>Länk</th>
            <th>Desktop</th>
            <th>Mobil</th>
        </tr>
        <tr>
            <td><a href="http://www.student.bth.se/~lajo15/dbwebb-kurser/design/me/portfolio/gallery">A1</a></td>
            <td><img src="%base_url%/image/ABC123DM/A1D.jpg" alt="A1D"></td>
            <td><img src="%base_url%/image/ABC123DM/A1M.jpg" alt="A1M"></td>
        </tr>
        <tr>
            <td><a href="http://www.student.bth.se/~lajo15/dbwebb-kurser/design/me/portfolio/galleryxl">A2</a></td>
            <td><img src="%base_url%/image/ABC123DM/A2D.jpg" alt="A2D"></td>
            <td><img src="%base_url%/image/ABC123DM/A2M.jpg" alt="A2M"></td>
        </tr>
        <tr>
            <td><a href="http://www.student.bth.se/~lajo15/dbwebb-kurser/design/me/portfolio/about">A3</a></td>
            <td><img src="%base_url%/image/ABC123DM/A3D.jpg" alt="A3D"></td>
            <td><img src="%base_url%/image/ABC123DM/A3M.jpg" alt="A3M"></td>
        </tr>
        <tr>
            <td><a href="http://www.student.bth.se/~lajo15/dbwebb-kurser/webtec/me/proj/public/album.php">B1</a></td>
            <td><img src="%base_url%/image/ABC123DM/B1D.jpg" alt="B1D"></td>
            <td><img src="%base_url%/image/ABC123DM/B1M.jpg" alt="B1M"></td>
        </tr>
        <tr>
            <td><a href="http://www.student.bth.se/~lajo15/dbwebb-kurser/webtec/me/proj/public/login.php">B2</a></td>
            <td><img src="%base_url%/image/ABC123DM/B2D.jpg" alt="B2D"></td>
            <td><img src="%base_url%/image/ABC123DM/B2M.jpg" alt="B2M"></td>
        </tr>
        <tr>
            <td><a href="http://www.student.bth.se/~lajo15/dbwebb-kurser/webtec/me/proj/public/doc.php">B3</a></td>
            <td><img src="%base_url%/image/ABC123DM/B3D.jpg" alt="B3D"></td>
            <td><img src="%base_url%/image/ABC123DM/B3M.jpg" alt="B3M"></td>
        </tr>
        <tr>
            <td><a href="https://lars-x.github.io/design-for-speed/">C1</a></td>
            <td><img src="%base_url%/image/ABC123DM/C1D.jpg" alt="C1D"></td>
            <td><img src="%base_url%/image/ABC123DM/C1M.jpg" alt="C1M"></td>
        </tr>
        <tr>
            <td><a href="https://lars-x.github.io/booklists/it_1_500.html">C2</a></td>
            <td><img src="%base_url%/image/ABC123DM/C2D.jpg" alt="C2D"></td>
            <td><img src="%base_url%/image/ABC123DM/C2M.jpg" alt="C2M"></td>
        </tr>
        <tr>
            <td><a href="https://lars-x.github.io/booklists/fiction_1_500.html">C3</a></td>
            <td><img src="%base_url%/image/ABC123DM/C3D.jpg" alt="C3D"></td>
            <td><img src="%base_url%/image/ABC123DM/C3M.jpg" alt="C3M"></td>
        </tr>

    </table>
</div>

<br>
Metod
-----------------------

Jag har använt mig av två verktyg för att samla in mätvärdena:

1. **Google Pagespeed**, har mätt på både Mobil och Desktop.
2. Fliken **Networks** under **Developer Tools** i **Firefox** i  **Windows 10** har mätt laddningstid, antal laddade resurser (bilder etc) och sidans totala storlek. Mätningarna gjordes **enbart för Desktop**. Medelvärdet beräknades för tre mätningar.

<br>
För att samla upp och sammanställa mätdata har jag använt mig av **Excel**, se nedan.

Resultat
-----------------------
#### Sammanställning av mätvärden för de nio sidorna på de tre webbplatserna A, B & C:

<div>
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRRQr6MSpSUcuP7HMzfoZBA2Jml_yAfWCZ9q-Grs14b4krHtyw62x7o8h5Si9HsGA/pubhtml?widget=true&amp;headers=false" width="100%" height="450"></iframe>
</div>

Analys
-----------------------

Vad som verkligen sticker ut är det väldigt dåliga betyget -- bara 17 av 100 -- för A1 (Gallerisidan). Min analys är att beror på Youtube-filmen längst ner på sidan. Om man tycker att 10 sekunder är lång tid, är lösningen att flytta länken till filmen till en egen sida. Kanske med varningstexten "Laddas långsamt"?

Den överlägsne vinnaren är C (github-pages), speciellt för mobilen, där den får max poäng både för gallerisidan och den stora tabellen (200 rader). Den mycket stora tabellen (2411 rader) påverkar (föga förvånande) laddningstiden och därmed betyget. Jag anser dock att 1.22 sekunder för 2411 rader är snabbt. Det är exempelvis snabbare än en kallstart av motsvarande tabell i Excel.

**Men man kan inte säga att någon av webbplatserna är sämre än de andra**, däremot några av sidorna:

* A1 är grymt långsam pga den inbäddade Youtube-filmen.
* A2 är långam pga de åtta relativt **stora bilderna**. Det var ju detta vi egentligen ville mäta och eventuellt bekräfta.
* A3:s låga betyg för mobilen är förvånande. Betydligt sämre resultat än för B. B körs också på BTH:s server med PHP. Kan det bero på att Pico är långsamt? Eller dåligt intrimmat?
* B1 har små bilder och laddas godkänt snabbt. Även för mobilen.
* B2 är snabbare än B3. Det var förväntat, eftersom B3 innehåller betydligt mer text.
* B3 är långsammare än B2. Men det skiljer inte speciellt mycket.
* C1:s galleri med 8 bilder laddas så snabbt i mobilen att betyget blir 100 av 100.
* C2:s resultat för mobilen (100 av 100) indikerar att man kan ha ganska stora tabeller, utan att det sänker betyget.
* C3:s resultat för mobilen tycker jag är det mest imponerande. 2411 rader fulla med text.

<br>
Sammanfattningsvis kan vi konstatera att det är fördelaktigt att ha så små (och få) bilder som möjligt med avseende användarupplevelse etc.

Mycket text på en sida påverkar dock inte speciellt mycket.

Jag kan tänka mig att 2 sekunder kan vara en lämplig maxgräns för laddningstiden utan att datorstressen blir alltför hög.

I så fall är det bara sidan A1 (sidan med den inbäddade Youtube-filmen) som inte klarar gränsen.

Övrigt
-----------------------

Jag, Lars Johansson, jobbade enskilt.
