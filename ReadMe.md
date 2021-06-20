Start StanfordCoreNLP in your locale on port 9000.
Run CorefResolution.py to get the coreference resolutions of Stories located in /Stories folder.
This will create a Corefs folder and populate it with Stories with their coreferences resolved to proper nouns by Stanford CoreNLP.
Then Run CharacterSentiments.py with argument 1 on the console to extract characters and their sentiments from original of the Stories, run it with argument 2 to extract the characters and their sentiments from Corefe folder.
The characters of stories will be located in Characters Folder and their sentiments in Sentiments Folder.