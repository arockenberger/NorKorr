# NorKorr – Norwegian Correspondences and Linked Open Data
## About the Project

The National Library of Norway has a substantial amount of private historical correspondences in its holdings, many of which are edited and published, either in printed editions or digitally. In addition, institutions of cultural heritage, like the Munch Museum, as well as Norwegian universities, like the University of Oslo, the University of Bergen and the Arctic University of Tromsø prepare digital editions of letters and correspondences of key figures of Norwegian public and academic life. Yet, these correspondences lead a solitary existence - hidden in editions of single authors. As a dialogical genre, their full potential lies in the connection of those sending and receiving letters, postcards, and telegrams - at a specific time and from and to a specific place. Because the collections of correspondences are distributed geographically and institutionally, there rarely exist links between them, thus making research on the correspondence networks that existed in Norway, the Nordic Countries - and beyond, to Europe and the rest of the world - impossible.

The project Norwegian Correspondences (NorKor) aims to link these individual correspondences not only to each other but to historical correspondences in Europe and beyond by use of the CorrespSearch web service. CorrespSearch is a web service that aggregates specific metadata from editions of correspondences. These data can be searched via the CorrespSearch website or queried via an open API. Norwegian correspondences will thus become visible as part of the greater European network of letters and allow for a macroscopic view on the correspondence networks that existed throughout the centuries.

## Aims

The aim of the NorKor project is to aggregate and provide correspondence metadata from Norwegian editions of correspondences from different projects, institutions and collections in a format that can be ingested by CorrespSearch. The final products are a large set of metadata for Norwegian correspondences under a Creative Commons licence in the CMIF (Correspondence Metadata Interchange Format) standard and an open workflow for (semi-)automatically creating and delivering CMIF-compliant correspondence metadata from future editions prepared by or hosted by the National Library of Norway (and other institutions) to the CorrespSearch web service.
## Participants

### National Library

Ellen Wiger (NB, NSL)

Mette Witting (NB)

Annika Rockenberger (NB)

### Other Norwegian Institutions

Hilde Bøe (Munch Museet)

Philipp Conzett (UiT)

## Implementation
### Step 1: Examination of Materials

The project participants meet IRL at NB for a one-day workshop (aka hackathon) in week 38.

#### Schedule for the workshop in week 38

| Tid | Tema |
|------|------|
| 10.00 – 10.45 | Velkomst og introduksjon til NorKorr-prosjektet |
| 10.45 – 11.00  | Pause |
| 11.30 – 13.00 | Lage oversikt: Brev og korrespondanser i våre samlinger |
| 13.00 – 14.00 | Lunsj (egen regning) |
| 14.30 – 15.45 | Skrive rapport, fordele oppgaver og veien videre |
| 15.45 – 16.00 | Avslutning med kaffe |

### Examination of Materials

We will take a close look at our materials (digital editions of Norwegian correspondences), with regards to:

 - Technical aspects
	 - file format
	 - TEI P5
	 - TEI P4
	 - Other XML
	 - Non-XML
	 - Plain text
	 - Image (scan)
 -  metadata format and coverage
	 - authority data for person & place names, ISO standard for dates
