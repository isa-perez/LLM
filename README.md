This is a copy of a kaggle notebook used for a submission into the Gemini 1.5 pro Long Context Competition.

The code uses a dataset of PDFs sourced from ArXiv on Quantum Gravity Theory.
PyPDF2 then parses the text and it is transformed into a combined_text.txt file.
The code uses many-shot prompts to summarize, validate, synthesize and then add to the context cache.
The dataset completely is 1.3 million tokens processed into 100,000 token chunks. 

The code has a global token cap of 2 million if used with Gemini 1.5 Pro, but originally intended for Gemini 1.5 Flash Version 2 which only respects around 1 million tokens.

The Goal: Synthesize a large dataset of Quantum Gravity Theory research into a new scientifically rigorous theory. 
Hopefully helping take a step in our understanding Quantum Gravity. 
