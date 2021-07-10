# NER-in-customs-declaration
I'm Long, this is my Project 1 at term 20202, Hanoi University of Science and Technology. <br />
My Instructor: DR. Thang Ngoc Tran.

#### Table of contents
1. [Data description](#description)
2. [Named-Entities description](#NEs)
3. [Compare the results obtained between `BERT` and `PhoBERT`](#compare)

# <a name="description"></a> Data description
The data is taken from the description of the customs declaration for cars and non-railway vehicles including records in Vietnamese. It should be added that this data is taken from records for 2015 and 2017 and the first few months of 2020 and the main item of vehicles is cars.
Data has 3 colums:

  - **Word**: words in sentences
  - **Tag**: entity label corresponding to **Word**
  - **Sentence #**: What sentence is the word in?

![alt text](https://github.com/longhoangphi225/NER-in-customs-declaration/blob/main/data.png)