5.  [http://viaf.org/](http://viaf.org/) (NB is member)  
6.  [https://en.wikipedia.org/wiki/Virtual_International_Authority_File](https://en.wikipedia.org/wiki/Virtual_International_Authority_File)
7.  [https://www.geonames.org/](https://www.geonames.org/)
8.  [https://www.iso.org/iso-8601-date-and-time-format.html](https://www.iso.org/iso-8601-date-and-time-format.html)
9.  licences (aka copyright, other limitations)
10.  …
11.  Content
12.  persons (who)
13.  periods
14.  scope (part, whole, selection etc.)
16.  Time and Budget

#### Possible materials to depart from could be
-   NB-kilder
-   Ibsen skrifter
-   Munch tekster
-   Qvigstad brev (started as a project of EDD/UiO [http://www.dokpro.uio.no/qvigstad/](http://www.dokpro.uio.no/qvigstad/), now at UiT/NB)
-   Bokselskap.no

Goal of the workshop is to come up with (1) an overview of digital editions of correspondences that are good candidates for CorrespSearch and (2) identify the work tasks needed to transform (select, format) the metadata to conform to the CorrespSearch standard and (3) assign tasks to the participants.

A brief but precise description of (1) will be done, including a list of authors (see Appendix 1), time periods and content of the correspondences to show the potential for future research on this corpus.
### Step 2: NorKor to CorrespSearch

The participants (who want to) prepare a conference paper and a research article about the workflow (material, data formats, distributed hosting, transformations etc.) for NorKor as an example of preparing large distributed heterogeneous metadata sets for ingestion into CorrespSearch. They explore the potential of such an endeavour and discuss advantages (and challenges) of using decentralized infrastructure and third-party solutions with regards to Norwegian cultural heritage institution’s scrope and policies. The workflow is supposed to serve as a basis for further editions of Norwegian correspondences and should stand as an example of re-use of digital data (and especially metadata) provided by large institutions of cultural heritage and research, especially in the Nordic countries.

The paper is to be given at the TEI2019 International Conference in Graz/Austria in September 2019. Alternatively (or additionally), the paper could be given at one of the DH conferences (DHN2019 in early March, DHd2019 in late March, DH2019 in July) or at conferences for edition philology (NNE2019 in September or AG-Edition in February 2020) or Historical Network Research (HNR2019 tba).

The article should be an edited and polished version of the paper and published soon after delivering the paper (aim: 2020, open access journal, international).



## Step 3: NorKor at NB - The Catalogue Data from the Private Archives and Automatic Correspondence Metadata Extraction from Bokhylla.no

This part of the project is tentative. It shall show the potential of the physical and digital collections of the National Library of Norway, especially in regards to exploiting digital humanities methods in metadata and text mining.

### Private Archives / HANSKE

Via nb.no/nbsok using the search phrase “brev -indulgens” yields 14.824 letters in the holdings of the Private Archives that have been digitized. These should be combed through to select all that are not correspondences or letters. Of the remaining, the letters have to be matched with DSEs in NB-kilder and Bokselskap.no as well as the digitized scholarly editions of letters in bokhylla.no. They can be used as facsimile or alternative presentations where copyright of scholarly editions prevents external access. The metadata of these letters could be extracted and matched with the CIMF standard.

### Hvem-til-hvem

As of XXXX, metadata for correspondences in the holdings of the Private Archive are stored in HANSKE (Manuscript Catalogue, [https://www.nb.no/hanske/](https://www.nb.no/hanske/) ) which in the course of being phased out and replaced by ZZ.. Some of the correspondence metadata in the archive have previously been extracted for searching for correspondence partners and dates. There’s a website providing access to a tool (BETA version) where users can type in person names or years and get a list of results from which they can navigate onwards: [https://www.nb.no/hanske/brev/](https://www.nb.no/hanske/brev/) . The service has been developed by Torstein Tjelta (NB).

Tasks:

-   Take a look at the catalogue data and materials and sketch a workflow for making them compatible with the CMIF-Standard used by CorrespSearch
    
-   Take a look at database behind “Hvem skrev til hvem” and decide if and how to extract data and transform to CMIF-Standard
    
-   How is correspondence metadata stored today and in the future and how can it be easily fed into CorrespSearch, granted this is wanted by NB
    

### Bokhylla.no

The digitisation efforts of the NB provide an enormous amount of textual data. Included in this are Norwegian scholarly editions of correspondences that formerly were printed and now have been digitized in full text (OCR). In order to complete the NorKor metadata set, first a selection of scholarly editions of Norwegian correspondences has to be made. Then, from the text of the editions, correspondence metadata has to be (semi-)automatically extracted, stored, and transformed into a CMIF compliant format to be ingested into CorrespSearch.

This is an endeavour of considerable complexity and size and requires expert knowledge in information retrieval from plain text. At this stage, it should be seen as an experiment in retrieving specific textual data from a large collection of text without too much manual interference. The results of this experiment could be presented as a paper or article in the future and the workflow and code could be published (on GitHub) for re-use on other full-text collections that contain flat encoded texts (aka plain text).

A list of URNs of digitized scholarly editions of correspondences and letters will be created (by AR) and the raw OCR files will be extracted from bokhylla.no by LJ. The corpus will then be divided into materials that are in the public domain and such that are still under copyright protection. For the letters still under copyright protection, no full-text can be shown outside of the NB, however, amount of words, word lists and topic models can be extracted that should allow for ‘distant reading’ of these letters.

### Aims

The aims for the two subprojects in Step 3 are:

-   meaningful re-use of a tool/service developed by NB (HANSKE / Hvem skrev til hvem)
    
-   accessibility of correspondence metadata that hasn’t been edited yet (or won’t ever be)
    
-   targeted retrieval of specific data (correspondence metadata from digitized scholarly editions) from bokhylla.no showing the potential of the digital collection even though it is flat encoded
    
-   large scale show case for “distant reading the network of Norwegian correspondence”
- 
## Bibliography

### Links

[https://www.nb.no/hanske/brev/](https://www.nb.no/hanske/brev/)

[https://www.nb.no/hanske/](https://www.nb.no/hanske/)

[http://historicalnetworkresearch.org/](http://historicalnetworkresearch.org/)

[https://journal.tei-c.org/index.php/journal/index](https://journal.tei-c.org/index.php/journal/index)

[https://correspsearch.net/index.xql?l=en](https://correspsearch.net/index.xql?l=en)

[https://correspsearch.net/index.xql?id=participate](https://correspsearch.net/index.xql?id=participate)

[http://dh2016.adho.org/abstracts/121](http://dh2016.adho.org/abstracts/121)

[http://correspsearch-test.nodegoat.net/viewer.p/4/136/scenario/1/geo/fullscreen](http://correspsearch-test.nodegoat.net/viewer.p/4/136/scenario/1/geo/fullscreen)

[http://www.tei-c.org/activities/sig/correspondence/](http://www.tei-c.org/activities/sig/correspondence/)

[https://github.com/TEI-Correspondence-SIG](https://github.com/TEI-Correspondence-SIG)

[http://www.dokpro.uio.no/](http://www.dokpro.uio.no/)

[http://www.nnedit.org/index.html](http://www.nnedit.org/index.html)

[http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-correspDesc.html](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-correspDesc.html)

[http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html#HD44CD](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html#HD44CD)

### Articles

Dumont, Stefan. “CorrespSearch – Connecting Scholarly Editions of Letters.” Journal of the Text Encoding Initiative, no. 10 (December 7, 2016). [https://doi.org/10.4000/jtei.1742](https://doi.org/10.4000/jtei.1742).

Neuber, Frederike. “CorrespSearch.” Variants. The Journal of the European Society for Textual Scholarship, no. 12–13 (December 31, 2016): 284–85.

Dumont, S. (2016). correspSearch - A Web Service to Connect Diverse Scholarly Editions of Letters. In Digital Humanities 2016: Conference Abstracts. Jagiellonian University & Pedagogical University, Kraków, pp. 175-178.

## Appendix 1

### Brev-utgivelser i NB kilder
pr 1/8-2018

| FRA | TIL | ÅR | PUBLISERT |
|---|---|---|---|
|Collett, Camilla| Bjørnson, Bjørnstjerne| 1867|NB kilder 2:2/2015|
|Collett, Camilla|Collett, Johan Christian|1849|NB kilder 2:4/2018|
|Collett, Camilla|Collett, Peter Jonas|1841-1851|NB kilder 2:4/2018|
|Collett, Camilla|Didriks, Emilie|1841-1842|NB kilder 2:4/2018|
|Collett, Camilla|Herre, Johanne Caroline|1830|NB kilder 2:4/2018|
|Collett, Camilla|Herre, Marie Emilie|1830|NB kilder 2:4/2018|
|Collett, Camilla|Ibsen, Henrik|1872-1889|NB kilder 2:1/2014|
|Collett, Camilla|Ibsen, Susanna|1872-1894|NB kilder 2:1/2014|
|Collett, Camilla|Lie, Jonas|1863-1884|NB kilder 2:3/2016|
|Collett, Camilla|Petersen, Emma|1839|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Amalie Sofie|1839|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Laura Augusta|1846|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Nicolai|1841-1844|NB kilder 2:4/2018|
|Collett, Camilla|Wergeland, Oscar|1844|NB kilder 2:4/2018|

### Planlagte brev-utgivelser i NB kilder

· Korrespondansen mellom Kitty Kielland og Arne Garborg, forventet publisering: 2018

· Brev fra Sumatra (Jacob Iversen m.fl.), forventet publisering: 2018

· Brev fra Just Qvigstad, forventet publisering: 2019

· Korrespondansen mellom Kitty Kielland og Eilif Peterssen, forventet publisering: 2019(?)

### Brevutgivelser NSL/bokselskap.no
pr 1/8-2018

| FRA | TIL | ÅR | PUBLISERT |
|---|---|---|---|
|Bjørnson, Bjørnstjerne|Div. danske mottakere (ca 400 brev)|1854-1874|NSL/bokselskap.no 2010|
|Brandes, Georg|Thoresen, Magdalene|1865-1899|NSL/bokselskap.no 2015|
|Ibsen, Henrik|Bjørnson, Bjørnstjerne|1864-1898|HIS/bokselskap.no 2014|
|Ibsen, Henrik|Collett, Camilla|1877-1893|HIS/bokselskap.no 2013|
|Ibsen, Henrik|Lie, Jonas|1879-1900|HIS/bokselskap.no 2012|
|Kielland, Alexander L.|Div. mottakere (ca 1800 brev)|1869-1906|NSL/bokselskap.no 2010|
|Obstfelder, Sigbjørn|Div. mottakere (ca 200 brev)|1884-1900|NSL/bokselskap.no 2016|
|Skram, Amalie|Skram, Erik|1882-1902|NSL/bokselskap.no 2016|
|Skram, Erik|Skram, Amalie|1882-1902|NSL/bokselskap.no 2016|
|Thoresen, Magdalene|Brandes, Georg|1865-1899|NSL/bokselskap.no 2015|
|Wergeland, Henrik|Bekkevold, Amalie|1838-1845|NSL/bokselskap.no 2011|

## Appendix 2

### Zotero group library

for scholarly editions of letters and correspondences in the hold of NB

### URNs

of scholarly editions of letters and correspondences in Bokhylla.no

Creating the corpus via bokhylla.no

Title “brev”, medium “books”, language “Norwegian (bokmål)” yields 718 hits; these were sorted chronologically, starting with the oldest. After manual inspection of each item, only the ones that match the following criteria are saved into a list of results “NorKorr-nb”. A search on 2018-08-13 yielded 173 books out of 718 hits. The list needs to be checked against the criteria below again and exported into Zotero (this is not possible via nb.no yet; it would have to be done manually for each item).

### Selection Criteria

-   has to be letters as part of an actual correspondence (no fictional letters, no religious sermons in the form of letters, no ‘letters to the editor’, no Briefromane)
    
-   has to be a scholarly edition - although, in the broadest, most inclusive sense

Q: What to do with so called “utvandrerbrev”? There’s a couple of editions with letters from/to Norwegian emigrants (to the US and other places); could be of interest? Perhaps as a subcorpus; I assume that getting authority data for the senders/receivers is difficult in this case.

Q: Should the corpus be limited to “important” people? Pragmatically speaking, limiting the correspondences to “important” people like writers, politicians, cultural and academic elite, nobility could be the easiest way to create a corpus where authority data is available. Letters and correspondences of other people is interesting from a different perspective (local history, cultural history, genealogy etc.) but presumably harder to back with authority data and larger correspondences (aka ‘letters of a lifetime’).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI5NzExMzA5LC04MDY3Mzg3MDksLTIwNT
k4NzI3MDksLTE0NTIxMzc5NTUsLTEyMTk0NDU2MDcsLTI4MjY1
ODQ5M119
-->