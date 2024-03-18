# Huffman Coding Java Implementation

Osa Idahor

## Overview
This Java application delivers a practical implementation of the Huffman coding algorithm, a widely recognized method for lossless data compression. By dynamically assigning shorter binary codes to more frequently occurring characters, Huffman coding efficiently reduces file size without losing any original data.

## Features
Encoding and Decoding: Transforms plain text into its compact binary representation and vice versa, demonstrating the algorithm's effectiveness in reducing file size.

Frequency Analysis: Analyzes character occurrences to construct a frequency map, laying the groundwork for the encoding process.

File Handling: Seamlessly reads from and writes to files, encapsulating the complexities of file I/O operations, and providing a user-friendly experience.

## How It Works: "abracadabra man" Example
### Input Text: abracadabra man
### Encoding
1. Frequency Analysis: Character frequencies are analyzed. For example, 'a' appears 6 times
2. Encoding to Binary:
   1. The text is encoded into a binary string, with the resulting compression showcased in enc.txt.
   2. Encoded Message (enc.txt): Contains the binary representation of "abracadabra man", such as 0110111010000100101101110 101001011
3. Frequency Map Output:
   1. A frequency map, detailing characters and their frequencies, is saved to freq.txt.
   2. Frequency Map (freq.txt): Lists each character's binary representation and occurrence count.
4. Decode Binary String:
   1. The encoded message is decoded back into the original text, demonstrating the lossless nature of Huffman coding.
   2. Original Text Reconstructed (dec.txt): The decoded file, matching the original input: abracadabra man
  
  ## How to Run
  Compile and run the HuffmanSubmit class, providing the necessary input file paths.
