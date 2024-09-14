# Summarization-with-BART

In this notebook we will look at a (artifical) 8 page PDF document containing 
  1. CV definition and summary
  2. sample CV 1
  3. sample CV 2
     
Using the pretrainied BART model enables us to summarize the pdf. As the token input size of BART is 1024 we will do some data prepocessing beforehand and then feed it into the BART model.
