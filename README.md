# Name-Entity-Recognition
Named-entity recognition (NER) is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.

### Dataset

This is the link to the [dataset](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)

### Approach !!!

- First I extracted the main information from the dataset to process it further.
- Then, I used BertTokenizer to tokenize the words so that these words can be processed by our network.
- After that **Bert Tranformer** specifically **BertTokenClassification** to classify the words according the tags or entities. 

### Result !!!

After 3 epochs :
- Training Loss = 0.0357
- Validation Loss = 0.1763

### Sample Output:

Input Text :

![Capture](https://user-images.githubusercontent.com/50714723/110706212-86133400-821d-11eb-952a-7c95333e2db2.JPG)

Output:

![2](https://user-images.githubusercontent.com/50714723/110706305-aa6f1080-821d-11eb-9fa2-4d487736e66c.JPG)
