# cosc-4f00

Similar-Checking program

This program is made by 5 people, some of us focus on paper work, some of us focus on front interface, for my part is focus on calculate engine. For course requirement we have final version.

The main goal for this program is to compare two code and calculate the similarity between them, however it should consider that if user's input is different type code file for example Java file and compares to C+ file, if the "language" and "grammar" is fitting the same, then it is cheating.

# Situation simulationg

For example, in Java "System.out.println( "Hello, World" );" and in C+ "printf( "Hello, world" );" is in the same "grammar", like in English's and Chinese's. An other example is in same language, in Java if define an array it has at least 2 ways to define, but same result.

# Main Calculation
Cosine-similarity is what i used, for compare two code like document, each line should be consider similarity, and for lines, each word using is the main consider point. Trade whole line as a string and seperate parts into array, it called N-grams.

<div><img src="https://github.com/Kasim-An/cosc-4f00/blob/master/cosine-similarity.png"></div>

By using cosine-similarity, it compares 2 vector's difference, so convert whole line as string, and seperate in small groups.
For example,"This is a string." can be convert in 2-grams [Th][hi][is][s ][ i][is] and so on. If the grams comes to 3-grams [Thi][his][is ][s a] will be totally different similarity.
<div><img src="https://github.com/Kasim-An/cosc-4f00/blob/master/1.png"></div>
<div><img src="https://github.com/Kasim-An/cosc-4f00/blob/master/2.png"></div>
<div><img src="https://github.com/Kasim-An/cosc-4f00/blob/master/3.png"></div>
<div><img src="https://github.com/Kasim-An/cosc-4f00/blob/master/4.png"></div>
