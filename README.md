# Boolean Query Processing

This program interacts with an incoming Lucene Index. 
A lucene Index is read and an inverted index is created using Lucene APIs. 
Boolean query results for TAAT and DAAT are returned. 
This is important in terms of Information Retrieval. 
An inverted Index is used to store unique mappings from given content. 
Term-At-A-Time (TAAT) and Document-At-A-Time (DAAT) are Boolean Query Processing techniques that are used to return results when a query is run on the given data.
The project can be run from the command line by giving the following command:
java -jar sumedhas_project2.jar path_of_index output.txt input.txt

input.txt : refers to the input file which contains the query terms.
output.txt : refers to the output file where the results are stored.
path_of_index : a string indicating the path of the given Lucene index

