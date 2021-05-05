# StoryTime2.0
Repo for the next iteration of StoryTime children's book recommender

Reading is an invaluable skill for teenagers, with the National Institute of Child Health and Human Development (NICHD) claiming: “Reading is the single most important skill necessary for a happy, productive, and successful life.” However, there is difficulty searching through large quantities of books trying to find one that is interesting and appealing enough to read. Depending on existing book recommender systems is not an answer to the problem, since most existing book recommender systems rely on previous reading data, reviews, or web traffic, but much of this data can be difficult or illegal to access for teenagers due to laws that protect the privacy of minors. Instead, we propose a novel technique of analyzing the emotional contents of a book and using them to compare the similarity of books and predict the likelihood a user will enjoy it based on their age. By using the [NRC Emotion Intensity Lexicon (NRC-EIL)](http://saifmohammad.com/WebPages/lexicons.html), we construct an emotion vector that represents the book’s ratio of emotions based on its description. By utilizing trends apparent in age groups regarding emotional preferences, we can create a recommender system to recommend books with relevant, age-appropriate emotional compositions and focuses. We further explore how to improve the accuracy of determining a book’s emotions by analyzing the synonyms of non-emotional words as well as the different preferences of different age groups of teenagers, namely that 12-13 year olds prefer Joy and Surprise and dislike Sadness, Fear, and Anger, while older teenagers exhibit the opposite trend. We have also discovered that high-rated books were significantly different from low-rated books in terms of emotion composition across all age groups.

# Organization

Method: All code for the individual parts and the whole of the recommendation strategy.

Evaluation: All code for evaluating the recommendation strategy.

Data: All data needed for development and evaluation.

Sandbox: A place for trail code. I figured this would be needed once we start try to combine all the moving parts. 

Be sure to name everything intuitively so someone can know what the file is for or doing are by its name.
