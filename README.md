<b>                     Assignment
                        Due 10 June 2021 23:59</b>
<b>                        Instructions</b>

Discuss what factors should you consider while designing and implementing software to detect plagiarism and para phasing? Develop sample application* for your arguments and prepare a report. * note: Application is not necessarily of your own but you need to explain methodology properly.

**My work**

*Add work*

*New*

*Points*

***100 points possible***

<b>                     Plagiarism Detection using Text Similarity</b>

This is a utility to check if 2 documents are plagiarized or not based on their similarity.

**How it works:**

It takes 2 text documents as input.

**1**. First, text preprocessing, tokenizing, filtering of stopwords is done. Then  the term frequency - inverse document frequency(tf-idf) is calculated and the tf-idf matrix  is created.

**2.** The raw documents were converted into their vector space representation in step 1. Now, the cosine of the angle between two vectors (in this case, two documents on the vector space) is calculated. This is the cosine similarity between the documents.

        If the similarity is high, then there&#39;s a good chance that one of the two documents is plagiarized from the other.

## **Required Libraries &amp; tools**

- Python 3
- Jupyter notebook
- Scikit-learn

**Demonstration:**

 ![main_window](/images/main_window.png?raw=true "Main Window")

Main window

**Custom Input:**

 ![custom_input](/images/custom_input.png?raw=true "Custom Input")

User has to enter 2 documents in the text fields , save them and press compare.

 ![custom_result](/images/custom_result.png?raw=true "Custom Result")

A message box will be shown that contains the percentage of similarity between the 2 text documents. The more the similarity, the more is the chance of plagiarism.



**Evaluation:**

We have used 4 categories of 20 newsgroup dataset for evaluating our proposed method.

 ![evaluation_window](/images/evaluation_window.png?raw=true "Evaluation Window")

Category Selection

 ![category_selection](/images/category_selection.png?raw=true "Random Source")

A random document is selected from the categories. This will work as the source document.

 ![similar_doc](/images/similar_doc.PNG?raw=true "Most Similar Document")

The software has found out the most similar document to the source.

 ![eval_similarity](/images/eval_similarity.png?raw=true "")

A message box will be shown that contains the percentage of similarity between the 2 documents.

 ![eval_category](/images/eval_category.png?raw=true)

Then the category of the most similar document will be displayed. If the category of the newly found document matches with the category of the source document then it proves that our algorithm works reasonably well.

Contributors:

Thapa Magar Khom Raj (https://github.com/KhomZ)<br>
kyzen khom (https://github.com/ikhomkodes)<br>
M.M. Arefin Zaman (https://github.com/murkho)<br>
Imran Sayeed (https://github.com/Imran51)
