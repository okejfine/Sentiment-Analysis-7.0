# Hw07_ling360


LING 360
Programming for Text Processing and Analysis
Assignment 7

Instructions:
In the CMS there is an untagged corpus named "AWE_untagd.zip". Write a Python program that uses the default part-of-speech tagger in the NLTK library (see relevant chapter here (Links to an external site.)) or TreeTagger to tag the AWE corpus. Your program should identify all noun + noun sequences (e.g., cell distribution, government policy) where both nouns are common nouns (not proper nouns). Make sure to include both singular and plural nouns. For each of the six registers in the AWE corpus, generate a frequency list of all common noun + common noun bigrams, ordered in descending order, that is, with the most frequent bigram first. Your program should then write 6 .csv files, one for each of the registers, with two columns: bigram, freq. When imported into spreadsheet software, each .csv file should look something like the following:

bigram freq
cell distribution 32
government policy 21
etc. etc.
With a small sample of the corpus (a file or two), check precision and recall of your program. In a .docx file, write a report in which you interpret and compare the frequency of noun + noun pairs across the six registers. Also, report the precision and recall measurements in the sample of the corpus you chose.

Turn into the CMS a .zip file with your Python program as a .py file, your report in prose in a .docx file, and the 6 .csv files with the frequency lists.

Tips:

Here's a list of the six registers: ['JA_BI', 'JA_HI', 'PS_BI', 'PS_HI', 'TB_BI', 'TB_HI']
