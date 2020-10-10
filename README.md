# Dictionaries
This is a collection of public dictionaries designed for free use in any context, but certainly spell checkers, translators, etc

I often need dictionaries for various projects.
One common need is a spelling dictionary. I use this for class assignments as well as for programs that check for words.
Password programs want to avoid common words. Editors want to make sure these words are spelled right.

Needed:
  simple translation dictionaries without lots of formatting and complexity.
  simple chinese word list for recognizing legal words in texts
  English words only, not numbers and other tokens (just subset the englishtokens.txt)
  
  Code to automatically read and strip jmdict and ecdict to create simple entries without pronunciation
It is also nice to have a translation dictionary, for example Chinese-English. This is not going to translate a document
well, but can convert critical terms. More important, we need a dictionary with legal sequences of Chinese words for purposes of data compression.
The most desired dictionaries for CJK would be simple format: just word, some delimiter like tab, and corresponding English word. I have not found any dictionaries like that.


## List of references
                   
contributor         file             type          size (words)         original author     source
Pieter-Janssens                                    84k                                       http://www.gwicks.net/textlists/engmix.zip
Pieter-Janssens                                    180k                                     http://www.gwicks.net/textlists/nederlands3.zip
Pieter-Janssens                                    208k                                     http://www.gwicks.net/textlists/francais.zip
Pieter-Janssens                                    82k                                      http://www.gwicks.net/textlists/ukenglish.zip
Dov Kruger                                         497k                                     https://github.com/dwyl/english-words
Dov Kruger          german.txt       wordlist      1.9M                 Marvin J Wendt      https://gist.github.com/MarvinJWendt/2f4f4154b8ae218600eb091a5706b5f4
Dov Kruger          hebrew.txt       wordlist      23k                  Yoav                https://yeda.cs.technion.ac.il/resources_lexicons_stopwords.html
Dov Kruger          names/germannames.txt list                                              edited from Wikipedia, should  be split into names and surnames
Dov Kruger          names/                                                                  https://github.com/davidsbatista/lexicons
Dov Kruger          jp.dic                         190k                                     http://www.edrdg.org/jmdict/edict_doc.html#IREF01
