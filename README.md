This project analyzes the comments in facebook posts efficiently with language traslation, emoji detection, hashtag detection, name entity recognition, and sarcasm detection using fine-tuned BERT deep learning LLM.
It gives very eye catching visulaizations about analysis outputs

There are some kind of difficulties and challenges that I had faced was it costs for everything. For example, when I was trying to translate other foreign languages to English, I had to use Google Cloud official translation API and it is not free. 
Also, when there are thousands of comments in a post, we can't fetch all comments at once, so we have to take those comments as batches. So, in order to improve the efficiency of analyzing comments, I had to parallalize the process of analzing comments. Sor for that, I have used aiohttp, asyncio, but for that also, it costs too much for my budget
