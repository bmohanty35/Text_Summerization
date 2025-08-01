# Text_Summerization

# Step-by-Step Process for Text Summarization & Keyword Extraction Project
Step 1: Install Required Libraries
Install the Hugging Face transformers library (if not already installed):

pip install transformers

Step 2: Import Necessary Libraries
Import modules for: Summarization (transformers), Keyword extraction (re for regex)

Step 3: Load the Pretrained Model
Load the BART (facebook/bart-large-cnn) model and tokenizer from Hugging Face.
Use them to create a summarization pipeline.

Step 4: Define the Summarization Function
Create a function that: Takes input text, Runs it through the model, Returns the summarized version

Step 5: Define the Keyword Extraction Function
Use a simple function that: Lowercases the text, Removes common stopwords, Finds word frequency, Returns top N frequent words as keywords

Step 6: Input Your Text
Provide the paragraph or content you want to analyze.

# Step 7: Run the Pipeline
Call the summarization and keyword extraction functions on the input text.

# Step 8: Display Results
Print the: Original text, Summarized version, Top keywords
