# Assignment_10_Jinwoo_Oh

# Threshold
0.45

# Hypothesis
My hypothesis is that the longer the text, the more mistakes Perspective will make.

# Assess the Hypothesis based on your sample
As you can see on the result, for short toxic comments, I got about 90% accuracy. However, for the long toxic commnets, I got about 50% accuracy which is low. Therefore, I would like to say that my hypothesis might be correct.

# How does a low sample size impact your results, and the conclusions we can draw from them?
A low sample size could have a significant impact on my results and conclusions I drew from them. Since my sample had only 40 comments, this absolutely affected my accuracy calculation. If there were more samples, the accuracy of the long text could have been higher, or the accuracy of the short text could have been lower. Therefore, I realized that I need more samples when I work on a huge project later on, because low sample size can reduce the reliability of my conclusion.

# What biases do you think might exist in the model based on intuitions or public documentation about how the model was created?
There are many possible sources of bias that can exist in the model. For example, looking at step 2, the word, "nigger", was the most common toxic word. However, the word that discriminates against Asians or other races could be not included in the model, which can be thought of as bias. Also, there can be some gender-related words such as Feminism. And there can be the possibility that these gender-related words can be thought of as toxic because the comments with those words usually come with a lot of controversies. We need to test the model more, but there could be more possible ways the biases exist.

# What were your results?
My hypothesis was that Perspective AI would make more mistakes on longer texts. Because the longer the text, the more positive and negative words are mixed, and I thought this fact would make it difficult for Perspective API to determine whether the text is toxic or not. First, to test this, we set the threshold as the average of the toxicity scores of toxic texts and the toxic scores of non-toxic texts obtained from the sample data. And, based on this threshold, I tested long toxic text, long non-toxic text, short toxic text, and short non-toxic text. The result says that longer toxic text has significantly lower accuracy.

# What theories do you have about why your results are what they are?
As I said in my hypothesis, Perspective API really made more mistakes on the longer texts. However, the result could be different if I had more sample size. Therefore, this does not mean that my hypothesis is absolutely correct, but that it is worth exploring more about Perspective APIs making more mistakes on longer texts.

# Personal Comment on the result overall
I've explored the accuracy of text's length this time, but I know that in order to evaluate this Perspective API, I still have to judge more elements. Gener-related words may cause more mistakes, or words referring to a particular race may cause more mistakes. In particular, I wonder the accuracy of Perspective API for text combined with other languages. Different languages often have different meanings, even if they have the same meaning in dictionary. Therefore, I wonder if Perspective API can understand the meaning of each country's cultural and social languages.
