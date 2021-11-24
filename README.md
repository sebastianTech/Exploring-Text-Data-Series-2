# Exploring-Text-Data-Series-2
Exploring Text data (Series 2)

In series 1, we look at the introduction of text data and the link with NLP. Some basic terms were introduced and concluded in implementing essential exploration to text data and word cloud. Text mining and data mining are two different concepts; however, there are slight differences. Text mining is the application of statistical tools to derive intelligence or analyse text data.   
![image](https://user-images.githubusercontent.com/66043834/135930398-e91f2460-2a93-4061-8364-bf37c70ae130.png)


In deriving intelligence, the unstructured text data need to go through some process to enable statistical algorithms to discover the relationship, patterns that will be informative-the accurate picture of big data. The first process is information retrieval. It can be in the form of keywords, term associations to identify the relevant document from a pool of digital text documents. An example is the web search or library catalog search, to search a piece of information.


The phase is for the computer to understand the strings and process them. Considering the ambiguity of human language and the fact that computer is garbage in and out, the outcome of Natural language processing may not be accurate. These challenges have led to the great success of classifying words into grammatic structures. The grammatic analysis gives an in-depth meaning to its representation, not just the elements in the sentences. At this stage, as shown in fig (), the linguistic side comes into view. Altogether the data is unstructured. Series 3 will cover the introduction to the NLTK Package, parts of speech tagging, and Parsing.
The third process is information extraction. The data needs to be structured and generated by the NLP system. At this stage, identification of specific terms through the concept of name entity, tokenisation, lemmatisation, stemming, and other concepts. All the concepts mentioned will be covered in series four, and that series four will come with some statistical concepts. In situations where a feature set may have a categorical feature that involves a level of pre-processing, the pre-processing is done in NLP often more involved than simply converting a categorical feature using label encoding, and the principle is the same. In NLP, the task is to represent individual observations of texts as a row and encode a static number of features, represented as columns, across all observations. As such, information extraction becomes the most critical aspect of text pre-processing.
The last process is "Data mining." The structured form of the text data is ready for insight. Almost every field requires texting mining, and the four processes are how machine learning learns from text data. Text mining can be predictive mining or descriptive mining, and its application is across different industries.
Here is a scenario: Given a task of text mining clinical data and at the point of exploring the data and discovered double words: 
"The patient has signs of tuberculosis in his left lung; let us try a new treatment with x-ray Isomaliazid, 400mgmg/ dayaya."
It could be tweet data:
"@..... was in herbernationmode when GPS enabled 2000rs was launched #mode 4."

These are the real problem in text mining and needs to be solved. It is good to know that one can use many programming languages to solve it, but such a task becomes easy to solve with regular expression.
In dealing with text data by default unstructured, a regular expression is a tool that comes in handy in finding information and patterns in text data. A regular expression or" regex" is a pattern of special characters or search pattern to match one or more characters. It can be a string "so," which would match strings containing the "so," for example, "Sophisticated," interpersonal," have an associated textual meaning and equally called a wild card expression. Writing a rule-based information mining system in NLP becomes possible. It is also good in segmenting words from sentences or paragraphs.
It can be a good tool in removing noise, as cited in the scenarios. The different syntax for regular expression exists (Syntax for Regular
expression). This series covers "Regular functions" available in the "re" python library and how to use it. The first function is:

Match: is for finding the first word in a sentence.
![image](https://user-images.githubusercontent.com/66043834/135930490-5d240209-fe75-4989-af45-88f5f08ecdad.png)

If a search for the string "Patient" with Match function, it will come back with "None" because the match function searches for the first string in text data. If we want to search for another word in the text data, we use a function called:
Search: locates pattern in the strings. This function goes through the text to discover the word "patient." 
![image](https://user-images.githubusercontent.com/66043834/135930538-8595e9ca-7d53-4800-b79a-49dfc7c5d968.png)

Assuming we have more than a word in a sentence, we use a function called:
Findall: It will list all the occurrences of the string. Attempting to find out the exact index where these strings require another function:
![image](https://user-images.githubusercontent.com/66043834/135930579-ddb94376-32fa-4562-ad75-1900d2c26f81.png)

 
finditer” is the function to use, however, with a for loop.

 ![image](https://user-images.githubusercontent.com/66043834/135930604-c97cf4c4-47ec-4153-970f-34e03e16d6f5.png)
 
If we want to replace a string with another string in text data, we can use a function called:
Sub: search and replaces.

Our text data is: "The patient has signs of tuberculosis in his left lungs, although his right lung is free; let's try a new treatment with x-ray Isomaliazid, 400mg/ day” I am going to replace 400 mg with 500mg.
 ![image](https://user-images.githubusercontent.com/66043834/135930623-c822f442-0250-4bba-a468-e1526368fe42.png)


 Conclusion
Knowing how to use regular expression is a good technique in exploring text data. It is a powerful search and string matching technique to make an exact match on text, words, characters, numerical expression, and non-alphanumeric expression. Application of regular function on tweet data will be uploaded on Github.  
