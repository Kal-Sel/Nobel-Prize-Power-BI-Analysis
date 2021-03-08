# Nobel Prize Data Analysis With Power BI

The Dashboard can be accessed [here!](https://app.powerbi.com/view?r=eyJrIjoiODc4MWVhMTEtNjA4NC00NzgzLThiZWMtNzMwNGQzZjNlMzVkIiwidCI6IjdlMWM0MDhjLTkyNDItNDcyYS05NmI4LWQzZjczZWQzYWQyZiJ9)

## Motivation

Since I want to exceed my analytics skills and knowledge, I try to gain experience through a diversity of open source projects. On that path, I am using different tools and techniques to gain insights and eventually solve real world problems. A couple of days ago I've stumbled upon Microsofts' __Power BI__ so I decided immediately that I want to do a project with it. Since the Nobel Prize Awards were taking place at that time, I was thinking that a Nobel Prize Analysis would be a good start with Power BI.  

## Description

For this project, I've used the Rest based API provided by [``Nobelprize.org``](https://www.nobelprize.org). The Site offers open data to developers in two ways: as API and as Linked Data. The data is free to use and it contains information about the Nobel Prizes and the Nobel Laureates. The data is updated as the information on ``www.nobelprize.org`` is updated, including at the time of announcements of new Laureates.

Endpoints for the API are:
``https://api.nobelprize.org/2.0/laureates``
This endpoint sorts the output based on Nobel Laureates (persons and/or organizations). It returns all information about Laureates and Nobel Prizes.
``https://api.nobelprize.org/2.0/nobelPrizes``
This endpoint sorts the output based on Nobel Prizes. Upon request, this endpoint returns a shorter result and the Laureates endpoint needs to be called as well to get the full response.

On 27 November 1895, Alfred Nobel signed his last will and testament, giving the largest share of his fortune to a series of prizes in Physics, Chemistry, Physiology or Medicine, Literature and Peace – the Nobel Prizes. In 1968, Sveriges Riksbank (Sweden’s central bank) established The Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel.

## Facts

* Between 1901 and 2020, the Nobel Prizes and the Prize in Economic Sciences were awarded 650 times. A total number of 930 Laureates were awarded, as you can see [``here``](https://github.com/Kal-Sel/Nobel-Prize-Power-BI-Analysis/blob/main/MostAwardedCategories.png).  
__*For this analysis, I've left the data on awarded organizations out.*__

* [``This Screenshot``](https://github.com/Kal-Sel/Nobel-Prize-Power-BI-Analysis/blob/main/Media/LaureatesAffiliation.png) shows a map with the universities, research institutions or companies Nobel Laureates were affiliated with at the time of the Nobel Prize announcement. Only Nobel Laureates in Physics, Chemistry and Physiology or Medicine, and Laureates in Economic Sciences are shown in the list. *(For a detailed look, open the [``PowerBI File``](https://github.com/Kal-Sel/Nobel-Prize-Power-BI-Analysis/commit/38aa9b0d854b14bac12019c52bfc181f656cae59) in this repository.)*

* The youngest Nobel Laureate is [`Malala Yousafzai`](https://en.wikipedia.org/wiki/Malala_Yousafzai), for her struggle against the suppression of children and young people and for the right of all children to education. She received the prize at the age of __17__.  
The oldest Laureate is [``John B. Goodenough``](https://en.wikipedia.org/wiki/John_B._Goodenough), for the developement of lithium-ion batteries. He received the Nobel Prize at the age of __97__.

* The Nobel Prize has been awarded 59 times to female Laureates, compared to the 946 times male Laureates have been awarded. The difference in percentage is [``5,87% to 94,13%``](https://github.com/Kal-Sel/Nobel-Prize-Power-BI-Analysis/blob/main/LaureatesGender.png).

* Two Nobel Laureates declined the prize and one was restricted.  
[``Jean-Paul Sartre``](https://en.wikipedia.org/wiki/Jean-Paul_Sartre), awarded the 1964 Nobel Prize in Literature, declined the prize because he had consistently declined all official honours.  
[``Le Duc Tho``](https://en.wikipedia.org/wiki/L%C3%AA_%C4%90%E1%BB%A9c_Th%E1%BB%8D), awarded the 1973 Nobel Peace Prize jointly with US Secretary of State Henry Kissinger. They were awarded the Prize for negotiating the Vietnam peace accord. Le Duc Tho said that he was not in a position to accept the Nobel Peace Prize, citing the situation in Vietnam as his reason.  
[``Boris Pasternak``](https://en.wikipedia.org/wiki/Boris_Pasternak), the 1958 Nobel Laureate in Literature, initially accepted the Nobel Prize but was later coerced by the authorities of the Soviet Union, his native country, to decline the Nobel Prize.

* The majority of Laureates, __*53*__ of them, are/were located in New York, followed by Paris with __*26*__ Laureates. Other cities are listed [``here``](https://github.com/Kal-Sel/Nobel-Prize-Power-BI-Analysis/blob/main/LaureatesLocation.png).  


*Feel free to take a look at my analysis and your feedback is very much appreciated*. :smile:
