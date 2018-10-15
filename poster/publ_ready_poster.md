# NorKorr – Norwegian Correspondences and Linked Open Data
## About the Project

The National Library of Norway has a substantial amount of private historical correspondences in its holdings,<sup>[1](#NBnrLetters)</sup> many of which are scholarly edited and published, either in printed editions or in digital form. In addition, other Norwegian cultural heritage institutions, like the Munch Museum,<sup>[2](#MMnrLetters)</sup> but also the university libraries of the Arctic University of Norway<sup>[3](#UiTnrLetters)</sup>  and the University of Bergen<sup>[4](#UiBnrLetters)</sup>  and the Gunnerus Library at the Norwegian University of Science and Technology,<sup>[5](#NTNUnrLetters)</sup>  hold significant collections of letters and are preparing digital editions of letters and correspondences of key figures of Norwegian public and academic life. Yet, all these correspondence projects lead a solitary existence–hidden either in editions of single authors or as digitized collections or individual pieces on institutional servers.

As a dialogical genre by nature, the full potential of letters and other correspondance material lies in the connection of the individuals writing and receiving letters, postcards, and telegrams–at a specific time and from and to a specific place. But because the collections of letters and individual pieces of a correspondence are historically distributed wide and far in regards to geography and institution, there rarely exist links between them. Thus research on correspondence networks that existed in Norway, the Nordic Countries–and beyond, to Europe and the rest of the world–as well as research on the letter as the main means of written communication for centuries is almost impossible.

The project **Norwegian Correspondences** (NorKorr, from Norwegian "Norske korrespondanser") aims to link these individual letters and similar materials not only to each other but to correspondences in entire Norway, Europe and beyond by use of the [CorrespSearch infrastructure](https://correspsearch.net/index.xql). CorrespSearch is both an infrastructure for connecting correspondences accross editions and collections and a web service that aggregates specific correspondence metadata from digital and printed scholarly editions.<sup>[6](#Dumont1)</sup> These data can be easily searched via the CorrespSearch web interface or queried via their open API. By integrating Norwegian correspondences in the corpus of letters that already exists on CorrespSearch, they will become for the first time visible as part of a greater international network of letters and allow for a macroscopic view on the correspondence networks that existed throughout the centuries.

## Aims

The aim of the NorKorr project is to aggregate and provide correspondence metadata from Norwegian editions of correspondences from different projects, institutions and collections in a format that can be ingested by CorrespSearch. The final product will be a large set of metadata for Norwegian correspondences under a Creative Commons license in the CMIF ([Correspondence Metadata Interchange Format](https://github.com/TEI-Correspondence-SIG/CMIF)) standard and an open workflow for (semi-)automatically creating and delivering CMIF-compliant correspondence metadata from future editions prepared by or hosted by the National Library of Norway (and other institutions) to the CorrespSearch web service.

In addition to aggregating the metadata from digital and printed (scholarly) editions, NorKorr aims to incorporate all digitized correspondence material. This means that all manuscript and private archive collections throughout Norway which have undergone or will undergo digitization and assign indivual URNs to each letter together with a minimum of metadata (often derived from manuscript catalogues) will be interconnected.<sup>[7](#Rettinghaus)</sup> At the present, CorrespSearch doesn't incorporate material that is not (scholarly) edited in either digital or printed format. NorKorr will, however, collect all correspondence metadata regardless and map it on the CMIF standard using the URNs as persistant identifiers for individual letters. It will thus be possible to use the existing infrastructure that CorrespSearch provides to connect material in almost all forms: scholarly edited, printed or digital, and digitized.

We see this expansion to be an important step towards making digital collections accessible and searchable cross-institutionally, a feature that is usually prevented by mutually incommensurable 'in-house' solutions regarding encoding standards, cataloguing methods and metadata standards.  In addition, because it is commonly only a small and often strongly canonised selection of authors, musicians, artists and academics whose letters are deemed worthy of a scholarly edition, the picture we have of Norwegian correspondence networks and Norwegian cultural contacts with the other Nordic countries and the rest of the world is strongly biased and non-representative. NorKorr is able to include correspondence material regardless of language, time period, social class, gender, and nationality.

## Status Quo

### Scope

We propose to present a collaborative poster at DHN2019 where we focus on five cases of correspondence collections at Norwegian cultural heritage institutions. For the cases, we decided to be as diverse and multifaceted as possible. We will describe the collections of letters of each contributing institution and the specific challenges each of these collections poses in regard to content (including language, occupation and background of authors, period) and technology (completeness of metadata and metadata format, IIIF-compatibility of digital material, editorial status, accessiblity, rights management) and the workflows we have established for mapping the correspondence metadata onto the CMIF standard for ingestion into CorrespSearch.

### Case 1 – Letters to and from Norwegian Writer and Feminist Camilla Collett (1841–1859)

### Case 2 –

### Case 3 –

### Case 4 –

### Case 5 –

### Project Website

The project NorKorr is collectively developed on GitHub _in plain view_. It is open for collaborators from all Norwegian cultural heritage institions (ALM sector), the universities and other research institutions as well as other organisations who hold collections of correspondence material. We document our code and share it under the Creative Commons Attribution 4.0 License. We build on the work shared by the CorrespSearch team, the TEI Correspondence SIG and individual researchers and developers on GitHub.

## Footnotes

<a name="NBnrLetters">1</a>: A query of the manuscript catalogue "HANSKE" which is in use at the National Library of Norway, retrieves 195.653 registered letters. Among them are letters to and from Henrik Ibsen (1828–1906), Fridtjof Nansen (1861–1930), Camilla Collett (1813–1895) but also letters by Norwegian emigrants to the United States, Mexico and Canada.

<a name="MMnrLetters">2</a>: The Munch Museum holds 8802 letter to and from artist Edvard Munch (1863–1944).

<a name="UiTnrLetters">3</a>: Including collections of Sami letters and material in the Sami and Kven language.

<a name="UiBnrLetters">4</a>:

<a name="NTNUnrLetters">5</a>: Including the historical correspondences of associates of the Royal Norwegian Society of Sciences and Letters (1760–1860) and the private collection of Thorvald Boeck (1835–1901).

<a name="Dumont1">6</a>: Dumont, Stefan. “CorrespSearch – Connecting Scholarly Editions of Letters.” Journal of the Text Encoding Initiative, no. 10 (December 7, 2016). DOI: [https://doi.org/10.4000/jtei.1742](https://doi.org/10.4000/jtei.1742).

<a name="Rettinghaus">7</a>: A comparable idea is put forward in Rettinghaus, K. (2018). Semantic minimal retrospective digitization of edited correspondence. Poster. TEI2018 International Conference, Tokyo, 9–13 September 2018. DOI: [https://doi.org/10.5281/zenodo.1410796](https://doi.org/10.5281/zenodo.1410796). 
