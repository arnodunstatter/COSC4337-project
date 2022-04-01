Here are some installion commands we used, apart from the usual (pandas, numpy, etc):
pip install wordcloud
pip install nltk
pip install spacy
python -m spacy download en_core_web_sm

It should be noted that the finBERT model is rather RAM hungry.
Particularly the codeblock within the "Now to test over the entirety of the dataset, but in small batches"
header. This section worked when run on a desktop with 6 GB of available RAM, but failed on a laptop with less 
available RAM. 
