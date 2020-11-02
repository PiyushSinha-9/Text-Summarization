## Text Summarization

####  TWO TYPES OF SUMMARIZATION

- Abstractive Summarization: <br />
Abstractive methods select words based on semantic understanding, even those words did not appear in the source documents. It aims at producing important material in a new way. They interpret and examine the text using advanced natural language techniques in order to generate a new shorter text that conveys the most critical information from the original text. <br /> <br />

 Input document → understand context → semantics → create own summary. <br />

- Extractive Summarization: <br />
Extractive methods attempt to summarize articles by selecting a subset of words that retain the most important points. <br />
This approach weights the important part of sentences and uses the same to form the summary. Different algorithm and techniques are used to define weights for the sentences and further rank them based on importance and similarity among each other.  <br /> <br />

Input document → sentences similarity → weight sentences → select sentences with higher rank. <br />

### I am using generate extractive summarization.