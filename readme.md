1. Installing Libraries That Are Required
   pdf2image==1.10.0
   pytesseract==0.3.0
   opencv_python==4.1.2.30
   numpy==1.19.4
   pandas==0.25.3
   Pillow==7.0.0
   fastapi[all]
   pytest==6.2.2

2. Using Regular Expression

   Exercises of Regular Expression can be done here https://regex101.com/.

   Whenver We Will be working on any reserve character we have to use scape sequence.
   Anydigit = \d
   Adding repeated digit = +
   Any special or reserved characters = \{characters}
   Example : 1520$ = \d+\$

   What if 45 dollars and Both the previous one- Meaning 120$ and 120 Dollars
   \d+\$|\d+dollars

   Regex For Websites Information Extraction :
   "www\.[a-zA-Z0-9]+\.com"gm

   Exercise: Extract all Twitter handles from the following text (i.e. your answer should be teslarati, dummy*tesla, and dummy_2_tesla). Twitter handle is the text that appears after https://twitter.com/ and is a single word. Also, it contains only alphanumeric characters i.e. A-Z a-z, o to 9, and underscore *

   text = "Follow our leader Elon musk on Twitter
   here: https://twitter.com/elonmusk, more information
   on Tesla's products can be found at https://www.tesla.com/.
   Also here are leading influencers for tesla-related news,
   https://twitter.com/teslarati
   https://twitter.com/dummy_tesla
   https://twitter.com/dummy_2_tesla

3.
