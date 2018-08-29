# Dataset: EMNLP 2018. Personalized Microblog Sentiment Classification via Adversarial Cross-lingual Multi-task Learning.


The userlist.txt contains the user id's correspondence between Weibo and Twitter. 

The first Weibo dataset was crawled using our built-in-house crawler from Sina Weibo, which contain only Chinese posts. Weibo users have their personal profile, and
their homepage links to Twitter may also appear in it. We extracted the Twitter homepage links for crawling our Twitter dataset via Twitter API, and the dataset contain only English posts.


Each post is formatted by "uid + "\t" + post  + "\t"+ emoticons" , or "uid + "\t" + post".

In the paper, we labeled the posts with sentiment polarity based on frequently used emoticons. Nevertheless, in this dataset, we have released all bilingual corpus we have collected, including posts without emoticons. You can label the posts by emoticons, or label manually for more available posts
according to your own needs.

-------  

For crawling more monolingual corpus, please use Sina Weibo API or Twitter API.
