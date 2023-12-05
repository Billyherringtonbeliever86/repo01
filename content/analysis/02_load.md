Titel på rapporten
=======================

<p> Uppgiften handlar om att jämföra olika sidor och se vilka och var dem värnar om sin laddningstid och om att ha effektiva och smarta resurs sparningar samt dokumentera dem </p>

Urval
-----------------------

Jag har valt 3 webbplateser baserade på deras eftefrågan och populäritet den första och minsta är en hemsida till en resturang här i karlshamn som har minst resurser och minnst trafik. Den andra är en större webbplats med flera besökare. Sist men störst blir den största och populäraste webbplatesen med mest resurser och som just nu är den andra största webbplatesen i världen. Syftet med detta är att se hur dem tre olika nivåerna av webbplateser tar sig an att effektivisera sinna laddningstider.
<a href="https://www.sushimakibnr.se/" target = "_blank"> resturang - liten </a></br>
<a href="https://www.blt.se/" target = "_blank"> Blt nyheter - mellan</a></br>
<a href="https://www.youtube.com/" target = "_blank"> youtube - stor </a>

Metod
-----------------------

Jag kommer använda mig av devtools för att kolla eventuella laddningstider samt bild storlekar. Jag kommer änven använda hemsidan pagespeed insights för att få fram flera laddningstider. Jag testar all 3 hemisdor mot vertygen och sedan fyller jag i datan i ett excel ark.


Resultat
-----------------------
<h2> Sushimaki </h2>

Sushimakis hemsida fick en okej till bra betyg av page speed när det kommer till dekstop men mycket mer klagomål på mobil testet. Sidan verkar ha skapats med en hemsido byggare på nätet som heter wix. Sidan verkar vara dominant i Js med många scripts och moduler som laddas in genomsnittet kom till 150 requests. Som ni ser verkar sig skaparen ha förlitat sig på wix verktyget och kunskaperna verkar låga eftersom det finns bilder som saknas och horisontela skrollbars

![alt text](%assets_url%/img/sushi.png)

Sushimakis hemsida verkar ha fått den bästa ratingen utav alla hemsidorna av PS (pagespeed insights). Hemsidan bör främst reducera sin användning av främst JS scripts men också css scripts som inte används då hade dem gynnat 2.4s.

<h2> Blt </h2>

Blt snittar sämre en sushimaki på PS testerna med en desktop prestanda på 41 och mobil på 38 från sushimakis 86 oh 47. Laddningstiden för 3g gick upp stort från vanligt internet även fast resurserna stannade dem samma i storlek. Den har på 3g den längsta genomsnittliga laddnings tiden som kom till 6.05 sekunder.

![alt text](%assets_url%/img/blt.png)

Blts främsta råd enligt PS är att Minska arbetsbelastningen på modertråden vilket igen handlar om att skära ner på / effektivisera sin användning av javascript.

<h2> youtube </h2>

Youtube som är den största hemsidan med väldigt mycket saker på sig är 
även störst i resurser på ca 16mb. Youtube kalara sig marginalt bättre en Blt på PS testerna. Det verkar dock vara sörligar öfr mobil användare med 3g där load timen kommer upp i 17,35s.

![alt text](%assets_url%/img/youtube.png)

Youtube har 2 åtgärder som PS uppskattar skulle bespara var för sig ca 1 sekund och det är att reducera javascripts som inte används och Läs in bilden i förväg för största uppritningen av innehåll.

<h2> Data </h2>
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTGMoKzqTpVUCPvcj0mpjv_gaA0QzE50ZaGGld37xmt1GBltmGXOqxMeLTb3xa29X9gEVkSjjaLX4bs/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" class = "excel"></iframe>

PS står för Pagespeed tester och M står för mobil läge. 
3g mättningarna var gjorde med 3g fast. Alla network tider är ett genomsnitt på 3 laddningar.


Analys
-----------------------

Det verkar som att bigger är inte better när dem kommer till sidors laddningshastighet. Boven verkar i varje fall ha med JS att göra och hur man hantera scriptsen. Men eftersom dessa sidor är går från mindre till större i inte bara trafik och resurser men också resurser i mb på hemsidan samnt endamål. Sushimakis hemsida är väldigt enkel och har ett enkelt endamål att presentera resturanges medans youtube är en stor streaming tjänst med miljontals tittare och stora algoritmer med mera som jobbar i bakgrunden. Detta måste ta i åtanke för att utse en vinnare av hemsidorna.
Jag väljer att Youtube kommer först och sushimaki 2a blt kommer sist och har den sämsta genomsnittliga poängen av alla även fast den har större endamål en suhimaki räker inte detta.

Jag tycker mellan 2 till 4 sekunder är en rimlig laddnings tid för en hemsida och gör sidan användar vänlig. Både youtbe och och sushimaki klarar detta men blt hamnar på 6s vilket känns länge.  Alla hemsidor förtuom blt känns snabba i vanligt internet med när det kommer till 3g tar youtube och blt väldigt långtid på sig, över 10 sekunder då känns det sakta.


Referenser
-----------------------

Inga referenser

Daniel Svensson