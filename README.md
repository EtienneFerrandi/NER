# NER
 NER for medieval encyclopedia for the SourcEncyMe project at IRHT (Paris). 

The model has been trained on the basis of the _Lewis & Short_ dictionnary of which only proper names have been maintained (file "data/ls_indexData_capital.json") and the encyclopedia of Marcus d'Orvieto. The proper nouns of the dictionnary have been declined thanks to a script of Dr. WJB Mattingly (https://github.com/wjbmattingly/latin_ner_lesson) in order to recognize the declined forms of the proper nouns in the texts.
 
The dictionnary of the recognized entities througout the encyclopedia of Marcus d'Orvieto is the file "train/training_set.json". Each entity and their position in the corpus are listed. A list of the entities without their position and only once referenced is the file "temp/ml_results.txt".

Trained on a test text, the results of the NER model have been listed in the file "temp/results.txt".
