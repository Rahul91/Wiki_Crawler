# Wiki_Crawler
A python based web crawler


Gone are the days when All roads leaded to Rome, now every link leads to Philosophy wiki page.

Quoting wikipedia-"As of May 26, 2011, 94.52% of all articles in Wikipedia lead eventually to the article Philosophy."
Link :  http://en.wikipedia.org/wiki/Wikipedia:Getting_to_Philosophy

This crawler, does exactly what it intends to : Crawling. It crwals through the first link of any wiki page untill it finds the Philosophy page.

The program is really very simple and interesting, not to forget that the most important thing in the program is to have an terminatig condiotion, without which it might keeps on crawling, wasitng memory space and time.
 
In my case, I have chosen the no. of links visited the terminating condition:
        
        if (i==100):				#Quits if the link count reaches 100
        	print "Quitting"
        	sys.exit(1)



The program takes, a string as input i.e. first wiki page you intend to start your search from, then it keeps on crawling untill it finds the safe heaven i.e. Philosophy wiki page.

#Demo

Demo of the crawler works:

1. Execute the program, and tye in any name, this will be the starting point for your crwaler, one thing to keep in mind that, whatever you type-in, should have an wiki page.
![alt tag](https://github.com/Rahul91/Wiki_Crawler/blob/master/images/start.png)

2. We can see that its crawling, pages after pages. We can see that, the number of pages it has crawled.
![alt tag](https://github.com/Rahul91/Wiki_Crawler/blob/master/images/processing.png)

3. Finished processing, as it has reached Philosophy page.
![alt tag](https://github.com/Rahul91/Wiki_Crawler/blob/master/images/finished.png)


#Extra
Also do visit the link below, it graphically and beautifully shows how, Philosophy can be reached from any node(Article).
 Link : http://www.xefer.com/wikipedia 
