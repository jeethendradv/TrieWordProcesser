I have implemented the Trie datastructure to search a word from list of words. 
We first read the file with list of words then sort it and insert the list to the Trie datastructure. The trie datastructure 
will create a tree using each word in the list. 
For each word in the list we are creating the Word object, The word object internally creates list of all possible words for 
a word, For example for a word "catrat" the word object will split the word into below word:

ca
cat
catr
catra
at
atr
atra
atrat
tr
tra
trat
ra
rat
at

Now each of the word from the above list will be search in Trie datastructure and added to the buffer. From the buffer list 
we look for words that will make up the full word.