# problemsgma
Anu was given an assignment by her teacher. The teacher gave her a set of sentences and asked her to find the number of vowels and consonants in each sentence. Anu was confused about finding the number of vowels and consonants. Develop a coding to help her to sort out the assignment given to her by the teacher.
Note:
Ignore spaces in the sentence.

Input Description:

The first line consists of the number of sentences. The following n lines consist of the sentences.

Output Description: 

Display the number of vowels and consonants appearing in each sentence in each line separated by a space.

Hints:

Using Iteration, traverse each string and find the number of vowels and consonants. Note: Ignore spaces in the sentence.

Sample Input:

3\n
How many vowels in this String\n
Sarah and Jessie are going Shopping\n
The frog jumped and landed in the pond

Sample Output:

7 18\n
12 18\n
10 21

Explanation:

As in the first sentence, there are 7 vowels and 24 consonants, the output is 7 24. The remaining sentence outputs follow.

Testcase 1:

Input:

2\n
When you are trying to understand a sentence break it into smaller pieces\n
My mom cooked pancakes for breakfast

Output:

24 37\n
11 20


Testcase 2:

Input:

3\n
A sentence is a group of words put together in a complete\n
The big dog went to the county fair\n
A clause is a set of words containing a subject and a predicate

Output:

19 27\n
10 18\n
22 29

Testcase 3:

Input:

1\n
The fox really liked pancakes and he ate them every day for breakfast 

Output:

21 36

Testcase 4:

Input:

4\n
We can break up into sentences by separating the main ideas\n
She completed her literature review, and she created her reference list\n
The punctuation can be as important as the words you use\n
A complex sentence contains at least one independent and at least one dependent clause


Output:

20 29\n
24 37\n
19 27\n
30 43

Testcase 5:

Input:

8\n
Readers expect what they already know to be at the beginning of a sentence\n
Effective writers use a variety of types of sentences\n
If thought corrupts language, language can also corrupt thought\n
Make your sentences more interesting by having some sentences which are very short\n
Effective sentences are careful to use the right conjunction\n
The goal of an argumentative essay is to convince readers\n
Compare and contrast essays examine similarities and differences\n
The chief ingredients of a good essay include not only the content and your arguments

Output:

23 38\n
18 27\n
20 35\n
25 4\n
21 31\n
21 27\n
23 34\n
27 44
