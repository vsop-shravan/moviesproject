# Logistic regression on IMDB Movies plot summaries to predict Genre
"Greed and class discrimination threaten the newly formed symbiotic relationship between the wealthy Park family and the destitute Kim clan." This is the plot summary of the 2019 movie 'Parasite' directed by Bong Joon Hu.
Do you think this is a Comedy? an Adventure? a Thriller? 

Our model predicts the answers as Yes, No, No whereas the answers are Yes, No, and Yes respectively. 
In fact, our algorithm does better than blind guesses - Blind guess of `No’ gives accuracies of 66%, 75%, 80%, for genres Comedy, Action, Thriller, respectively (for example, there are 500/1500 comedy movies). Where as our algorithm gives 75, 80, 87% accuracy. Furthermore our algorithm gives 99% accuracy on 'War' genre (likely because the word 'war is used in summary'.

