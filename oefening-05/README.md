# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /top-headlines.
3. Voeg een X-Api-Key header toe met je API-sleutel.
4. Voer het verzoek uit en bekijk de respons.

https://newsapi.org/v2/top-headlines?sources=bbc-news

:

{
    "status": "ok",
    "totalResults": 10,
    "articles": [
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "US Speaker Mike Johnson may pay political price for Ukraine deal",
            "description": "Republican Mike Johnson can savour a hard-fought victory, but hard-line colleagues are plotting to oust him.",
            "url": "https://www.bbc.co.uk/news/world-us-canada-68866912",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/D502/production/_133203545_mediaitem133203544.jpg",
            "publishedAt": "2024-04-20T20:52:20.5931133Z",
            "content": "Media caption, Watch the moment the US House passed critical Ukraine aid package\r\nAfter months of delay and increasingly dire warnings, the US House of Representatives approved $61bn in new aid to Uk… [+4764 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "USC: University cancels all outside graduation ceremony speakers after controversy",
            "description": "It comes after the decision to cancel a speech by a Muslim student sparked protests on campus.",
            "url": "https://www.bbc.co.uk/news/world-us-canada-68863345",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/DBF6/production/_133201365_gettyimages-2147911890.jpg",
            "publishedAt": "2024-04-20T20:22:13.2650148Z",
            "content": "The University of Southern California (USC) has cancelled outside speakers for this year's graduation ceremony.\r\nIt follows controversy surrounding the cancellation of the university's valedictorian … [+3165 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "Mandisa: American Idol singer dies aged 47",
            "description": "Tributes are being paid to the gospel singer who won a Grammy in 2014 for her record Overcomer.",
            "url": "https://www.bbc.co.uk/news/entertainment-arts-68863609",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/18326/production/_133201199_gettyimages-495218263.jpg",
            "publishedAt": "2024-04-20T19:22:20.9869317Z",
            "content": "Tributes are being paid after Grammy-winning American Idol singer Mandisa Lynn Hundley died at the age of 47.\r\nPaula Abdul, who was a judge during her Idol season in 2006, called her a \"true beacon o… [+1163 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "Ukraine Russia war: US House passes crucial Ukrainian aid deal worth $61bn",
            "description": "The House of Representatives has passed a long-stalled package that could reshape Kyiv's war effort.",
            "url": "https://www.bbc.co.uk/news/world-us-canada-68848277",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/137C2/production/_133201897_gettyimages-2136563370.jpg",
            "publishedAt": "2024-04-20T18:22:19.4087932Z",
            "content": "The House of Representatives has voted in favour of billions of dollars in US military aid for Ukraine after months of delay.\r\nThe measure had vocal opponents in Congress, and it took a fragile bipar… [+5903 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "Thousands rally in Spain's Canary Islands against mass tourism",
            "description": "Protesters demand curbs on tourists numbers and uncontrolled development in the Spanish archipelago.",
            "url": "https://www.bbc.co.uk/news/world-europe-68865755",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/38C2/production/_133203541_snipimage.jpg",
            "publishedAt": "2024-04-20T17:37:16.1356039Z",
            "content": "Tens of thousands of people in Spain's Canary Islands have rallied against a model of mass tourism they say is overwhelming the Atlantic archipelago.\r\nThe protesters want limits on tourist numbers an… [+2064 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "Taylor Swift: The Tortured Poets Department broke Spotify record",
            "description": "The Tortured Poets Department became Spotify's most-streamed album in a single day, the platform said.",
            "url": "https://www.bbc.co.uk/news/entertainment-arts-68863614",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/16E1/production/_133175850_fd0592d7-b75b-45ec-bedd-18847a0e0eda.jpg",
            "publishedAt": "2024-04-20T15:52:18.5700895Z",
            "content": "Taylor Swift's new album, The Tortured Poets Department, has broken the record for Spotify's most-streamed in a single day, the platform said.\r\nThe pop sensation also became the most-streamed artist … [+2504 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "Trump jury members set for opening statements: Who are they?",
            "description": "The five women and seven men make up a highly educated group who will deliberate on the case.",
            "url": "https://www.bbc.co.uk/news/world-us-canada-68848665",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/846B/production/_133199833_trump_trials_promo-9-976.png",
            "publishedAt": "2024-04-20T13:37:19.6313519Z",
            "content": "In just three days, a court has weeded through hundreds of Manhattanites, selecting 12 people and six alternates to serve on the jury in the first-ever criminal trial of a former president. \r\nFinding… [+5222 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "Explosion hits Iraqi military base housing pro-Iranian militia",
            "description": "The militia blamed an attack, while Iraq's military said it did not detect drones or jets in the area.",
            "url": "https://www.bbc.co.uk/news/world-middle-east-68863981",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/C936/production/_133201515_gettyimages-2147941276.jpg",
            "publishedAt": "2024-04-20T11:07:17.6784808Z",
            "content": "A military base in Iraq housing a pro-Iranian militia has been damaged in an explosion, killing one and wounding eight, security officials there have said. \r\nIraq's military reported no drones or fig… [+1866 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "Man who set himself on fire outside Trump's Manhattan hush money trial dies",
            "description": "Maxwell Azzarello doused himself in liquid before throwing conspiracy-theory pamphlets, police said.",
            "url": "https://www.bbc.co.uk/news/world-us-canada-68863157",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/13FEC/production/_133200918_screenshot2024-04-20065145.png",
            "publishedAt": "2024-04-20T06:52:18.2407922Z",
            "content": "Media caption, Someone screamed 'don't do it' before man set himself on fire - BBC reporter\r\nA man who set himself on fire outside the Manhattan court where former President Donald Trump's hush-money… [+2492 chars]"
        },
        {
            "source": {
                "id": "bbc-news",
                "name": "BBC News"
            },
            "author": "BBC News",
            "title": "'How gold becomes guns': heist spotlights illegal US-Canada gun trade",
            "description": "The majority of handguns used in Canadian crimes come from the US, where gun laws are much more lax.",
            "url": "https://www.bbc.co.uk/news/world-us-canada-68841961",
            "urlToImage": "https://ichef.bbci.co.uk/news/1024/branded_news/13E9C/production/_133146518_gh2.jpg",
            "publishedAt": "2024-04-20T01:22:12.8425871Z",
            "content": "The arrests that followed a \"sensational\" gold heist have shed light on the illegal gun trade between the US and Canada. \r\nThousands of gold bars worth C$20m ($14.5m; £11.6m) were stolen from the Tor… [+4470 chars]"
        }
    ]
}
