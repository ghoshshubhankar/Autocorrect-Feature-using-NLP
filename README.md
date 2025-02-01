# Autocorrect-Feature-using-NLP
Autocorrector Feature Using NLP in Python:
Autocorrect is a way of predicting or making the wrong spellings correct, which makes the tasks like writing paragraphs, reports, and articles easier. Today there are a lot of Websites and Social media platforms that use this concept to make web apps user-friendly.
Data In hand:
The dataset used in this project is an unstructered data. Basically here we used a novel of Sherlock Holmes. 
Analysis:
So, here we are using Machine Learning and NLP to make an autocorrection generator that will suggest to us the correct spellings for the input word. We used Python for this. 
Using the data at first we created the list of correct words. Then using dictionary we counted the total no of distinct words and store their frequency. Then calculated the probability of the distinct words.
So, After that the further process is divided into 5 main parts ….that created all types of different words that are possible.
 To did this, we used :
1.	Lemmatization 
2.	Deletion of letter
3.	Switching Letter
4.	Replace Letter
5.	Insert new Letter

To do Lemmatization we have used pattern module. 
For deletion of letter we created function which removes letter from a given word.
In switching the letter here we basically swaps the two letters of a word.
And then we replaced one letter by another but after replacing the letters the work was not done properly, by doing these steps we didn’t able to create enough suggestions for a wrong word so, for that reason we did one final step that was inserting new letters which helped to create enough meaningful suggestions against a wrong word and increased the accuracy of the given task.
Now, we have implemented all the five steps. It’s time to merge all the words (i.e. all functions) formed by those steps. To implement that we used 2 different functions.

Thereafter, the main task was to extract the correct words among all. By using a user defined function we did the same.
So, now the total project is almost ready. Finally we checked it by putting some wrong words like “daedd” against which it gave suggestions like ‘dared’, ‘dead’, ‘died’. 

Conclusion:
So, basically here we have implemented the basic auto-corrector using the NLTK Library and Python. For further steps, we can work on the High level auto-corrector system which uses the large amount of dataset and works more efficiently. 
To enhance accuracy, we can also use transformers and more NLP related techniques like n-grams, Tf-idf, and so on.


