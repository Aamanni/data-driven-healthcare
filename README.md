# Data-driven healthcare

Final project for the Building AI course

## Summary

Healthcare is going through a transition and facing challenges, e.g. because of aging population. Insights from data help in targetting the scarce healthcare resources and lead to huge savings for the society and to better quality of life for people. 


## Background

Some questions that could better be solved using AI-methods: 
* how to identify groups that have a high probability of having a certain diagnosis or suffering from a certain condition, e.g. mental illness, stroke, sleep apnea 
* how to differentiate between different treatments and their effectiveness in terms of costs and patient outcome
* how to speed up clinical trials by finding study and control populations


## How is it used?

The insights derived from the healthcare AI solutions could be used e.g. by the healthcare policy makers when optimizing the resource allocations. Also if high-risk populations for a certain diagnosis would be identified more precisely, the preventive solutions could be targeted more effectively and the developments of high-risk statuses to diagnoses could be slowed down and reduced.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

One of the largest challenges in healthcare related AI solutions is that actual patient data would be needed and that data is very sensitive and its use is limited and controlled for good reasons. Permissions to use the data need to be obtained. Procedures to collect, store, handle, anonymize / pseudonymize, analyze, archive and eventually delete have to be well defined and strictly followed.

In Finland and other Nordic countries the situation regarding the digital strucured patient data is probably better than on average.

Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

TBD

## What next?

The intention is to start with a few small-scale Proof-of-Value projects where the challenges related e.g. to data availability and permissions to use will be solved in practice. A few well-specified diagnoses will be taken for analysis and an understanding of the data quality, possibilities to apply simple AI methods.

Healthcare sector and medical device business as a whole are very promising application areas for AI because:
* 
How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
