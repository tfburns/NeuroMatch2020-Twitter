# NeuroMatch2020-Twitter
 Twitter data analysis from #NeuroMatch2020

This is a bit of bare-bones repo. But as a quick bit of documentation:
- `NeuroMatch Twitter Data Scraping & Analysis.ipynb` is a Jupyter Notebook which collects Twitter information. It relies on some packages like `tweepy` and `GetOldTweets3` to get its data, and you'll need a Twitter API key to run the anaylses. Details about this are in the notebook.
- `neuromatch_participants` is a Twitter Streaming Importer plug-in query file for Gephi. More info on Gephi here (https://gephi.org/) and more info on its Twitter Streaming Importer plug-in here (https://github.com/seinecle/gephi-tutorials/blob/master/src/main/asciidoc/en/plugins/twitter-streaming-importer-en.adoc).
- `neuromatch_twitter_network.gephi` is a Gephi file where each vertex is a Twitter user, and an edge exists two users if one of them followers the other.
