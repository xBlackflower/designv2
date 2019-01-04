Tema med fokus på designprinciper
=======================

Min uppgift var att välja ut tre webbplatser och testa hur snabbt de laddas och om de innehåller saker som kan förbättras med avseende på laddningstid och användbarhet.

Urval
-----------------------

Jag fortsatte jobba med de tre oljebolag jag använde i förra uppgiften. Varför jag valde just oljebolag är för att det ligger närma till hands då jag jobbar med oljor till vardags.

Metod
-----------------------

Jag öppnade sidorna i Firefox och använde dev-tools för att titta på laddningstid, sidstorlek och antal resurser. Jag valde tre olika sidor på varje webbplats och testade att öppna varje sida tre gånger för att få ett medelvärde.
Jag använde även [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) som är en webbplats som analyserar andra webbsidors innehåll och ger förslag på hur sidan kan göras snabbare. Resultatet redovisas där som ett hastighetsresultat med en siffra mellan 0 och 100 där 100 är snabbast. 90-100 är snabbt, 50-89 genomsnittlig och 0-49 är långsam.

Resultat
-----------------------

Nedan redovisas mina resultat från studien. Jag har delat upp och redovisar resultaten för webbplatserna var för sig.

En sammanställning av data finns i den länkade [excelfilen](../content/data/comparison.xlsx)

#####Preem

[FIGURE src=image/Preem_2.jpg?w=500 caption="Preems webbplats."]

[FIGURE src=image/Preem_start_PageSpeed_Insights.png?w=500 caption="Förbättringsförslag för Preems sida på mobil enhet"]

Jag valde följande tre sidor på Preems webbplats, [Startsidan](https://www.preem.se/privat/), [Hitta station](https://www.preem.se/hitta-station), [I butiken](https://www.preem.se/privat/i-butiken/).

Preem kan förbättra sin sida genom att använda bilder i modernare format, skjuta upp CSS som inte används och ta bort resurser som blockerar renderingen. Det är särskilt på mobila enheter sidan är långsam.

#####Shell

[FIGURE src=image/Svenska_Shell.png?w=500 caption="Shells webbplats."]

[FIGURE src=image/Shell_start_PageSpeed_Insights.png?w=500 caption="Förbättringsförslag för Shells sida på mobil enhet"]

Jag valde följande tre sidor på Shells webbplats, [Startsidan](https://www.shell.se/), [Bensinstationer](https://www.shellstationer.se/bensinstationer), [Kundservice](https://www.shellstationer.se/kundservice).

Shell kan förbättra sin sida genom att använda bilder med rätt storlek. De kan också göra sidan snabbare att ladda genom att läsa in viktiga resurser i förväg och ta bort resurser som blockerar renderingen.

#####Circle K

[FIGURE src=image/Circle_K_Sverige.png?w=500 caption="Circle Ks webbplats."]

[FIGURE src=image/CircleK_PageSpeed_Insights.png?w=500 caption="Förbättringsförslag för Circle Ks sida på mobil enhet"]

Jag valde följande tre sidor på Circle Ks webbplats, [Startsidan](https://www.circlek.se/sv_SE), [Sök station](https://www.circlek.se/sv_SE/pg1334072572280/privat/Vara-stationer/Sok-station.html), [Drivmedel](https://www.circlek.se/sv_SE/pg1334072442317/privat/drivmedel.html).

Circle Ks webbplats är den som tar längst tid att ladda på mobila enheter. Där finns mycket som kan optimeras. De kan ta bort resurser som blockerar renderingen, aktivera textkomprimering, skicka bilder i modernare format mm.

Analys
-----------------------

Alla tre webbplatserna får bra hastighetspoäng på testet när man tittar på dator men på mobila enheter är det sämre. Circle K är ganska usel och Preem är inte mycket bättre. Den klart bästa här är Shell.
Utav de tre webbplatserna utser jag Shell som vinnare. Deras sidor är de som laddas snabbast och är minst storleksmässigt.

Det som verkar vara den vanligaste orsaken till att sidan blir långsam är resurser som blockerar renderingen och hur bilder hanteras. Dels har bilderna fel storlek, dels har de fel filformat. Att åtgärda detta skulle snabba upp sidorna mycket.

En laddningstid på 4-6 sekunder tycker jag är tillräckligt snabbt och det klarar alla tre webbplatserna bra i testet.

Jag är dock inte riktigt säker på att analysen är rättvisande. När sidan analyseras med PageSpeed Insights antar jag att det är webbplatsen för dator som analyseras även för mobil. När jag testar att öppna sidorna på min mobil ser sidorna helt annorlunda ut. På Preems sida saknas tex. videon högst upp på sidan, den antar jag är en del som ökar laddningstiden en hel del. Det känns som sidorna laddar snabbt även på mobilen.

Referenser
-----------------------

[PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)

Firefox Developer Edition, dev-tools

[Moz](https://moz.com/learn/seo/page-speed)

Övrigt
-----------------------

Analys och rapport är gjord av Liselotte Westlin som enskilt arbete.
