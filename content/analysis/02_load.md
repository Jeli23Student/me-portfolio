---
Title: Load
Description: This a loading analysis page
---

# Loadingtimes analysis

<h1>Laddningstid analys</h1>
Denna uppgiften handlar om att utvärdera laddningstiden på tre webbplatser.

Urval
chess.com - Världens största onlinechess hemsida.
avanza.se - Sveriges mest använda verktyg för aktiehandel.
fiaformula2.com - Onekligen roligaste race-serien i värdlen, F1 förarare utan konsekvenstänk! Fungerar som en farmarliga till F1.

Valde ovan tre av anledning att det var de tre översta hemsidorna som dök upp i sökfältet i Firefox. Samt att jag gjorde min färganalys av dessa så nu får jag se om de är bra på annat också!

<h1>Metod</h1>
Jag använde verktyget PageSpeed Insights för att få fram betyget på respektive sida både på desktop och mobil. DevTools för att analysera laddningstiden, antal resurser och totala storleken på sidan.

<h1>Reslutat</h1>
<iframe height="275" width="92%" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRVmhKdwLNBi4659C_-RuZ28Icy1wssAVaSM4_ChevyLDyG7UOnBUuMNzpDYvujUadgEfDMxdwr9rhe/pubhtml?widget=true&amp;headers=false"></iframe>

<h1>Chess.com</h1>

<div class=image-container>
    <img src="../themes/jesper/images/chess_com.png" alt="Chess.com">
</div>

Hemskärmen fick grymt bra resultat för desktop och mobil, då den är väldigt enkel. Puzzle sidan kan förbättras genom att optimera resurshanteringen, exempelvis genom att minska antalet och storleken på resurserna (250 resurser och 11,22 MB är högt), vilket kan korta ned laddningstiden för både mobil och desktop, och därmed förbättra användarupplevelsen.

<h1>Avanza.se</h1>

<div class=image-container>
    <img src="../themes/jesper/images/avanza_se.png" alt="Avanza.se">
</div>

Hemskärmen fick horribelt resultat Avanza.se kan förbättra sin prestanda genom att minska sidans totala storlek (7,62 MB) och optimera resurserna, särskilt för mobilanvändare, för att förbättra Pagespeed-scoren och säkerställa snabbare laddningstider även vid lägre bandbredd. Deras sidor för aktier är ännu tyngre och kan anses behöva åtgärdas akut för mobilanvändare. Eller inte då de hänvisar sina användare till appen som förhoppningsvis är snabbare!

<h1>FiaFormula2.com</h1>

<div class=image-container>
    <img src="../themes/jesper/images/formula2_com.png" alt="FiaFormula2.com">
</div>

Hemskärmen fick grymt bra resultat för desktop och lite sämre för mobilen. Driver sidan kan förbättras genom att optimera resurshanteringen, exempelvis genom att minska antalet och storleken på resurserna. För desktop versionen så är det fortfarande väldigt bra, men lite mer optimering för mobilversionen behövs.

<h2>Sammanfattning</h2>

Jag anser att en snabb webbplats laddar på under 1 sekund, medan en långsam webbplats laddar på över 2 sekunder. Generellt visar urvalet att det finns stor potential för optimering på alla sidor, särskilt för mobilanvändare, men Chess presterar bäst i snabbhet.

Author: Jesper Liljeroos
