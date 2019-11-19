# thoughts-to-words
> 
### 19th November 2019
- **Two Sum** (which two array elements add up to a `val`): Hash Map! Iterate through array. Check if `val` - array element is present in the hash map. If not add array element as key,value pair inside hash map.

--- 


### 18th November 2019
- **Intersection of Linked List** (to find whether two linked lists intersect): Have two pointers: headA and headB. Increment them until they finish, then make them point to the other's head. Idea is because of their length difference, they *will* end up pointing to merged node (or at the end of the lists) at the next iteration.

--- 

### 16th November 2019
- **Ciruclar Linked List** (to see if linked list has a circle): Have two pointers: fast(jumps two steps) and slow(jumps one step). The idea is if there is a circle, first will eventually become equal to slow. 

--- 
### 15th April 2019
- Cosine Similarity more robust than Dot Product as similarity measure for word vectors specially when the word embedding model is trained on really less data. For pretrained embeddings or when word embedding model is trained on considerably large data, the two similarity metric would not have much difference in query expansion and consequently retrieval effectiveness. 

---

### 10th April 2019
- A MLP with unlimited data will give similar performance like a CNN. CNN is effective with constrained data. Also better than RNN since it can be parallelized. 
- Before trying a model or something always have the answer to the question *Why are you trying the new model?* ready. Better with toy examples. 

---

### 8th April 2019
- Cool [cheat sheet](https://github.com/abhat222/Data-Science--Cheat-Sheet) for people looking for interviews.
---
### 22nd March 2019
- Finished implementing IWE word embedding model. Here's the [github repo](https://github.com/roynirmal/IWE)! Time to run experiments. Pretty confident about PyTorch now.
---

### 9th March 2019
- Started implementing [IWE word embeddings](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14724) using PyTorch. They have their source code but it is written in C# :eyes: which is terrible for someone like me. Nonetheless, I hope I can implement it and find it to be performing better for my Query Expansion task! 

---

### 3rd March 2019
- Finished Word Embedding [tutorial](https://pytorch.org/tutorials/beginner/nlp/word_embeddings_tutorial.html) by Pytorch. It is part of the Deep Learning for NLP [tutorial](https://pytorch.org/tutorials/beginner/deep_learning_nlp_tutorial.html). Skipped the last [slide](https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html) for later, seemed a bit too advanced. 

--- 

### 26th February 2019
- There's not much difference between skip-gram and CBOW performance and really depends on the task. 
- However, it is important to keep in mind, for the same amount of data skip-gram (predictiong context from word) gets `N` times more training than CBOW (predicting word from context) where `N` is the context window :bulb:

---

### 25th February 2019
- Started following [this course](https://www.youtube.com/playlist?list=PL8PYTP1V4I8Ajj7sY6sdtmjgkt7eo2VMs) by Graham Neubig. Excellent series of videos to teach us about use of Neural Networks in NLP. They have links to their [github repo](https://github.com/neubig/nn4nlp-code) as well, which gave me the much needed kick to start learning pyTorch as well. 

- Working on the Literature Review is ongoing.

--- 

### 20th February 2019
- Okay not everyone appreciates markdown. Specially, non-technical people.

---

### 19th February 2019

- **Realisation**: Markdown is probably the best place to write informal things and thoughts. Specially for the forgetful like me. It looks cool too. 


- **Literature Review for my thesis**: The first draft completely tanked. [Claudia](chauff.github.io), my supervisor, could not finish reading the chapter - it was *that* bad. Nonetheless, time to improve my writing. We hardly have any *writing* practice in India. It's the system's fault, not mine. Aggregate findings and prior work, instead of simply writing two sentences about them! 

- However, [proposal](https://github.com/roynirmal/queryExpWikiPassageQA/blob/master/homerun.md) for the final part of my thesis was approved! 
