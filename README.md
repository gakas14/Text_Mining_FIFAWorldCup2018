### Natural Language Processing ###

#Text_Mining_FIFAWorldCup2018



The 2018 FIFA World Cup was the 21st FIFA World Cup which is an international football tournament contested by the men&#39;s national teams of the member associations of FIFA conducted once every four years. It took place in Russia from 14 June 2018 to 15 July 2018 and was the first World Cup to be held in Eastern Europe.

Objective: Practice text processing using FIFAWorldCup2018.txt file.

Actions to Perform:
1. Write separate Python functions that accept a string, a number ‘n,’ and return the following:

N most frequent nouns (Take function name as “GetNMostFrequentNouns”)
N most frequent verbs (Take function name as “GetNMostFrequentVerbs”)
N most frequent delimiters (Take function name as “GetNMostFrequentDelimiters”)
N most frequent prepositions (Take function name as “GetNMostFrequentPrepositions”)
Run all the functions on the file “FIFAWorldCup2018.txt” and print the results.

2. Write a Python function that accepts a string and prints the first sentence in the string along with its syntax tree.
Take function name as “PrintSyntaxTree"
Run this function on the file “FIFAWorldCup2018.txt.

3. Write a Python function that accepts and returns a string using regular expressions:
Text from the string after removing all the punctuation (Take function name as “TextAfterRemovingPunctuations”)
Text from the string after removing all the numbers/digits (Take function name as “TextAfterRemovingDigits”)
All the words that begin with a capital letter (Take function name as “AllCapitalizedWordsFromText”)
All the emails from the string (Take function name as “AllEmailsFromText”)
Run all the above functions on the file “FIFAWorldCup2018.txt” and print the results.

4. Write Python functions that accept a string as an input and return the following chunks:
Phrases that have proper nouns followed by verbs (Take function name as “ChunkingVer1”)

Verb phrases that have verbs followed by adjectives (Take function name as“ChunkingVer2”)
Noun phrases that have determiners followed by nouns (Take function name as“ChunkingVer3”)
Verb phrases that have verbs followed by adverbs (Take function name as “ChunkingVer4”)
Phrases that have delimiter, adjectives, and nouns in the respective order. (Take function name as “ChunkingVer5”)
Noun phrases that have nouns and adjectives, terminated with nouns. (Take function name as “ChunkingVer6”)
Run all the functions for the first sentence in the file “FIFAWorldCup2018.txt” and print the results.

5. Make a content-free grammar having the following rules:
Noun phrases are followed by verb phrases
Verb phrase can have:

Verb and noun phrases
Verb, noun phrases, and preposition phrases
Noun phrases can have:

Delimiters followed by nouns
Preposition phrase has a preposition followed by a noun phrase
The delimiters, verbs, prepositions, and nouns for the grammar should be the 2 most
frequent words of each type from “FIFAWorldCup2018.txt”. Generate the CFG for
“FIFAWorldCup2018.txt” file and save them in a file named “CFG.txt”
