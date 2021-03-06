---
title: Carousel with scroll snap
---

Scroll snap is a relative new feature in CSS, that recenty got [pretty decent support](https://caniuse.com/?search=scroll%20snap). It was 'good for nothing', if you believed [these folks in 2016](https://css-tricks.com/introducing-css-scroll-snap-points/). But three years later Nolan Lawsons carousel with scroll snap was received much better.

But it was not Nolan, but the [Google Scroll Survey](https://web.dev/2021-scroll-survey/) that inspired me. The perfect use case for scroll snapping is a standard header carousel. I found Nolans work while doing research for building one. Nolan [described](https://nolanlawson.com/2019/02/10/building-a-modern-carousel-with-css-scroll-snap-smooth-scrolling-and-pinch-zoom/) three components: 'scroll snap', 'smooth scroll' and 'pinch to zoom'. We do not need pinch to zoom and today we can achieve smooth scroll with a single line of CSS. Therefore I only needed to implement this one component: scroll snapping. Nolan was still worried about IE support, but we are not. Therefore I used anchor links instead of javascript for smooth scrolling, resulting in better performance and better degredation.

## Interested in the result? 

Check out my [natively scrolling carousel with touch support](https://codepen.io/joosts/pen/MWJBPgo?editors=0010) on Codepen. It has got buttery smooth scrolling, degrades nicely and is just 3kb large.

## Putting it in perspective

Great! But what does this mean in the bigger scheme of things? Modern technology allows us to build lighter websites, because HTML and CSS are getting more powerful. What [once](https://flickity.metafizzy.co) required 120kb, can now be achieved in under 3kb. We also have [more bandwith](https://www.nngroup.com/articles/law-of-bandwidth/) available and faster computers. This combination leads to new possibilities. What was deemed impossible in 2008 and was just [a fun commercial](/blog/websites-that-load-instantly), is now actually within reach: [loading a full website in 0.1 seconds](/blog/websites-that-load-instantly). Although [instantly loading websites](/blog/websites-that-load-instantly) have better reach, better conversion and a better user experience, this is not the direction in which web development is moving. On average, websites are getting [bulkier](https://httparchive.org/reports/page-weight), allowed by the [increasing bandwidth](https://www.nngroup.com/articles/law-of-bandwidth/). But, as expected, [the variation](https://httparchive.org/reports/page-weight) is also getting larger. This means that you now have a choice.

## You now have a choice

Do you want your next website to be slow and bulky, or... do you want it to a blazing fast and lightweight marvel of modern technology? The choice is yours. Interested? [Contact me!](/contact)