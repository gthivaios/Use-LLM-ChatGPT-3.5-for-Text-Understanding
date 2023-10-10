# Analyzing-the-pre-elections-political-speeches-of-greek-major-party-leaders

## Why this project?

What are the main topics covered by political leaders in their campaign speeches? Which are the most important words/phrases in their speeches? How strong is the sentiment impact(negative or positive)? How inspiring their speeches are?
The project is designed as an experimental collaboration between political theory and data science. I’ve started this project with a focus on the Greek general elections, which happened before 4 months and more specifically in the political speeches of the two major leaders, K.Mitsotakis(New Democracy) and A.Tsipras(SYRIZA).

## How we analyze the campaign speeches of political leaders?

- Collect speeches from the written text that the partty provides
- Preprocessing text(lowercase, remove stopwords, remove special characters, lemmatize)
- Calculate word frequency(wordcloud)
- Calculate tf-idf for bigrams(N=2)
- The dominant sentiment (sentiment analysis) expressed in each paragraph, categorized as positive, neutral, or negative.
- The main topic of each speech. To conduct the thematic analysis, i have created a list of topics which may be expanded if required during the election period. The current list includes the following topics: climate change, education, health, economy, labour, elections, social causes, politics and ideology. Paragraphs that do not fit any of these topics are categorized as “other”
- Rationality vs intuition
