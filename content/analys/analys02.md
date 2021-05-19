Titel på rapporten
=======================

I detta kursmoment jag ska undersöka ett antal websidors laddningstid. Jag ska även kolla om man kan förbättra något på websidan.

Urval
-----------------------

Jag har valt websidan <a href="https://www.blocket.se">Blocket</a>, <a href="https://www.nike.com/se/en/">Nike</a> och <a href="https://www.asos.com">Asos</a>. Jag ska undersöka dessa tre websidors laddningstid beroende på  bilder och artiklar.


Metod
-----------------------

Jag använder Google Pagespeed Insights och Developers Tools Network för att kunna analysera laddningstid, resuser och storlek. Jag även använder kursmaterial och dbwebb artiklar och föreläsningar. 

Resultat
-----------------------

<a href="https://docs.google.com/spreadsheets/d/1TvBQZ8DZ91DeBqlQVKwyZeDoW939pDzWHU5SM33Sg94/edit?usp=sharing">Excel Sheet</a>
<img src="../assets/img/blocket.jpg" alt="blocket">


### Blocket

Blockets websidans förbättringsåtgärder för att spara laddningstid är att ta bort JavaScript som inte används och ta bort resurser som blockerar renderingen.

<img src="../assets/img/nike.jpg" alt="nike">


### Nike

Nikes förbttringsåtgärder för att spara laddningstid är att ta bort Javascript som inte används, minska initial responstid, ta bort resurser som blockerar renderingen och minifiera JavaScript.

<img src="../assets/img/asos.jpg" alt="asos">


### Asos

Asos webbsidans förbättringsåtgärder för att spara laddningstid är att ta bort JavaScript som inte används, undvika erving legacy JavaScript till moderna browser, ta bort duplicate modular i Javascripts bundles och ta bort CSS som inte används.

Analys
-----------------------

Enligt resultaten från google pagespeed så är Nike.com/en/sv den som laddas snabbast men enligt developers tools så är det Blocket.se som är snabbast. Det kan vara på grund av dess resurs, blocket har ganska mindre resurser jämför med Nike och Asos. Nike och Asos har nästa lika mycket resurser och laddningstid men Asos har mindre storlek på sin websidan än Nike enligt developerstool och tvärtom enligt Google PageSpeed.

Nike.se har jätte mycket bilder och annonser som blädras hela tiden och kanske det är darför den är stort i storleken än andra websidor. Asos har bara en första sidan och ett stort bild websidan är inte så jätte långt för att man skalll välja met olika knappar för att ska navigeras vidare. Blocket har också en del bilder för olika annonser men det är inte lika mycket som Nike. Jag tycker blocket är mycket enkelt webbsidan. Enligt PageSpeed så blocket borde förbättras med radering av oanvänds jaascript, skicka bilder i modern bildformat för att skicka mindre bytes via nätverk. Dessto snabb en websidans laddas dessto mer den har chans att användare stannar på den.

Jag tycker Nike är vinnare eftersom den har det minsta betyg enligt pagespeed visst det har mindre laddningstid på blocket enligt developerstools men blocket har inte lika mycket resurser som nike. Nike är vinnare respektiv sina resurser. På andra plats kommer Blocket då det har mindre betyg i pagespeed och tredje plats är Asos, samtidigt är det svårt att bedömma det kan vara Asos på andra plats för det har mer resurser än blocket men det är mindre i storlek än blocket och även mindre tid än blocket på mobil enhet enligt pagespeed.

Referenser
-----------------------
<a href="https://moz.com/learn/seo/page-speed">Moz om Page Speed</a>


Övrigt
-----------------------

Denna raport är skrivit av Nabil Zafari(naza20).