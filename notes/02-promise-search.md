http://www.holderdeord.no/promises

### search-json

https://github.com/kareblak/search-json

### Data

Her er en ad-hoc representasjon av løftesøket som vi bruker internt:

```json
{
    "navigators": [
        {
            "query": {
                "parliament_period": "2013-2017",
                "promisor": "Arbeiderpartiet"
            },
            "title": "Søk",
            "param": "q",
            "type": {
                "keyword": true,
                "facet": false
            },
            "filter_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet&q=%7Bquery%7D",
            "value": null
        },
        {
            "query": "2013-2017",
            "title": "Periode",
            "param": "parliament_period",
            "type": {
                "keyword": false,
                "facet": true
            },
            "terms": [
                {
                    "name": "2013-2017",
                    "count": 847,
                    "active": true,
                    "clear_url": "/promises?promisor=Arbeiderpartiet",
                    "filter_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet"
                }
            ]
        },
        {
            "query": "Arbeiderpartiet",
            "title": "Parti / Regjering",
            "param": "promisor",
            "type": {
                "keyword": false,
                "facet": true
            },
            "terms": [
                {
                    "name": "Arbeiderpartiet",
                    "count": 847,
                    "active": true,
                    "clear_url": "/promises?parliament_period=2013-2017",
                    "filter_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet"
                }
            ]
        },
        {
            "query": null,
            "title": "Kategorier",
            "param": "category",
            "type": {
                "keyword": false,
                "facet": true
            },
            "terms": [
                {
                    "name": "Arbeidsliv",
                    "count": 56,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Arbeidsliv&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Arbeidsmiljø",
                    "count": 12,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Arbeidsmilj%C3%B8&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Arbeidsvilkår",
                    "count": 25,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Arbeidsvilk%C3%A5r&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Atomvåpen",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Atomv%C3%A5pen&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Avgifter",
                    "count": 5,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Avgifter&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Barn",
                    "count": 32,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Barn&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Barnehager",
                    "count": 18,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Barnehager&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Barnetrygd",
                    "count": 5,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Barnetrygd&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Barnevern",
                    "count": 16,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Barnevern&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Bergverk",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Bergverk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Bibliotek og litteratur",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Bibliotek+og+litteratur&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Boligsaker",
                    "count": 35,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Boligsaker&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Bygningsvesen",
                    "count": 5,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Bygningsvesen&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Den norske kirke",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Den+norske+kirke&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Departementer",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Departementer&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Distriktspolitikk",
                    "count": 26,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Distriktspolitikk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Domstoler",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Domstoler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "EFTA/EU",
                    "count": 13,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=EFTA%2FEU&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Eldreomsorg",
                    "count": 43,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Eldreomsorg&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Elektrisitet",
                    "count": 8,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Elektrisitet&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Energi",
                    "count": 43,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Energi&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Europarådet",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Europar%C3%A5det&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "FN",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=FN&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "FN-styrker",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=FN-styrker&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Familie",
                    "count": 27,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Familie&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Fangst",
                    "count": 8,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Fangst&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Fengsler",
                    "count": 5,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Fengsler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Ferger",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Ferger&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Finanser",
                    "count": 11,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Finanser&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Fiskeomsetning",
                    "count": 8,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Fiskeomsetning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Fiskerier",
                    "count": 17,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Fiskerier&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Folkehelse",
                    "count": 23,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Folkehelse&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Forbrukersaker",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Forbrukersaker&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Forskning",
                    "count": 45,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Forskning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Forsvar",
                    "count": 12,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Forsvar&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Forsvarsmateriell",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Forsvarsmateriell&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Forurensning",
                    "count": 10,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Forurensning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Fredsarbeid",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Fredsarbeid&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Funksjonshemmede",
                    "count": 20,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Funksjonshemmede&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Fylker",
                    "count": 11,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Fylker&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Fylkeskommunenes økonomi",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Fylkeskommunenes+%C3%B8konomi&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Grensespørsmål",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Grensesp%C3%B8rsm%C3%A5l&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Grunnskole",
                    "count": 59,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Grunnskole&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Handel",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Handel&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Havbruk",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Havbruk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Havner",
                    "count": 5,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Havner&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Helseinstitusjoner",
                    "count": 38,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Helseinstitusjoner&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Helsepersonell",
                    "count": 21,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Helsepersonell&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Helsevesen",
                    "count": 55,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Helsevesen&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Husbanken",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Husbanken&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Husdyr",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Husdyr&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Høgskoler",
                    "count": 21,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=H%C3%B8gskoler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Høyere utdanning",
                    "count": 30,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=H%C3%B8yere+utdanning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Idrett",
                    "count": 13,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Idrett&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Industri",
                    "count": 9,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Industri&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Innvandrere",
                    "count": 31,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Innvandrere&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Internasjonal rett",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Internasjonal+rett&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Internasjonalt samarbeid",
                    "count": 40,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Internasjonalt+samarbeid&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Jernbaner",
                    "count": 11,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Jernbaner&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Jordbruk",
                    "count": 7,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Jordbruk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kommunenes økonomi",
                    "count": 14,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kommunenes+%C3%B8konomi&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kommuner",
                    "count": 46,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kommuner&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kommunikasjon",
                    "count": 16,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kommunikasjon&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kriminalomsorg",
                    "count": 5,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kriminalomsorg&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kringkasting",
                    "count": 9,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kringkasting&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kultur",
                    "count": 43,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kultur&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kulturvern",
                    "count": 1,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kulturvern&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Kunst",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Kunst&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Landbruk",
                    "count": 19,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Landbruk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Landbruksprodukter",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Landbruksprodukter&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Likestilling",
                    "count": 21,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Likestilling&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Lokalforvaltning",
                    "count": 38,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Lokalforvaltning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Lotteri og spill",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Lotteri+og+spill&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Luftfart",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Luftfart&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Lønn",
                    "count": 14,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=L%C3%B8nn&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Massemedier",
                    "count": 9,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Massemedier&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Menneskerettigheter",
                    "count": 10,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Menneskerettigheter&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Merverdiavgift",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Merverdiavgift&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Militært personell",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Milit%C3%A6rt+personell&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Miljøvern",
                    "count": 43,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Milj%C3%B8vern&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "NATO",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=NATO&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Naturskader",
                    "count": 18,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Naturskader&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Naturvern",
                    "count": 19,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Naturvern&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Nordisk samarbeid",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Nordisk+samarbeid&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Norsk rikskringkasting",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Norsk+rikskringkasting&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Næringsliv",
                    "count": 46,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=N%C3%A6ringsliv&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Næringsutvikling",
                    "count": 28,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=N%C3%A6ringsutvikling&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Olje",
                    "count": 16,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Olje&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Oljeomsetning",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Oljeomsetning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Oljeutvinning",
                    "count": 9,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Oljeutvinning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Personvern",
                    "count": 7,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Personvern&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Polarområder",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Polaromr%C3%A5der&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Politi og påtalemyndighet",
                    "count": 23,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Politi+og+p%C3%A5talemyndighet&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Politiske partier",
                    "count": 1,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Politiske+partier&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Post",
                    "count": 1,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Post&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Priser og konkurranseforhold",
                    "count": 9,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Priser+og+konkurranseforhold&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Privatskoler",
                    "count": 1,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Privatskoler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Redningstjeneste",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Redningstjeneste&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Reindrift",
                    "count": 7,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Reindrift&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Reiselivsnæring",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Reiselivsn%C3%A6ring&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Rettsvesen",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Rettsvesen&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Rusmidler",
                    "count": 23,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Rusmidler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Samer",
                    "count": 10,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Samer&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Samferdsel",
                    "count": 24,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Samferdsel&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sikkerhet til sjøs",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sikkerhet+til+sj%C3%B8s&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sivil beredskap",
                    "count": 7,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sivil+beredskap&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sivilrett",
                    "count": 1,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sivilrett&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sjøfart",
                    "count": 8,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sj%C3%B8fart&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sjøfolk",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sj%C3%B8folk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Skatteadministrasjon",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Skatteadministrasjon&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Skatteavtaler",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Skatteavtaler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Skattefradrag",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Skattefradrag&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Skatter",
                    "count": 7,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Skatter&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Skogbruk",
                    "count": 5,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Skogbruk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Skoler",
                    "count": 54,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Skoler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sosialvesen",
                    "count": 53,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sosialvesen&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Spesialundervisning",
                    "count": 12,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Spesialundervisning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Språk",
                    "count": 12,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Spr%C3%A5k&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Statoil asa",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Statoil+asa&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Statsbedrifter",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Statsbedrifter&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Statsbudsjettet",
                    "count": 15,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Statsbudsjettet&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Statsforfatning",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Statsforfatning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Statsforvaltning",
                    "count": 37,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Statsforvaltning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Statslån",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Statsl%C3%A5n&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Strafferett",
                    "count": 10,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Strafferett&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Studiefinansiering",
                    "count": 11,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Studiefinansiering&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Svalbard",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Svalbard&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Svangerskap",
                    "count": 8,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Svangerskap&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sykdommer",
                    "count": 33,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sykdommer&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sykehus",
                    "count": 12,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sykehus&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Sysselsetting",
                    "count": 15,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Sysselsetting&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Særavgifter",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=S%C3%A6ravgifter&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Telekommunikasjoner",
                    "count": 27,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Telekommunikasjoner&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Toll",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Toll&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Trossamfunn",
                    "count": 10,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Trossamfunn&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Trygder",
                    "count": 24,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Trygder&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Ungdomsarbeid",
                    "count": 8,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Ungdomsarbeid&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Universiteter",
                    "count": 20,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Universiteter&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Utdanning",
                    "count": 98,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Utdanning&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Utenrikshandel",
                    "count": 13,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Utenrikshandel&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Utenrikssaker",
                    "count": 13,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Utenrikssaker&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Utviklingshjelp",
                    "count": 21,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Utviklingshjelp&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Valg",
                    "count": 6,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Valg&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Varehandel",
                    "count": 1,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Varehandel&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Vassdragsregulering",
                    "count": 4,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Vassdragsregulering&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Vegtrafikk",
                    "count": 7,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Vegtrafikk&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Vegvesen",
                    "count": 1,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Vegvesen&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Verftsindustri",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Verftsindustri&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Veterinærvesen",
                    "count": 2,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Veterin%C3%A6rvesen&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Videregående skoler",
                    "count": 62,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Videreg%C3%A5ende+skoler&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Voksenopplæring",
                    "count": 13,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=Voksenoppl%C3%A6ring&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                },
                {
                    "name": "Økonomisk samarbeid",
                    "count": 3,
                    "active": false,
                    "clear_url": "/promises?parliament_period=2013-2017&promisor=Arbeiderpartiet",
                    "filter_url": "/promises?category=%C3%98konomisk+samarbeid&parliament_period=2013-2017&promisor=Arbeiderpartiet"
                }
            ]
        }
    ],
    "results": [
        {
            "body": "Ap vil holde de samlede skattene og avgiftene på samme nivå som i dag.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Avgifter",
                "Merverdiavgift",
                "Skatteavtaler",
                "Skattefradrag",
                "Skatter",
                "Statsbudsjettet",
                "Særavgifter"
            ],
            "id": "9203",
            "type": "promise"
        },
        {
            "body": "Ap vil aktivt arbeide internasjonalt mot skattekonkurranse.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Internasjonalt samarbeid",
                "Næringsliv",
                "Priser og konkurranseforhold",
                "Utenrikshandel",
                "Utenrikssaker"
            ],
            "id": "9208",
            "type": "promise"
        },
        {
            "body": "Ap vil opprettholde arbeidstakernes rettigheter i sykelønnsordningen.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv",
                "Arbeidsvilkår",
                "Lønn",
                "Svangerskap",
                "Sykdommer"
            ],
            "id": "9210",
            "type": "promise"
        },
        {
            "body": "Ap vil styrke arbeidet mot sosial dumping og fremme nye tiltak i en tredje handlingsplan.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv",
                "Arbeidsvilkår",
                "Lønn"
            ],
            "id": "9215",
            "type": "promise"
        },
        {
            "body": "Ap vil sikre etterlevelse av likebehandlingsprinsippet ved bruk av innleie. De som leies inn, skal ha minst like gode lønns- og arbeidsvilkår som om de var ansatt direkte hos innleier.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv",
                "Arbeidsvilkår",
                "Lønn"
            ],
            "id": "9222",
            "type": "promise"
        },
        {
            "body": "Ap vil bruke handlingsrommet i EØS-avtalen aktivt for å ivareta arbeidstakerrettigheter.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv",
                "Arbeidsvilkår",
                "Internasjonalt samarbeid"
            ],
            "id": "9227",
            "type": "promise"
        },
        {
            "body": "Ap vil målrettet bruke ordningen med tilleggspoeng til utdanninger for det underrepresenterte kjønnet, i kombinasjon med andre rekrutteringstiltak, herunder bruk av ordningen på flere studier der det er få gutter.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Høyere utdanning",
                "Likestilling",
                "Studiefinansiering",
                "Utdanning"
            ],
            "id": "9234",
            "type": "promise"
        },
        {
            "body": "Ap vil mer overordnet og tydelig målformulering for å redusere detaljstyringen i blant annet oppdragsdokumentene.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Helsevesen",
                "Lokalforvaltning",
                "Statsbedrifter",
                "Statsforvaltning"
            ],
            "id": "9239",
            "type": "promise"
        },
        {
            "body": "Ap vil etablere bedre rutiner for å spre kunnskap om «beste praksis» i alle deler av offentlig sektor.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Departementer",
                "Fylker",
                "Kommuner",
                "Lokalforvaltning",
                "Statsforvaltning"
            ],
            "id": "9241",
            "type": "promise"
        },
        {
            "body": "Ap vil ha en god og løpende dialog med ideell sektor med sikte på å utvikle gode velferdstilbud for framtida.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Barnetrygd",
                "Sosialvesen"
            ],
            "id": "9246",
            "type": "promise"
        },
        {
            "body": "Ap vil definere tydeligere hva som er overordnede nasjonale interesser, sørge for at statlige aktører koordinerer seg bedre i planprosessene og ha som mål å begrense bruken av innsigelser i lokal og regional planlegging.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Boligsaker",
                "Bygningsvesen",
                "Distriktspolitikk",
                "Lokalforvaltning",
                "Statsforvaltning"
            ],
            "id": "9253",
            "type": "promise"
        },
        {
            "body": "Ap vil føre en mediepolitikk som legger til rette for at publikum får tilgang til kvalitetsjournalistikk på de plattformene de ønsker.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Kringkasting",
                "Massemedier",
                "Norsk rikskringkasting"
            ],
            "id": "9258",
            "type": "promise"
        },
        {
            "body": "Ap vil ha et lovverk som bidrar til å sikre en bredde i eierskap i mediene.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Kringkasting",
                "Massemedier",
                "Priser og konkurranseforhold"
            ],
            "id": "9260",
            "type": "promise"
        },
        {
            "body": "Ap vil likebehandle offentlige og private barnehager, og sikre at offentlige tilskudd og foreldrebetaling kommer barna til gode. Når man har oppnådd full likebehandling bør det også som hovedregel stilles like krav til barnehagene, for eksempel når det gjelder opptakskriterier.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Barnehager",
                "Familie",
                "Næringsliv"
            ],
            "id": "9265",
            "type": "promise"
        },
        {
            "body": "Ap vil avvikle kontantstøtten i neste stortingsperiode. Familier som har søkt om barnehageplass kan motta kontantstøtte fra foreldrepermisjonen tar slutt til barnehageplass tilbys.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Barnehager",
                "Barnetrygd",
                "Sosialvesen"
            ],
            "id": "9272",
            "type": "promise"
        },
        {
            "body": "Ap vil arbeide mot lagring av nye atomvåpen i Europa.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Atomvåpen"
            ],
            "id": "9900",
            "type": "promise"
        },
        {
            "body": "Ap vil knytte skole og SFO tettere sammen med kulturskole, idrett og frivillige aktiviteter, slik at elevene opplever et mest mulig helhetlig og variert aktivitetstilbud.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Grunnskole",
                "Idrett",
                "Kultur",
                "Skoler",
                "Ungdomsarbeid",
                "Videregående skoler"
            ],
            "id": "9296",
            "type": "promise"
        },
        {
            "body": "Ap vil sørge for at de som ikke kan klare seg med oppfølging fra helse- og omsorgspersonell hjemme, får tilgang til bolig med heldøgns omsorg eller sykehjemsplass.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Eldreomsorg",
                "Helseinstitusjoner"
            ],
            "id": "9594",
            "type": "promise"
        },
        {
            "body": "Ap vil aktivt fremme funksjonshemmedes rettigheter, bekjempe diskriminering og arbeide for å gi funksjonshemmedes barn tilgang til utdanning. [utviklingspolitikk].",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Utviklingshjelp"
            ],
            "id": "9892",
            "type": "promise"
        },
        {
            "body": "For å rette en særlig innsats mot bransjer som er spesielt utsatt for \nuseriøsitet og sosial dumping, vil Arbeiderpartiet blant annet videreutvikle treparts\nbransjeprogrammer som virkemiddel.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv",
                "Arbeidsvilkår"
            ],
            "id": "9929",
            "type": "promise"
        },
        {
            "body": "Ap vil inngå flere samarbeidsavtaler mellom staten og frivillig sektor på aktuelle områder, som beredskap og inkludering.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Kultur",
                "Sivil beredskap"
            ],
            "id": "9791",
            "type": "promise"
        },
        {
            "body": "Ap vil arbeide for en verden fri for atomvåpen gjennom gjensidig forpliktende nedrustning.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Atomvåpen"
            ],
            "id": "9897",
            "type": "promise"
        },
        {
            "body": "Ap vil følge opp Langtidsplanen for forsvaret 2013-2016, og sørge for en god økonomistyring i forsvaret og en langsiktig balanse mellom forsvarets oppgaver, struktur og økonomi.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Forsvar"
            ],
            "id": "9905",
            "type": "promise"
        },
        {
            "body": "Ap vil gjennomgå fritaks- og pliktgrunnlaget når verneplikten endres.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Militært personell"
            ],
            "id": "9912",
            "type": "promise"
        },
        {
            "body": "Ap vil videreutvikle og forsterke det nordiske forsvarssamarbeidet gjennom materiellanskaffelser, deltakelse i internasjonale operasjoner, utdanning, overvåking, beredskap og krisehåndtering og arktiske spørsmål.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Forsvar",
                "Forsvarsmateriell",
                "Nordisk samarbeid",
                "Polarområder",
                "Sivil beredskap",
                "Utdanning"
            ],
            "id": "9917",
            "type": "promise"
        },
        {
            "body": "Ap vil gi unge asylsøkere rett til videregående skoletilbud.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Innvandrere",
                "Utdanning"
            ],
            "id": "9924",
            "type": "promise"
        },
        {
            "body": "Ansatte som arbeider ved utsalgssteder, er i dag ikke omfattet av bestemmelsene om natt- og \nhelgearbeid i arbeidsmiljøloven. De har dermed ikke samme lovvern som andre arbeidstakere og \nsvekket innflytelse over egen arbeidstid. Arbeiderpartiet vil ta initiativ til en gjennomgang av dette med sikte på en helhetlig regulering \nsom sikrer arbeidstakernes behov for vern, medvirking og grunnleggende \nbedriftsdemokratiske prinsipper i ulike eierkonstruksjoner. Åpningstidsbestemmelsene \ngjennomgås parallelt med dette, med sikte på en modernisering. I tråd med den norske \nmodellen gjøres dette i samarbeid med partene i arbeidslivet.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv",
                "Arbeidsmiljø"
            ],
            "id": "9931",
            "type": "promise"
        },
        {
            "body": "Arbeiderpartiet er sterkt opptatt av å redusere omfanget av \nmidlertidige ansettelser og konsulentbruk, da dette kan svekke arbeidstakernes rettigheter, \nmedbestemmelse og det offentliges muligheter for å utvikle god kompetanse hos egne \nmedarbeidere.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsmiljø"
            ],
            "id": "9936",
            "type": "promise"
        },
        {
            "body": "Arbeiderpartiet mener at statlig kapital både skal være med å legge til rette for innovasjon og \nnyetableringer. Vi vil løpende vurdere behovet for kapital i de statlige investeringsselskapene \nInvestinor og Argentum. Arbeiderpartiet vil derfor styrke det statlige eierskapet.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Næringsutvikling"
            ],
            "id": "9943",
            "type": "promise"
        },
        {
            "body": "Arbeiderpartiet vil at det utvikles utdanningstilbud på høgere nivå både innen tekniske og administrative fag som gir verdensledende maritim kompetanse. Dette forutsetter oppbygging av noen særlig sterke fagmiljø.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Havbruk",
                "Sjøfart"
            ],
            "id": "9948",
            "type": "promise"
        },
        {
            "body": "Arbeiderpartiet vil videreføre og styrke nettolønnsordningen for sjøfolk.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Sjøfolk"
            ],
            "id": "9950",
            "type": "promise"
        },
        {
            "body": "Arbeiderpartiet vil blant annet følge opp klimameldingen slik at bygningskravene i teknisk forskrift blir passivhusnivå i 2015 og nesten nullenerginivå i 2020.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Energi",
                "Miljøvern"
            ],
            "id": "9955",
            "type": "promise"
        },
        {
            "body": "For å bidra til at \nen større andel av verdens energiproduksjon kommer fra fornybare kilder, vil Arbeiderpartiet \narbeide for at fossile subsidier avvikles og for at det etableres flere og bedre systemer for å \nprise utslipp av klimagasser.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Avgifter",
                "Energi",
                "Miljøvern"
            ],
            "id": "9962",
            "type": "promise"
        },
        {
            "body": "Arbeiderpartiet vil fortsette den nasjonale satsingen på klimateknologi, gjennom blant andre Enova og fondet \nfor klima, fornybar energi og energiomlegging.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Miljøvern"
            ],
            "id": "9967",
            "type": "promise"
        },
        {
            "body": "Reindriftsloven må evalueres spesielt med sikte på i større grad å verne om små aktører i \nprosesser der det totale reintallet skal ned. De næringspolitiske aspekter i de \nreindriftspolitiske virkemidlene må forsterkes.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Reindrift"
            ],
            "id": "9974",
            "type": "promise"
        },
        {
            "body": "Vi er opptatt av at utfordringene som [fiskeri]næringen i dag har, i hovedsak lakselus og rømming, må løses.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Fiskerier"
            ],
            "id": "9979",
            "type": "promise"
        },
        {
            "body": "Stebarnsadopsjoner i homofile familier skal gjennomføres raskere og enklere.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Familie"
            ],
            "id": "9981",
            "type": "promise"
        },
        {
            "body": "Allmenn informasjon må være tilgjengelig for alle. Det betyr for eksempel at informasjon må \nvære tilgjengelig på lydfil, i tillegg til å foreligge i elektronisk form.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Funksjonshemmede"
            ],
            "id": "9986",
            "type": "promise"
        },
        {
            "body": "Arbeiderpartiet vil fortsette å forbedre ordningene for refusjon gjennom folketrygden til spesielle diagnoser.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Helsevesen"
            ],
            "id": "9993",
            "type": "promise"
        },
        {
            "body": "Ap vil bevare deltakerloven og råfiskloven.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Fangst",
                "Fiskeomsetning",
                "Fiskerier",
                "Statsforvaltning"
            ],
            "id": "9474",
            "type": "promise"
        },
        {
            "body": "Ap vil utvikle gode samhandlingsarenaer mellom maritime og marine næringer og forsterke innsatsen på forskning, teknologiutvikling og innovasjon i fiskeri og havbrukssektoren.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Fangst",
                "Fiskeomsetning",
                "Fiskerier",
                "Forskning",
                "Næringsutvikling"
            ],
            "id": "9479",
            "type": "promise"
        },
        {
            "body": "Ap vil bidra til at lokalsamfunn får tilbake for å stille sine arealer til disposisjon for havbruksnæringen ved at en andel av vederlaget fra nye konsesjoner skal tilfalle kommunene.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Havbruk",
                "Kommuner",
                "Lokalforvaltning"
            ],
            "id": "9481",
            "type": "promise"
        },
        {
            "body": "Ap vil bruke offentlige virkemidler for å sikre [IKT-]tilgang der markedsbaserte løsninger ikke etableres.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Telekommunikasjoner"
            ],
            "id": "9486",
            "type": "promise"
        },
        {
            "body": "Ap vil at befolkningen skal ha digital kompetanse og bruke digitale tjenester på en trygg og sikker måte.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Kommunikasjon",
                "Telekommunikasjoner"
            ],
            "id": "9493",
            "type": "promise"
        },
        {
            "body": "Ap vil at graderte ytelser og mulighet til å være delvis i arbeid ved sykdom eller uførhet skal være et aktivt virkemiddel for helse og deltakelse.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv",
                "Funksjonshemmede",
                "Sykdommer",
                "Trygder"
            ],
            "id": "9498",
            "type": "promise"
        },
        {
            "body": "Ap vil at personer med rusproblemer skal få tett oppfølging i form av en kombinasjon av hjelp til å mestre rusproblemene og arbeidstrening. Oppfølgingen skal tilbys i form av et individuelt program etter modell av kvalifiseringsprogrammet.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Sosialvesen",
                "Trygder"
            ],
            "id": "9501",
            "type": "promise"
        },
        {
            "body": "Ap vil at sivilsamfunnet skal involveres i arbeidet med å få flere i arbeidslivet. Initiativ i regi av ideelle aktører vil kunne nå ut til målgrupper som tradisjonelt ikke oppsøker NAV eller offentlige tjenester.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Arbeidsliv"
            ],
            "id": "9506",
            "type": "promise"
        },
        {
            "body": "Ap vil vurdere medlemskapsbestemmelsene i Folketrygden for å forhindre misbruk av folketrygdytelsene.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Innvandrere",
                "Sosialvesen",
                "Trygder"
            ],
            "id": "9513",
            "type": "promise"
        },
        {
            "body": "Ap vil styrke rådgivning om gjeld og økonomi ved NAV-kontoret og sørge for at dette inngår som en del av oppfølgingen i individuell plan.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Sosialvesen",
                "Trygder"
            ],
            "id": "9518",
            "type": "promise"
        },
        {
            "body": "Ap vil innføre 12 måneders studiestøtte for studenter med barn og økt forsørgerstipend for de med lavest inntekt.",
            "party_names": [
                "Arbeiderpartiet"
            ],
            "parliament_period_name": "2013-2017",
            "promisor_name": "Arbeiderpartiet",
            "category_names": [
                "Barn",
                "Familie",
                "Studiefinansiering"
            ],
            "id": "9520",
            "type": "promise"
        }
    ],
    "next_url": "/promises?page=2&parliament_period=2013-2017&promisor=Arbeiderpartiet",
    "previous_url": null,
    "current_page": 1,
    "total_pages": 17
}
```
