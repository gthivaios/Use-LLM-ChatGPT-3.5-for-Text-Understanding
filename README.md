# Use LLM (ChatGPT 3.5) for Text Understanding

## Scope of this project

How we can do advanced text analysis in texts with political content? Researchers have found that LLMs are capable of carrying out nearly any text analysis task we throw at them. As these models are general rather than taskspecific, they are even able to carry out tasks that traditional computational methods have failed at – such as irony, sarcasm or subjective and contextual interpretation. Recent studies have found that LLMs perform well for a wide range of purposes, including ideological scaling, text annotation tasks, for simulating samples for survey research, and much more.
As an illustrating example, we will draw on the important task of measuring populism in political texts. Within populism research, text analysis is seen as a direct way of measuring politicians’ ideas as they are communicated to the public. However, measuring populism in text has proven a longstanding challenge.
The project is designed as an experimental collaboration between political theory and data science. I’ve started this project with a focus on the Greek general elections, that took place before 4 months and more specifically in the political speeches of the two major leaders, K.Mitsotakis(New Democracy) and A.Tsipras(SYRIZA).

## How we analyze the campaign speeches of political leaders?

- Collect speeches from the written text that the partty provides
- Preprocessing text(lowercase, remove stopwords, remove special characters, lemmatize)
- Calculate word frequency(wordcloud)
- Calculate tf-idf for bigrams(N=2)
- The dominant sentiment (sentiment analysis) expressed in each paragraph, categorized as positive, neutral, or negative.
- The main topic of each speech. To conduct the thematic analysis, i have created a list of topics which may be expanded if required during the election period. The current list includes the following topics: climate change, education, health, economy, labour, elections, social causes, politics and ideology. Paragraphs that do not fit any of these topics are categorized as “other”
- Rationality vs intuition
