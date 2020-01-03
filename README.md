# AristarchusTreebank-Lit

2020.01.03
This is a very preliminary version of a repository of treebanks of Ancient Greek literary authors.
The treebank format is based on the Perseus treebank schema (https://perseusdl.github.io/treebank_data/), but some attributes have been added, and the parsing is different in several, important ways. 

The main differences are as follows:

(1) This is a "stratified" dependency bank, i.e., you can reconstruct the immediate constituents (using @strat)<p>
(2) Punctuation is annotated as an attribute of the word the punctuation mark is attached to (@punct)<p>
(3) The PP is considered an exocentric phrase (as Bloomfield did). So in a PP, the substantive is the head of the phrase, and the preposition depends on its substantive. Following the same logic, a verb is the head of a subordinate VP and any relative or conjunction conjunction depends on it. Again, <p>
(4) The "contid" attribute is used to tag correference. Wait a couple of weeks to see how it works.<p>
(5) The value of the "lemmaprev" attribute is the word (usually a verb) with the preverb(s) differentiated from the lemma with a "-".<p>
(6) The "tSint" attribute is where you find the specific kind of phrase (PP, SP, AdvP, etc.).<p>

CAVEATS<p>
  
(1) Don't worry about the "codari" attribute: it is an internal code of the syntactic function that will disappear in the definitive version<p>
(2) The refereces of elliptical elements are not marked yet.<p>

This repository will hold treebanks for (a) literary texts as well as (b) literary and (c) subliterary papyri
The repertoire of attributes for the papyri (b and c sections of the final repositoire) is longer. Quite longer.


