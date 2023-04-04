# Python-CommonCrawlerURLs
A way to pull a list of URL's and appropriate Keywords from a Common Crawl dataset and save it to a .txt file.

This is simply a way to pull the URL's and keywords (if applicable) from the Common Crawl dataset.

The code finds every URL and keyword, matches them, and saves them to a .txt file.

You will need to download your own WARC files from Common Crawl. I used the instructions located below:

https://commoncrawl.org/2023/02/jan-feb-2023-crawl-archive-now-available/

Download a WARC file, open with notepad (or equivalent), take the first URL and download the file, I used this one:

crawl-data/CC-MAIN-2023-06/segments/1674764494826.88/wet/CC-MAIN-20230126210844-20230127000844-00000.warc.wet.gz

Convert the downloaded file to a .txt and then run this script. Most websites do not have sufficient keywords, but this is really just a demonstration.
