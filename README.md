Hi, welcome to my Github account made for recruitment purposes. 
Currently I am looking for a job that allow me to develop my skills, mainly regarding cooperating with other developers.

Cause not all of my project can be published I prepared short descriptions of them and I'll be happy to present
my code during interview.


Automated webstore.

This project uses Scrapy/Selenium to gather data from specified supplier webpage and upload it to django models.

If data provided are not sufficient we got additional module that takes title line like 
"Laptop Lenovo X250 i5-5gen 8GB 180GB SSD KAM Windows Professional", searches for model details in Duckduckgo/CNET,
creates template and fills it with specified parameters from title, If photos are missing, takes them from Bing.
There is additional scraper to prepare processors database with number of cores and frequency,
When it's all ready products are uploaded to Prestashop with features, options and combinations by my script based on prestapyt library. 

Status: in develepement. usable
Scrapy
Selenium
Django
Prestashop

demo: https://demoabc.coolcatsof.dev/
used in: https://bullimania.pl/



Betting services playing bot.

In last month I was part of team creating bots for mass play in betting services. 
Bot tasks:
receive and parse data from Betburger,
and play simultanously on several websites. 
My part was to write serve BETCLICK, EXPECT, UNIBET, BETSSON, CASHPOINT

Status: finished succesfully
Selenium Webdriver
Seleniumwire
