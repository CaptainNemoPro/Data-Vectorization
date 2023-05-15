# Data-Vectorization

Since we have to perform vectorization at some point, we need to be mindful that we want as many minimum columns as possible in our list of unique words.

We have already looked how we can achieve the same using lemmatizing and stop words removal, however we cannot ignore the numbers in our data which may have been entered mistakenly and is required to be removed as it will eventually increase the number of columns in our list of unique words.

# What has been performed?

To achieve the same I have first of all created a function that will remove the stop words, but since this is not the end of the story I have further made a function that will remove the number from the data thereby making vectorization much simpler for us and ofcourse python.

# After MATH

I have compared the number of unique words generated before and after removing the stop words and number form the text data and the difference was significant. This explains the significance the data cleaning before we procees to do anything further.