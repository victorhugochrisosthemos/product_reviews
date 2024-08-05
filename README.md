Natural Language Processing to categorize product reviews as positive or negative

Considering the needs of a public relations department, paying attention to comments 
about a company on social media proves to be a factor to be considered in strategic 
decision-making relationships. With this in mind, the use of Machine Learning can 
help optimize the categorization of reviews, defining them between positive and 
negative. To do this, a dataset coming from customer comments that have experienced 
a product, with a sufficient number of customer reviews together with a manual 
rating of positive or negative, we can now create a natural language processing 
algorithm to generate the project.

Basically, the project carried out analyzes more than 3000 reviews using 
Machine Learning techniques. With a database trained in this coding, it 
is possible to receive new evaluations and automatically define whether 
they are positive or negative.

Regarding the initial dataset, there needed to be a column defining 
whether the review is positive or negative, necessary to later apply 
Naïve Bayes and Logistic Progression methods. After this part, the 
developed base does the classification on its own.

To train the machine, I needed to join all the reviews into a string, 
remove words that don't help to understand feelings (like me, you, this), 
remove accents and then generate a matrix with the column being all 
the unique words existing in that string . Then, for each review, a 
line was defined in this matrix, identifying the frequency of each 
of the relevant words in this column, being used later to train the machine.

In the case of this example, I used a database of reviews made 
by customers of the Amazon Alexa product available on the Kaggle 
website, in addition to having the help of classes by Doctor in 
Artificial Intelligence Jones Granatyr.

The concepts covered include data pre-processing, generation 
of graphs to analyze correct processing, Tokenization (CountVectorizer from sklearn), 
intuition through Naïve Bayes algorithms and algorithms related to 
logistic progression (LogisticRegression from sklearn).

Kaggle website that I used: (https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews)
