# BussinessOnBot-Task2

# Sentiment analysis

**This task is about predicting the Twitter sentiment**

Algorithms used - **Naive Bayes**
                               Multinomial naive  bayes has been used to find the probability of classes assigned to texts using the joint probabilities of words and classes, the Naive Bayes algorithm was used. The basic idea behind Naive Bayes is to find the probability of classes that have been assigned
Given that they computed a database of probabilities for terms appearing in the dataset (positive or negative). It can proceed to the last step of the Naive Bayes classifier, which is the classification.

                          𝑦 = 𝑎𝑟𝑔𝑚𝑎𝑥 𝑘 ϵ{𝑃𝑜𝑠𝑖𝑡𝑖𝑣𝑒, 𝑁𝑒𝑔𝑎𝑡𝑖𝑣𝑒} 𝑝(𝐶 𝑘 ) 𝑖 = 1 N 𝑝(𝑥 𝑖 | 𝐶 𝑘 )

Libraries - **VaderSentiment **( for analysis)
                             VADER means Valence Aware Dictionary and sEntiment Reasoner.VADER is a lexicon and rule-based feeling analysis instrument that is explicitly sensitive to suppositions communicated in web-based media. VADER utilizes a mix of lexical highlights (e.g., words) that are, for the most part, marked by their semantic direction as one or the other positive or negative. Thus, VADER not only tells about the Polarity score yet, in addition, it tells us concerning how positive or negative a conclusion is.
