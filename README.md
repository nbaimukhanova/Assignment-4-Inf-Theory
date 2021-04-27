# Assignment-4-Inf-Theory
Input: a sequence of binary digits from Part 2.

Goal: Decode back into text the result binary sequence after Part2 (Shannon-Fano or Huffman
code).

Output: a text identical to an initial text from “Text.txt” file.

1. Read the file with the sequence of bits from the previous assignment. 

2. Use a Huffman tree to decode text that was previously encoded. The
decoding algorithm is to read each bit from the bit string, one at a time, and use this bit to
traverse the tree. In order to decode a bit string, you'll need to iterate through each bit, and use
whether that is a 0 or a 1 to "traverse" down a branch (a subtree) of the 
Huffman tree. Once you hit a leaf, you can add the letter contained in that leaf to your output
String. Using the Huffman tree, we walk from the root until we find
characters, then output them and go back to the root.

3. Print out the text you got from the previous step. The text should be identical to an initial
text from “Text.txt” file. Print out both of them. 
