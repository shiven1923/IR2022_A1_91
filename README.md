# IR2022_A1_91
Information Retrieval 2022 Assignment 1 Group 91  
Member 1 : Shiven Gupta (2019333) @shiven1923  
Member 2 : Shubham Sharma (MT20324) @ShubhamMT20324  
Teaching Assistant : Rajat Agarwal @rajatag27  
Implementation of Inverted Index and Positional Index for Boolean Retrieval and Phrase Queries 

How to Use the Code?  
1. Extract the corpus from humor,hist,media,food.zip into folder called dataset_new
2. Run the CreateIndex2.ipynb code from the same folder containing dataset_new
3. Inverted_Index and Positional_Index will be created which can be used in Q1.ipynb and Q2.ipynb
4. Creationg of Indexes will take around 10 minutes.
5. Alternatively, you can use already created indexes inverted_index.txt and positional_index.txt by extracting those files from indexes.zip  

Q1.ipynb (Boolean Retrieval)  
ASSUMPTION : NOT operations will be processed first, OR operations will be processed second, AND operations will be processed third at last.  
It expects a number N i.e the number of queries  
For each query there will be 2 lines :   
1st line for the query in string , for e.g "romans, fellow countrymen"  
2nd line for the operation sequence separated by commas, for e.g "and,or not,not,and not"  
The output will be number of documents retrieved and the number of comparisons done to retrieve the document  

Q2.ipynb (Phrase Retrieval)  
ASSUMPTION : Stopwords are removed, for e.g "Hello for the World" will be treated as "Hello World" phrase  
You can give infinite phrase queries as input here because of infinite while loop  
Each query will just be a string of phrase.  
The output will be number of documents retrieved and the names of those documents  





