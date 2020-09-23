# Question Generator 



## Working

- The algorithm takes a paragraph as input (suggested to take content from curriculum textbooks like NCERT Books) and generates fill-up type multiple choice questions.
- The algorithm uses Python Keyword Extractor, to determine the most important keywords out of the input text, finds the sentences they are used in and replaces them with a blank to generate the question. 
- Now that we have the question, the next step is to generate distractors for the correct answer to provide the student with choices. This is done using the wordnet and conceptnet.
- The generated questions are then displayed back to the admin so that he/she can select the most appropriate ones.
