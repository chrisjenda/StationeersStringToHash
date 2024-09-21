# StationeersStringToHash
Script to Convert an Array of Ascii Strings plus Concatenate an Integer to the end in IC10 Basic

- StringToHash_Basic: This is the Main Script (Hash Generator), this Version uses the Memory to store the CRC32 Table rather than the Stack which may be better or worse depending on the final implementation.  NOTE: This File contains the Uncompiled Basic Version (NOT the IC10 Code)
  
- StringToHash_IC10: Same as the Basic, but Compiled in IC10 Format.  NOTE: the After Compile Changes that are in the instructions within the Basic version have already been applied, Just Flash and Enjoy.

- StringToHashTest_Basic: This Script is used to Showcase the Abilities of the Hash Generator Script,  It also has the ability to test that the Results are in fact valid String Hashes.  NOTE: This File contains the Uncompiled Basic Version (NOT the IC10 Code)

- StringToHashTest_Basic: Same as the Basic, but Compiled in IC10 Format.

- Make sure to Read Each Scripts Comments, there are more comments in the Basic Version, but Important Comments persist into the IC10 code.

- The Hardware Setup Consists of 2 IC Housings, 2 IC Chips, 2 Optional LED Small Displays, Consult the Picture Below (Ignore the Stopwatch)

![image](https://github.com/user-attachments/assets/37f7f42e-0ef5-4883-9d89-58970f8c5db5)

