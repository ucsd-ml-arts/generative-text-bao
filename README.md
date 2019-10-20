# Project 1 Generative Text

Bao Hoang, bghoang@ucsd.edu

## Abstract

I am a fan of sitcom so my idea would be generate a new script based on the script for a sitcom that I watched. Originally, I think that How I Met Your Mother would be a good show to use for this project. I used to watch this show 3 years ago and found it really interesting to follow Ted, our main character, and his love life. However, the generated text is really bad and sometimes you can't understand it. Therefore, I decided to include another script for another TV show, The Office. The result is significantly better. I will be using RNN for training module. The training data, as I mentioned, will be the script of How I Met Your Mother and The Office. 

## Model/Data

In this repository:
- File to get the script from a website: web_scraping.ipynb
- Training data: himym.txt, script.txt

## Code

Code that does the generate script:
- generative_code.ipynb

## Results

All the generated texts are in result folder:
- Inside result folder, the 'himym' folder contain generated text I have from just using the How I Met Your Mother script.
- The 'both' folder contain generated text that I have using How I Met Your Mother script and The Office script.
- I tried multiple inputs to see what result that I have.
- Some results are meaningless while some are decent.
- The name of each text file in result represent the number that I adjust for each case. 
- The best result is the one with batch size 100 and epochs of 200.

## Technical Notes

Package for software: 
- Since I used web scrapping method to get the script from a website, there are some packages, python libraries that need to be installed: BeautifulSoup library to get the html component, urlopen library to load the website.
- For generate text, you will need tensorflow and numpy.


## Reference

References to any papers, techniques, repositories I used:
- Repositories: 
  - [ECE 188 repo](https://github.com/ucsd-ml-arts)
- Tutorial:
  - [tutorial](https://www.tensorflow.org/tutorials/text/text_generation)  
  
