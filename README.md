# Legal-Sentence-Classification
This project aims to explore classification of types in annotated sentences of documents from the US Board of Veteran's Appeals’ decisions. Different segmenters are observed to select the optimal performing one, followed by tokenization and developing of a custom word embedding model from an unlabeled corpus. Finally, different models are used using TFIDF and word embedding featurizations to find the best performing according to some metrics.

* **Literature-Survey**: Carried out over different papers which use sentence classification on legal texts. An analysis of their methods and results are included at the end.
* **Project-Report**: Document of the comprehensive analysis done at every step of the project as well as discussions on the findings.

A requirements file with necessary libraries has been included.

The embedding model can be downloaded from [here](https://drive.google.com/file/d/1Q33eX6H9GXz-Jtsz-DmwimhDHzbOKmRX/view?usp=sharing).

All the other files included are used to run the **Setup_and_Analyze** notebook which contains the required **analyze** function. The notebook has three cells to be run sequentially. The analyze function takes a string and returns a list of split sentences along with the name of types they have been classified as. The **Project_Code** notebook includes all cleaned code with the outputs cleared to perform the entire classification pipeline.
