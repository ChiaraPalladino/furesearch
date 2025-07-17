## Annotation of the Anonymous Periplus of the Erythraean Sea 

Author: Olivia Bishop, Furman University '27
Email: bishol3@furman.edu
 
### Introduction

The Periplus of the Erythraean Sea is a navigational text describing a sailing route starting on the west side of the sea in Egypt and ending in India around the modern day island of Sri Lanka, written by an anonymous Greek author. The periplus also explores the African coast down to modern day Tanzania and the east coast of the Red Sea, as well as discussing some of the inland areas of India and the surrounding areas. The text was written sometime between the first and third century AD.

The edition used for the _Periplus of the Erythraean Sea_ is the most recent edition by Stefano Belfiore for the _New Jacoby_ (Fr. 2036), which is based substantially on the established critical text by Frisk (1927), with some updates. The digital text is the one published in the online edition of the _New Jacoby_, cleaned, formatted, and inspected for mistakes. All footnotes and apparatus criticus were removed. Additionally, the text was processed for Named Entity Recognition using the UGARIT NER model for Ancient Greek (https://huggingface.co/UGARIT/grc-ner-bert). Recogito, an online platform for geoannotating texts (https://recogito.pelagios.org/), was used to inspect and disambiguate automatic annotations generated through NER. 

### Annotating the Text

The first part of my research consisted of reading through the translation of the text. I used the Casson (2012) translation and commentary for the majority of this work, though I also used the Shipley translation and commentary from Geographers of the Ancient Greek World Selected Texts in Translation, published by the Cambridge University Press in 2024. 

While reading through the text, I attemped to geolocate each toponym mentioned in the text, making sure to also check for places that were not recognized initually. I used the Pleiades gazzeteer (http://pleiades.stoa.org/) for most occurrences. Some places were easy to find in the gazzeteer, by simply searching their name as it appeared in the Greek text or the English translation, while others were much more challenging or ambiguous. Places that we were not able to identify, or that challenged our idea of geographic location at a fundamental level, were flagged as unidentifiable. 

Secondly, I went back through the text and used tags to further disambiguate the types of entities. The "collective" tag was used for the mentions of people groups such as "Indians" or "Greeks". A "derivative" subtag was used when the name of a place was used as an adjective expressing provenance or another relation to a certain place, such as "Indian (cinnabar)".

After this, I annotated all of the specific people and events that were mentioned in the text. Using Wikidata, I disambiguated and linked people such as Alexander the Great and Menendar I, an Indo-Greek king. The events in the text were mostly instances of times, namely the Greek and Egyptian names of months, where the author was describing the best times to set sail from to certain places.

Next, I was tasked with identifying the non-toponymic spatial entities present in the text, using a "geoname" tag. Geonames include english words such as 'river', 'mountain', 'sea', 'port', 'island', etc. For this part of the project, I used the Perseus Digital Library's Scaife Viewer (https://scaife.perseus.org/), which includes the Greek text of the Periplus and allowed me to see the translations for every word. I used Scaife throughout the entire project, but in this stage it was the most useful.

For the final part of my research, I annotated and tagged mentions of orientation and distance in the text. There were two types of orientation mentioned in the periplus, one being "relative" which included phrases such as "to the left" or "to the right" and needed further context to understand (to the right of what?). The other was "absolute" which included phrases such as "to the west" or "to the east". All of these instances were identified and tagged with the 'orientation' tag and a further 'relative' or 'absolute' tag. Examples of distance in the text were phrases such as "three thousand stades", stades being a distance measurement that was used at the time. These were tagged with a 'distance' tag.

### The Numbers

Throughout my eight weeks of research, I annotated 429 places, 19 people, 15 events, and 458 "uncategorized" entities, according to Recogito's analytics, which would be the geoname, orientation, and distance tags. In total, I annotated 917 entities in the text, and made 638 tags (some entities such as regular place names, specific people, and events did not require tags but only annotations).

### My Thoughts

I really enjoyed my time doing summer research with the Furman Classics department. I find the most valuable thing that I learned was how to annotate a text and use digital tools such as Recogito. I was introduced to many websites and programs that I didn't even know existed like Pleiades and Wikidata. I think the archiving of knowledge is deeply important, and discovering these online platforms that are dedicated to just that was very interesting to see.

During my research, I was unable to identify some places and people because they are very obscure, some only ever being mentioned in this specific text. Some places I was able to find a match in Pleiades, but the gazzeteer has them as unlocated. This was one thing that was frustrating to me. I wish that I had all the answers and could have a clean dataset with no places highlighted in yellow, flagged because I wasn't able to identify them. But, as mentioned, the sources I used that are dedicated to archiving these places and people give me hope that more unknown places and people from history can be identified, and I think that it is incredible that I was able to contribute to this goal in even just a small way. I am glad that there are researchers and academics that care about even the most obscure parts of history, and I have found through this project that I do as well.

I am very grateful to Dr. Palladino and the Furman Classics department for giving me the opportunity to participate in this research and I hope that I am able to conduct similar research again in the future.

