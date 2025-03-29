# Data Essay
The _Old English Martyrology_ is an Anglo-Saxon encyclopaedic compilation of approximately 250 Christian saint biographies, or hagiographies. Each entry corresponds to a different day of the year and offers brief vignettes into the life and death of its corresponding saint. The text was composed somewhere between 800 and 900 CE, though the saints covered span from late antiquity to the early medieval. While written in Old English, I am using the modern English translation by Christine Rauer for my work. The author is unknown but presumed male and closely follows the conventions deployed by his variant sources. I therefore chose this work as means through which I could investigate tradition and convention in hagiographic terminology.


There are 207 total martyrdom entries in the _Martyrology_. Of these, 144 are male saints, 35 are female, and 28 involve more than one saint of different sexes. My goal was to compare the terminology used to describe male versus female martyrs using the terms function in Voyant to discern the gendered conventions imbued in accounts of martyrdoms. I created three folders: __Male Martyrs__, __Female Martyrs__, and __Miscellaneous__ into which I sorted plaintext files of each entry. I then uploaded the __Male Martyrs__ and __Female Martyrs__ corpora separately into Voyant. Using the “terms” function of the __Female Martyrs__ corpus, I added the __Male Martyrs__ corpus ID into the comparison setting. I then added a column that would display the difference in the relative frequencies of given terms between the two corpora. Relative frequency denotes the raw count of each term’s appearance divided by the total number of terms, per a normalized count of one million terms. Terms with the highest comparative value feature most prominently in the original corpus __(Female Martyrs)__ but not in the comparison corpus __(Male Martyrs)__, while terms with the lowest comparative value are reversed.


### Difference in relative frequency between terms used in accounts of male martyrdoms versus female martyrdoms
<iframe style='width: 600px; height: 600px;' src='https://voyant-tools.org/tool/CorpusTerms/?view=CorpusTerms&stopList=keywords-e5265467aae4b80d72e5ff3bc69f11ba&termColors=terms&comparisonCorpus=f6137eeda3a4a64c8a5218d8cb8b5f30&corpus=31d665a14d4a66a1aa76c4dcd3f88130'></iframe>


Each entry in the _Martyrology_ begins with a formulaic starting sentence: “On the [x] __day__ of the [x] __month__ is the [feast/death/commemoration/etc.] of the [person] __called__ __St__ [Name]...” I therefore decided to include _day_, _month_, _called_, and _St_ in my stopwords list, as these were terms that were guaranteed to appear in each entry. The term with the highest comparative value, at 0.00738, became _virgin_, along with other terms like _holy_, _beautiful_, _house_, and _birth_; these terms feature prominently in female but rarely male hagiographies. Interestingly, words like _God_ and _Christ_ as well as the verb _said_ have high comparative values, pointing to an anecdotal format of hagiography in which the female martyrs themselves relay their faith. The term with the lowest comparative value, at -0.00315, is _bishop_, along with other terms like _pope_, _church_, and _country_. The words _martyr_ and _miracle_, which would seemingly be integral to a martyrology, feature primarily in male entries. The author acknowledges female martyrdom but not their role as martyrs, additionally omitting any miracles occurring at their burial sites.


## Analysis
While it would be difficult to make claims regarding the extent the author venerates saints based on their sex, comparing relative frequencies illuminates linguistic convention in hagiographic construction. Women were more restricted in their routes to sanctity due to limited access to the ecclesiastical hierarchy, religious space, and the cultural capital required for veneration. This rendered the female body an integral avenue to sanctity, magnifying attention to virginity. Alternatively, the male martyrs of the _Martyrology_ are most denoted by their ecclesiastical positions and actions in the public domain. The terms associated with female martyrs in the _Martyrology_ reflect a different, more enclosed sphere of sanctity. While not less revered, the paths to female martyrdom ran in continuum with general gendered thought of late antiquity and the Early Middle Ages.


## Bibliography
[Rauer, Christine. “Female Hagiography in the Old English Martyrology.” In Writing Women Saints in Anglo-Saxon England, edited by Paul E. Szarmach, 13–29. University of Toronto Press, 2013.](https://www.jstor.org/stable/10.3138/j.ctt5hjvgx.5.)


[———, ed. “Text and Translation.” In The Old English Martyrology, 10:34–227. Edition, Translation and Commentary. Boydell & Brewer, 2013.](https://www.jstor.org/stable/10.7722/j.ctt31njnj.7.)


[Stodnick, Jacqueline. “Bodies of Land: The Place of Gender in the Old English Martyrology.” In Writing Women Saints in Anglo-Saxon England, edited by Paul E. Szarmach, 30–52. University of Toronto Press, 2013.](https://www.jstor.org/stable/10.3138/j.ctt5hjvgx.6.)
