# French FastContext cues generation

Created in 2019 for the semi-automation of the generation of the French lexical cues used by French Fastcontext [1].

#### Description
The repository contains the following Jupyter Notebooks:  



**1_Initiator.ipynb**   

This notebook takes the `./excels/0_Phase3_LexicalCluesENFR.xlsx` as input which is an English version of FastContext with seed (google translated) French counterparts. The outcome of this notebook is the `./excels/1_Phase3_TranslationTable.xlsx` which is automatic enriched information such as POS, the number of occurence of French rules, the words candidate for synonyms, etc.  

**2_SynonymExtraction.ipynb**  

This notebook takes the `./excels/1_Phase3_TranslationTable.xlsx` as input which is an enriched French version of FastContext rules. The outcome of this notebook is the `./excels/2_Phase3_Word_Sense_Extraction.xlsx` which is the synomym extraction from differnet sources such as "JDM_Sense","JDM","WordNet","Cnrtl","Synonymo","Cisco" and "DicSyn_Sense".  

**3.1_SynonymVoting.ipynb**  

**3.2_SynonymVoting.ipynb**  

**4_SynonymTableMerger.ipynb**  

**5.1_CFG Renaming.ipynb**  

**5_CFG_Maker.ipynb**  

**6_CFG2Rule.ipynb**  

**7_ResultAnalyser.ipynb**  



./excels/0_Phase3_LexicalCluesENFR.xlsx
./excels/0_Phase3_LexicalCluesENFR_Grouping_CJ.xlsx
./excels/1_Phase3_TranslationTable.xlsx
./excels/2_Phase3_Test.xlsx
./excels/2_Phase3_Word_Sense_Extraction.xlsx
./excels/2_Phase3_Word_Sense_Voting_CJ-15-07-19.xlsx
./excels/3_Phase3_Word_Sense_Voting.xlsx
./excels/3_Phase3_Word_Sense_Voting_New_Format.xlsx
./excels/3_Phase3_Word_Sense_Voting_with_Occurances.xlsx
./excels/3_Phase3_Word_Sense_Voting_with_Occurances_curated_CJ2.xlsx
./excels/3_Phase3_Word_Sense_Voting_with_Occurances_curated_CJ2_Cleaned.xlsx
./excels/4_Phase3_TranslationTable.xlsx



#### Authors 
Mehdi Mirzapour (@mehdi-mirzapour) with supervision of Clement Jonquet (@jonquet)

#### Copyright
LIRMM


[1] [https://github.com/practikpharma/FrenchConText]()
