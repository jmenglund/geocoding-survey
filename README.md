# Geografisk information i naturhistoriska samlingsdatabaser

Här finns en sammanställning över lokalinformation i naturhistoriska samlingar i Sverige. Materialet har tagits fram för att ge en bakgrund till ansökan om  finansiering av DINA-projektet från Svenska artprojektet för perioden 2017–2019.

Se även ArtDatabankens information om stöd till biologiska samlingar: [](http://www.artdatabanken.se/verksamhet-och-uppdrag/svenska-artprojektet/stoed-till-biologiska-samlingar/)


Detta repo innehåller två filer:

#### gbif-collection-stats-20160401.csv

Genomgång av geografisk och taxonomisk information för svenska poster hos GBIF. Filen har följande innehåll:

| Kolumn                  | Beskrivning                                     |
| ----------------------- | ----------------------------------------------- |
| dataset                 | namn på datasetet                               |
| date_checked            | datum då kontrollen gjordes på GBIF             |
| records                 | totalt antal poster                             |
| swe                     | antal svenska poster                            |
| swe_georef              | antal georefererade svenska poster              |
| swe_georef_noissue      | antal georefererade svenska poster utan problem |
| taxon_match_none        | antal svenska poster utan matchande taxon       |
| taxon_match_higher_rank | antal svenska poster som matchar högre taxon    |
| taxon_match_fuzzy       | antal svenska poster med oskarp taxonmatchning  |


#### geocoding-survey.ipynb

[Jupyter Notebook](http://jupyter.org) med lite mer detaljerade uppgifter om den geografiska informationen i några samlingar vid Naturhistoriska riksmuseet i Stockholm.