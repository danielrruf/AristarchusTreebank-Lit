# AristarchusTreebank-Lit

2020.01.03
This is a very preliminary version of a repository of treebanks of Ancient Greek literary authors
The treebank format is based on Perseus' (https://perseusdl.github.io/treebank_data/). 

The main differences are as follows:

(1) This is a "stratified" dependency bank, i.e., you can reconstruct the immediate constituents (using @strat)<p>
(2) Punctuation is annotated as a attribute of the word the punctuation mark is attached to (@punct)<p>
(3) The PP is considered a exocentric phrase (as Bloomfield did). S,, pte preposition depends on its substantive (the substantive is the heac of the SP. In the same way, a verb is the head of a VP and the relative and the conjunction depends on it.<p>
(4) The contid attribute is used to mark correference. Wait a couple of weeks to see hoh it works.<p>
(5) The value of the lemmaprev attribute is the word (usually a verb) with the preverb(s) differentiated from the lemma with a "-".<p>
(6) tSint attribute indicates the kind of phrase (PP, SP, AdvP, etc.) of the phrase.<p>

CAVEATS<p>
  
(1) Don't worry about the codari attribute: is an internal code of the syntactic function that will disappear in the definitive version<p>
(2) The refereces of elliptical elements are not marked yet.<p>

This repository will hold treebanks for literary texts as welll as literary and subliterary papyri
The repertoire of attributes for the papyri is longer. Quite longer.

