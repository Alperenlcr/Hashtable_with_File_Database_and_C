# Hashtable_with_File_Database_and_C

Problem : Reading file
Solution : Program dynamically by reads character by character and separating my keys and values ​​from spaces and enters.

Problem : Finding Hash Table size
Solution: I found the number of Keys in the file just from the number of spaces and enters. Then I created a dynamic array with the number. And filled the keys array.
Since it will be Linear probing, I need the number of different keys. I found them by sorting them and then increasing the count to see if they are the same as binary.
The duos I've been looking at go from the beginning to the end of the series.

Problem: Understanding and answering queries
Solution: I separated the keywords in the queries. According to the 've', 'veya' in the query, I made intersection or union in values ​​arrays.

This project includes many more sub-problems. I have mentioned a few of the important ones above.

Hash Table features:
It is created by linear probing. Indices are determined by Horner's rule. The load factor entered by user. I use; Index calculation with insert, search, init, horner, primality
control, load factor and size finder functions.


&nbsp;
# Project Explanation
There is a pdf in repo that explains what is done.

Also a video link that I explained code:

https://www.youtube.com/watch?v=YNBElm4O1qo&t=1s