# Easy-to-Hard Generalization in Math Problems
This is our final project for **10-623: Generative AI** as taught by Matt Gormley and Yuanzhi Li at CMU in Spring 2024. 

Easy-to-hard generalization has been demonstrated on simpler datasets, but not on the [MATH dataset](https://arxiv.org/pdf/2103.03874), whose questions were designed to be particularly difficult to solve. We categorize the questions in the dataset into easy (levels 1-3) and hard (levels 4-5) and fine-tune two models — Llama2-7B and Llemma-7B — on either only the easy questions or on all the questions and then evaluate them on hard questions of the test dataset. Because of time and computation constraints, we test on a subset of the full dataset. 

We draw heavily from the [MATH repository](https://github.com/hendrycks/math). Our comprehensive list of our changes can be found under *6 Code Overview* in our final report. 
