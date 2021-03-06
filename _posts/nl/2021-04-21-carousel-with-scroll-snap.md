---
title: Carousel met scroll snap
---

Scroll snap is een relatief nieuwe feature in CSS, die sindskort ook [behoorlijke goed ondersteund](https://caniuse.com/?search=scroll%20snap) wordt. Deze feature was 'good for nothing', aldus [een angry mob in 2016](https://css-tricks.com/introducing-css-scroll-snap-points/). Drie jaar later werd de carousel met scroll snap van Nolan Lawsons echter een stuk positiever ontvangen.

Het was echter niet de carousel van Nolan, maar de [Google Scroll Survey](https://web.dev/2021-scroll-survey/) die mij inspireerde. Een standaard 'header carousel' is de perfecte 'use case' voor scroll snap. Ik liep tegen Nolans werk aan tijdens mijn onderzoek hiernaar. Nolan [beschrijft](https://nolanlawson.com/2019/02/10/building-a-modern-carousel-with-css-scroll-snap-smooth-scrolling-and-pinch-zoom/) drie componenten: 'scroll snap', 'smooth scroll' en 'pinch to zoom'. In onze carousel hebben we echter geen pinch to zoom nodig en smooth scroll werkt tegenwoordig met slechts een enkele regel CSS. Ik hoefde dus alleen maar scroll snapping te bouwen. Nolan maakte zich nog druk om IE support, maar wij uiteraard niet meer. Daardoor kon ik anchor links gebruiken in plaats van javscript voor smooth scroll, wat resulteerde in betere prestaties en 'graceful degredation'.

## Benieuwd naar het resultaat? 

Check mijn [carousel met native scroll en touch ondersteuning](https://codepen.io/joosts/pen/MWJBPgo?editors=0010) op Codepen. De carousel scrollt soepel, 'degradeert' mooi en is slechts 3kb groot.

## Wat betekent dit?

Fantastisch! Maar ik kijk ook graag naar wat deze vooruitgang betekent in het grotere geheel. Door moderne technologie kunnen we namelijk steeds lichtere websites bouwen. HTML en CSS worden steeds krachtiger. Wat [ooit](https://flickity.metafizzy.co) 120kb vereiste, kan nu in minder dan 3kb gerealiseerd worden. We hebben ook steeds [meer bandbreedte](https://www.nngroup.com/articles/law-of-bandwidth/) en snellere computers tot onze beschikking. Deze combinatie leidt tot veel nieuwe mogelijkheden. Wat in 2008 nog onmogelijk leek en slechts [een grappige reclame](/blog/websites-that-load-instantly) was, ligt nu binnen handbereik: [het laden van een volledige website in 0.1 seconde](/blog/websites-that-load-instantly). Hoewel [direct ladende websites](/blog/websites-that-load-instantly) beter bereik, meer conversie en een betere gebruikservaring hebben, beweegt onze branche niet per se in die richting. Gemiddeld worden website steeds [zwaarder](https://httparchive.org/reports/page-weight), wat mogelijk wordt gemaakt door de [toenemende bandbreedte](https://www.nngroup.com/articles/law-of-bandwidth/). Maar, zoals verwacht, neemt ook [de variatie](https://httparchive.org/reports/page-weight) toe. Dit betekent dat je tegenwoordig een keuze hebt. 


## De keuze is aan jou

Wil je dat je volgende website traag en zwaar is, of... wordt het een razendsnel en vederlicht wonder van moderne techniek? De keuze is aan jou. Geïnteresseerd? [Neem contact op!](/contact)