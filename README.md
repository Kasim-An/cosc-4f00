# cosc-4f00

Similar-Checking program

This program is made by 5 people, some of us focus on paper work, some of us focus on front interface, for my part is focus on calculate engine. For course requirement we have final version.

The main goal for this program is to compare two code and calculate the similarity between them, however it should consider that if user's input is different type code file for example Java file and compares to C+ file, if the "language" and "grammar" is fitting the same, then it is cheating.

# Situation simulationg

For example, in Java "System.out.println( "Hello, World" );" and in C+ "printf( "Hello, world" );" is in the same "grammar", like in English's and Chinese's. An other example is in same language, in Java if define an array it has at least 2 ways to define, but same result.

# Main Calculation
Cosine-similarity is what i used, for compare two code
