# TemperatureTextProject
Python program on my Raspberry Pi that texts my phone the current temperature every morning.

I created this project because the temperature on my phone would take forever to refresh. The refresh wheel would just keep spinning until either it refreshed or I gave up and didn't care what the temperature was. I had heard about web scraping with Python, but had never used it. I also learned that you could send text messages with a Python program using a website called Twilio. I decided to put these two things together to make my program.

The first thing I did was learn how to send text messages to my phone with Twilio. You'll need to install the helper library using the command 'pip install twilio'. Twilio has a lot of examples for different projects so I was able to find the code and modify it so that it worked for me. This code can be found in the text file 'message.txt'.

The second thing I did was learn how to web scrape with Python. Web scraping basically just takes information or data from a website. I used this to grab the current temperature from the weather channel's website. To web scrape, you'll need to install a helper library called Beautiful Soup used for web scraping. You can install this using the command 'pip install beautifulsoup4'. I found an example of code that I used to get an idea of how to use web scraping. This code can be found in the text file 'webscrape.txt'.

The third step in this project was to put together what I had learned and create a program that would text me the current temperature for my location. 
