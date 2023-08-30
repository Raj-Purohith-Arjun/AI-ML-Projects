BLINDNESS DETECTION
You are provided with a large set of retina images taken using fundus photography under a variety of imaging conditions.

A clinician has rated each image for the severity of diabetic retinopathy on a scale of 0 to 4:

0 - No DR

1 - Mild

2 - Moderate

3 - Severe

4 - Proliferative DR
DATA SET AND INPUT FILE LINK AND REFERENCE :https://www.kaggle.com/competitions/aptos2019-blindness-detection
Like any real-world data set, you will encounter noise in both the images and labels. Images may contain artifacts, be out of focus, underexposed, or overexposed. The images were gathered from multiple clinics using a variety of cameras over an extended period of time, which will introduce further variation.

Files
In a synchronous Kernels-only competition, the files you can observe and download will be different than the private test set and sample submission. The files may have different ids, may be a different size, and may vary in other ways, depending on the problem. You should structure your code so that it returns predictions for the public test set images in the format specified by the public sample_submission.csv, but does not hard code aspects like the id or number of rows. When Kaggle runs your Kernel privately, it substitutes the private test set and sample submission in place of the public ones.
You can plan on the private test set consisting of 20GB of data across 13,000 images






















# Simple-Plagiarism-Checker

Web application of Plagiarism Checker using Python-Flask. TF-IDF and cosine similarity is a very common technique. It allows the system to quickly retrieve documents similar to a search query. Similarly, based on the same concept instead of retrieving documents similar to a query, it checks for how similar the query is to the existing database file. 

## Steps:
1. User enters a query
2. Query gets processed (Uppercase to lowercase, Removal of punctuationmarks, etc.)
3. Calculations are done (Term Frequency, Cosine Similarity)
4. The Plagiarism Percentage is returned on the web page

## Python-Flask
1. Flask is a light-weight web framework for Python
2. Easy to  work with (Same syntax as of Python)
3. While Flask addresses itself as a "micro-framework", it is not lacking in features or power, especially with a clutch of extensions to support features such as authentication, databases and so on
4. Comprehensive documentation available

