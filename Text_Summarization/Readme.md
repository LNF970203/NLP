### Notebooks and python scripts regarding the Text_summarizations
- Hugging Face Models are used to summarize the texts.
- Performance of the summarization models were measured using rouge score comparing system summary and a human summary
- Main components to consider........
                  Time
                  Accuracy
                  Number of tokens - Most of the models are having maximum number of tokens as 1024 or 512. After exceedng this amount list index out error will be thrown
- It is overcome by using nltk sentence tokenization to measure the number of tokens
