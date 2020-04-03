#Covid-19 data

**Important:** Since I started scrapping the [SARS-CoV-2 dashboard](http://aquas.gencat.cat/ca/actualitat/ultimes-dades-coronavirus), Generalitat de Catalunya has provided datasets with more data than what I scrap in their open data portal. These datasets include [COVID-19 tests by sex and *àrea bàsica de salut*](https://analisi.transparenciacatalunya.cat/Salut/Registre-de-test-de-COVID-19-realitzats-a-Cataluny/xuwf-dxjd), [COVID-19 tests by sex and age](https://analisi.transparenciacatalunya.cat/Salut/Registre-de-test-de-COVID-19-realitzats-a-Cataluny/qwj8-xpvk) and [COVID-19 tests by sex and city](https://analisi.transparenciacatalunya.cat/Salut/Registre-de-test-de-COVID-19-realitzats-a-Cataluny/jj6z-iyrp)
For the sake of completeness I'll continue scrapping the data until this finishes.

This data is dayly scrapped from the Generalitat de Catalunya [SARS-CoV-2 dashboard](http://aquas.gencat.cat/ca/actualitat/ultimes-dades-coronavirus) via [this](https://github.com/ibesora/covid-19-scrapper) scrapper

**Notice:** Seeing that the data is being constantly updated during the day I've automated the scrapper to run each day at midnight so we get the complete data of that same day. As a consequence, the first day of data, scrapped on 2020-03-28 has been flagged as 2020-03-27 data.

**Notice 2:** Due to a code error on the scrapper, data from "Arees Bàsiques" is not available for 2020-03-28. Sorry about that.