![sentiment analysis pic.png](https://github.com/jdickson207/final-project-/blob/master/visualizations/sentiment%20analysis%20pic.png?raw=true)



# What is a sentiment analysis?
The Oxford Dictionary defines a sentiment analysis as such: sen·ti·ment a·nal·y·sis, a noun, the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral. In other words, it is a technique through which you can analyze a piece of text to determine the sentiment (feelings) behind it.

## Why do a sentiment analysis?
Friedrich Nietzsche said: "A good writer possesses not only his own spirit but also the spirit of his friends." I feel like this quote embodies so much of how we, as human beings, express ourselves online. I wanted to explore this concept a bit by doing a sentiment analysis of user comments of chosen YouTube videos though Machine Learning in the area of Natural Language Processing.

### Background information/Hypothesis:
This sentiment analysis is based on 3 different YouTube channels that focus on their families' dairy farms that were all posted within a 24 hour period on the date of November 17, 2021. I wanted to see if the sentiment/defining words varied based on the channels' geographic locations. The farm channel names are: Tom Pemberton Farm Life, Sask Dutch Kid, and 10th Generation Dairyman. Tom Pemberton's farm is in Surrey, England. Sask Dutch Kid's farm is in Saskatchewan, Canada. The 10th Generation Dairyman's farm is in Pennsylvania, USA.


![SDK_wordcloud.png](https://github.com/jdickson207/final-project-/blob/master/visualizations/SDK_wordcloud.png?raw=true)


### Conclusions/Final Thoughts:
I found that the different words that defined each channel varied greatly. For the farm in England, the words that best defined the channel were words such as name of the farm's bull (Nigel) and a lot of British slang/curse words. Some of this can be attritubted to geographical location (like the slang/bull name), but I also think it could be a result of the overall sentiment of this channel. Are slang and curse words postive or negative? For most people, they would be considered negative when taken in context of their usage. 
For the Canadian farm, a lot of the words that defined the channel were words that pertained to the farm, like parlor (for a milking parlor) and wellies (boots you wear for muck/mud/messes). These words don't seem to invoke a strong reaction either way, so they would be consdiered neutral. 
For the American farm, the defining words were predominately focused on the farm and the family members that the farmer mentioned in the video itself. This showed to be quite postive in the the sentiment shown in the words that defined this channel.

I feel like I should mention that there are many different ways to perform a sentiment analysis. As a farmer myself and language enthusiast, this is just the way that I chose to do it. Don't let my methods and choices defer you from doing this differently if you chose to do so. :)


### Acknowledgements:
THank you to Tina Huang and Ken Lee for all of their guidance and for paving the way for new data scientists to learn and grow their skills. You can find their YouTube channels here: https://www.youtube.com/c/TinaHuang1  https://www.youtube.com/channel/UCiT9RITQ9PW6BhXK0y2jaeg


### Notes:
In order to perform the analysis as I did, you will need a developer key. You can get one from Youtube Data API: https://developers.google.com/youtube/v3


