# Wiki_Crawler
A python based web crawler


Gone are the days when All roads leaded to Rome, now every link leads to Philosophy wiki page.

Quoting wikipedia-"As of May 26, 2011, 94.52% of all articles in Wikipedia lead eventually to the article Philosophy."
Link :  http://en.wikipedia.org/wiki/Wikipedia:Getting_to_Philosophy

This crawler, does exactly what it intends to : Crawling. It crwals through the first link of any wiki page untill it finds the Philosophy page.

The program is really very simple and interesting, not to forget that the most important thing in the program is to have an terminatig condiotion, without which it might keeps on crawling, wasitng memory space and time.
 
In my case, I have chosen the no. of links visited the terminating condition:
            if(i==100):                 #if link count reaches hundred, the program aborts
				      print "Quitting"
				      sys.exit(1)


The program takes, a string as input i.e. first wiki page you intend to start your search from, then it keeps on crawling untill it finds the safe heaven i.e. Philosophy wiki page.
