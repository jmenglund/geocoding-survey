# Geografisk information i naturhistoriska samlingsdatabaser

Här finns en sammanställning över lokalinformation i naturhistoriska samlingar i Sverige. Materialet har tagits fram för att ge en bakgrund till ansökan om  finansiering av DINA-projektet från Svenska artprojektet för perioden 2017–2019.

Se även ArtDatabankens information om stöd till biologiska samlingar: [http://www.artdatabanken.se/verksamhet-och-uppdrag/svenska-artprojektet/stoed-till-biologiska-samlingar/](http://www.artdatabanken.se/verksamhet-och-uppdrag/svenska-artprojektet/stoed-till-biologiska-samlingar/)


Detta repo innehåller två filer:

* gbif-collection-stats-20160401.csv
* geocoding-survey.ipynb


#### gbif-collection-stats-20160401.csv

Genomgång av geografisk och taxonomisk information för svenska poster hos GBIF under april 2016. Filen har följande innehåll:

| Kolumn                    | Beskrivning                                     |
| ------------------------- | ----------------------------------------------- |
| dataset                   | namn på datasetet                               |
| url                       | webbadress till dataset                         |
| date\_checked             | datum då uppgifterna hämtades från GBIF         |
| date\_published           | datum då datasetet publicerades på GBIF         |
| records                   | totalt antal poster                             |
| swe                       | antal svenska poster                            |
| swe\_georef               | antal georefererade svenska poster              |
| swe\_georef\_noissue      | antal georefererade svenska poster utan problem |
| taxon\_match\_none        | antal svenska poster utan matchande taxon       |
| taxon_match\_higher\_rank | antal svenska poster som matchar högre taxon    |
| taxon\_match\_fuzzy       | antal svenska poster med oskarp taxonmatchning  |
| dataset_sv                | svensk benämning på datasetet (som används här) |



#### geocoding-survey.ipynb

En [Jupyter Notebook](http://jupyter.org) med lite mer detaljerade uppgifter om den geografiska informationen i några samlingar vid Naturhistoriska riksmuseet i Stockholm.

Rådata som ligger till grund för statistiken skickas vid förfrågan. Kontakta [Markus Englund](http://www.nrm.se/ommuseet/kontakt/sokmedarbetare) vid Naturhistoriska riksmuseet.