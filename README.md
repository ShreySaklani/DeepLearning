# DeepLearning- Fake News Prediction

Objective: To classify news and identify if the news is real or fake news using Natural Language Processing

What Is Fake News?
-> Fake news is false or misleading information presented as news. It often has the aim of damaging the reputation of a person or entity or making money through advertising revenue.
-> The prevalence of fake news has increased with the rise of social media, especially on Facebook and Whatsapp. Political polarization, post-truth politics, confirmation bias, and social media algorithms have been implicated in the spread of fake news in today's digitalized world.

Does It Really has any Impact?
-> Fake news can reduce the impact of real news by competing with it; a Buzzfeed analysis found that the top fake news stories about the 2016 U.S. presidential election received more engagement on Facebook than top stories from major media outlets
->Misinformation and disinformation spread in media is becoming a serious social challenge. It is leading to the poisonous atmosphere on the web and causing riots and lynchings on the road. 
 ->It also has the potential to undermine trust in serious media coverage.The term has at times been used to cast doubt upon legitimate news, and U.S. president Donald Trump has been credited with popularizing the term by using it to describe any negative press coverage of himself

EXAMPLES of FAKE NEWS
-> Muzzafarnagar riots of 2013: fake video fuelled communal passions
-> UNESCO has declared ‘Jana Gana Mana’ best national anthem in the world (WhatsApp)
-> President Kovind makes Twitter debut; gains 3 million followers in one hour (Republic, Zee news, TOI etc.)
-> GPS tracking nanochip in 2000 Rupee notes (Nov 2016)
-> Ministry of Home Affairs (MHA) annual report used a picture of Spain-Morocco border to show Indian border floodlighting Missing JNU student Najeeb Ahmed has joined the ISIS

NLP and It's Use Cases
NLP represents the automatic handling of natural human languages like speech or text, and although the concept itself is fascinating, the real value behind this technology comes from the use cases. Some of its use cases are discussed below:

-> Amazon’s Alexa and Apple’s Siri are examples of intelligent voice-driven interfaces that use NLP to respond to vocal prompts and do everything like find a particular shop, tell us the weather forecast
-> Companies like Yahoo and Google filter and classify your emails with NLP by analyzing text in emails that flow through their servers and stopping spam
-> Organizations can determine what customers are saying about a service or product by identifying and extracting information in sources like social media
-> NLP enables the recognition and prediction of diseases based on electronic health records and patients’ own speech. This capability is being explored in health conditions that go from cardiovascular diseases to depression and even schizophrenia

Insights From EDA 
-> Political News and World News hold the most domination counts in the data set that we have considered.
-> The maximum number of titles range between 7-8 words. Would be a bit tricky to judge if the news is true or fake only with these few words. So we hope we shall not be getting a great amount of accuracy using the title alone.
-> News articles are within a range of 100-200 words. Anything beyond this point is not very catchy, and even the media tends to avoid it. But yes when the number of words is such large, it will be much easier for the model to predict.

Conclusion
-> We have been successfully able to reach the target for classifying a News- and are able to identify if this is a True or Fake
-> Its not much feasible to predict the news just from its title. Titles may be misleading.
-> A much better Idea was obtained when we considered the context for the News. The accuracy percentages shot up 
-> Considering both the title and the context, we have been able to reach the highest percentages of accuracy
