# WikiTopics

This contains all the code involved in downloading and processing the data from Wikipedia. The notebooks are:

- **Notebook 1:** Downloads the lastest (November 20th, 2024) database dump from Wikipedia in order to be processed.
- **Notebook 2:** Converts the data from the Wikipedia database dump format into a columnar format that can be more easily loaded. Cleans the data of invalid or spam articles and extracts the date of each article.
- **Notebook 3:** Extracts the date of each article and download a plain text (as opposed to WikiText, the format Wikipedia uses to represent articles) version of the article from Wikipedial.
- **Notebook 4:** Use BERTopic to run a topic modeling algorithm (using BERT) on the articles, to extract the most common topics from each article. Exports the resulting topics for each article to JSON format.
- **Website ([wikitopics.github.io](https://wikitopics.github.io)):** A very simple quiz where users guess the most popular topics present within a particular time period. (Source code at [WikiTopics/wikitopics.github.io](https://github.com/WikiTopics/wikitopics.github.io))

## Group Credits:
- **Om:** Data Extraction/Conversion (Notebooks 1-3)
- **Nishanth:** Topic modeling work using BERTopic; conversion to JSON format used by the website (Notebook 4)
- **Harshit:** Topic data analysis + insights _(misssing, will be added upon completion)_
- **Kenny:** Website creation
