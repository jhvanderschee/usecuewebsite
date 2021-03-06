---
title: 'Goodbye Google'
---

Today I found out that Google Maps on my website showed a dark 'for development purposes only' overlay. As a website developer and host I am responsible for hundreds of websites, so, as you can understand, I panicked. 

I soon found out that I was in good company. The website of the Communal Transportation Company of the capital of the Netherlands, used by half a million people a day, was broken too. You can see this here:

<a href="/uploads/gvb.png" style="display: block;"><img src="/uploads/gvb_pattern.png" style="display: block;" /></a>

My browsers development console showed red errors and a pop-up was shown. It were messages from Google for the owner of the website, and they read: 'The request is missing an API key, billing has not been enabled on your account, the provided billing method is invalid (for example an expired credit card) or a self-imposed daily limit has been exceeded'. Googling for 'Google Maps API billing' led to a page headed 'Pricing that scale to fit your needs'. I read that I could continue to use Google Maps if I entered my billing information. 

> This was Google saying: We broke your website without warning, and we will hold it hostage until you give us a credit card number.

What to do? Send my client an email? Begging for money? And for how much? Or worse... ask them for their credit card number?

I was angry. I did not want my websites to stop working, but could not ask my clients for money as a result of my poor judgement. And with 'poor judgement' I mean 'choosing Google as a partner in software development'. Google had stabbed me in the back. I had not expected them to be this unreliable, but here I was, facing the ugly truth. I had read that Google was losing ground (advertising income) to Amazon and Facebook, but I never thought that that would influence their loyalty towards developers. The once so popular company (amongst developers) had become greedy and irresponsible. I do not know what I found more appalling: that they had broken millions of websites or that they were blaming us with their 'for development purposes only' message.

I did the only thing I could do: I replaced Google Maps on every single website I hosted. It costed me thousands of dollars in lost income. I replaced Google Maps by [the open-source Leaflet library](https://leafletjs.com/) and Open Street Maps or by a self-rolled SVG maps solution (see: [beukenbuurt.amsterdam](https://beukenbuurt.amsterdam/)). It has an up-side: Leaflet has much better documentation than Google Maps and my self-rolled SVG solution is fully GDPR complaint.

Google as a partner in web development? Never again! Google, you can stick your over-priced Compute Engine and all its API's in a place where the sun does not shine... Yes... I mean one of those unused data centers you own. Goodbye Google.