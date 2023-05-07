Download Link: https://assignmentchef.com/product/solved-homework-5
<br>
In this homework, you will be writing a short program in Python to find duplicate words in a file.This assignment focuses on Chapter 5, specifically reading data from a file.

Program(Features(A common mistake when writing is duplicating a word (“the the”). This is a big enough problemthat Microsoft Word and other text editing software will mark these mistakes as errors. In thisassignment, we will develop a short Python program that will find these duplicate words and alertthe user by printing out a simple message. I suggest using a for loop to read the file data line by line.Once you have a line you will need to perform further string manipulations to determine if there s aduplicate word.

Given the following (slightly mangled) text stored inside of quote.txt:

He that would make his own liberty liberty secure,must guard even his enemy from oppression;for for if he violates this duty, hehe establishes a precedent that will reach to himself.— Thomas Paine

Running your program would produce the following output (user input is green):

Enter file name: quote.txtFound word: “liberty” on line 1.Found word: “for” on line 3.Found word: “he” on line 4.

As shown above, your program should also be able to find duplicate words across(lines in the inputfile.

Helpful(Hints(We haven t gotten to lists yet, but we can make use of one for this assignment without knowing allthe details. Here s an example of how to get all of the words in a line and turn them into separatestrings:

line = “This is a line from a file”words = line.split() # We saw split() in Chapter 4. It will break up# our string into just the words (no whitespace)# and maintain the order. So the variable words# contains “This”, “is”, “a” “line”, “from”,# “a”, and “file”.# To access those individual words (separate strings) use a for loop:for word in words:print(word)

Each iteration of the for loop will print out a word. The variable word becomes “This”, then “is”and so on, until all of the words have been printed. The result of the loop is shown below:Thisisalinefromafile(What(to(SubmitFor this assignment you should submit your hw5.py file.