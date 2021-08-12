# Programming Problems

## There are a lot of mistakes programer  make when solving programming  problem 

1-he want write code as soon as possible

2-is trying to over solve the solution on the first iteration.  Keep it simple, don’t try to get fancy.

##  a simple set of steps to follow which you can use for any algorithm type programming problem.

1-Read the problem completely twice.

2-Solve the problem manually with 3 sets of sample data.

3-Optimize the manual steps.

4-Write the manual steps as comments or pseudo-code.

5-Replace the comments or pseudo-code with real code.

6-Optimize the real code.

**As much as 70% of our time should be spent in steps 1-3.**

don't worry from time you take when understand problem this very important to solve the problem


 everything you want write code to it must write that manually

examples

Let’s look at a very basic example, reversing a string.

If I give you a string “Zebra”, and ask you to reverse it, most people will do the following manual steps.

Write “Zebra” down.

Start a new word, and put “a” as the first letter.  (Why –> because it is the last letter, we want to start here)

Put “r” down as the 2nd letter.  (Why –> because it is the next letter backwards from the last letter we copied)

Put “b” down as the 3rd letter.  (Why –> same as above)
Etc

## Optimize the manual solution

when rearranging or reconstructor the algorithm in your head more easier from write it in the code

Let’s look at our string reversal example and see if we can simplify the steps.

We should be able to immediately recognize that we can use a loop here to reduce the manual steps.  Our duplicate why’s for most of our steps tell us that we are doing the same thing over and over for each step, just with different data.

Write “Zebra” down.

Start at the last letter in the word and create a new empty word.

Append the current letter to the new word

If there is a previous letter, make the previous letter the current letter and start back at 3.

Look how close we are getting to code at this point.  You should be tempted to actually write the code for this.

That is good, it tells you that you have solved and simplified the problem well.  Writing code should now become very easy.

## Write pseudo-code or comments

Many times you can skip this step if you have a really good handle on the problem or your previous steps already created a detailed enough description of the solution that coding it is already a 1 to 1 translation.


What we want to do here is capture all the steps we created and now either put them into our editor as comments or write them as psuedo-code that we can translate to real code.


By doing this, we can know exactly what the structure of the code we are going to write is going to look like which makes the job of filling in the actual code later trivial.

Let’s look at some psudeo-code for reversing a string.

/ NewWord = “”


// Loop backwards through word to reverse


//   NewWord += CurrentLetter

// Return NewWord


## Replace comments with real code

This step should be extremely easy at this point. 
 If you have done all the other steps, this step involves no problem solving at all.

All we do here is take each comment and convert it into a real line of code.

Taking the string reversal, we might end up with something like this.

String newWord =""

for(int index = oldWord.Length – 1; index >= 0; index—)

   newWord += oldWord[index];
return newWord;