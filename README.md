# Text_Summerization

## Step-by-Step Process
### Installed Required Libraries
Installed the transformers library from Hugging Face to access pretrained NLP models like BART.

### Imported Essential Python Modules
Imported pipeline, AutoTokenizer, and AutoModelForSeq2SeqLM from transformers for summarization, and re for basic keyword extraction using regex.

### Loaded Pretrained Summarization Model
Used the "facebook/bart-large-cnn" model to initialize a Hugging Face summarization pipeline. This step included loading the tokenizer and model.

### Defined a Summarization Function
Created a function to generate a concise summary from input text using the loaded BART model, setting max and min length constraints.

### Implemented Lightweight Keyword Extraction
Designed a basic keyword extractor that:

Converts text to lowercase

Removes stopwords manually (without NLTK)

Uses regex to extract meaningful words

Counts word frequency

Returns the top frequent words as keywords

### Provided Sample Input Text
Pasted a paragraph about the Apollo space program to test the summarization and keyword extraction functions.

### Executed the Summarization and Keyword Extraction
Ran the summarization and keyword extraction functions on the input text and stored the results.

### Displayed the Final Output
Printed the original text, its generated summary, and the top extracted keywords.
Call the summarization and keyword extraction functions on the input text.

Step 8: Display Results
Print the: Original text, Summarized version, Top keywords
