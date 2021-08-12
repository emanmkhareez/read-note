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

# Act like you make $1000/hr


## We should not spend your time without interest, everyone should decide what you do and how much time it takes to do it



Possibly you feel intimidated by all the programming terms before you even start to learn. Maybe the challenges seem solvable, but you can’t think of a way to solve them due to limited context. Once you start programming, you might spend hours looking for a bug and feel ready to quit. How can you get around these common pitfalls?

1-Be Persistent

The most important thing, whatever your situation, is to be persistent.

In the beginning when you research ways to solve a challenge, push yourself beyond your limit—at least a little bit more than usual. When you feel exhausted, drained, and ready give up, many times that's when you finally figure it out. The moment where most people give up is the moment you need to keep going because this is when you improve. Everything uncomfortable is a gift so we can grow as individuals and strengthen our character.

The first few months are the most difficult. Don’t worry; I can tell you from experience it gets better. The hard work you put into it matters. I guarantee you’ll improve as time goes by.

2-Remember Your Goals

Another way to push yourself forward is to remember your goals. Why do you want to learn to code? Keep a list of your goals on your computer, in a notebook, or stuck to your wall. I like to make lists of my goals, then remind myself of them every morning. That sets my intention for the day and helps me focus on accomplishing them.

# 5 Whys

 5 Whys technique (sometimes known as 5Y). This is a simple but powerful tool for cutting quickly through the outward symptoms of a problem to reveal its underlying causes, so that you can deal with it once and for all.

 The 5 Whys uses "counter-measures," rather than "solutions." A counter-measure is an action or set of actions that seeks to prevent the problem from arising again, while a solution may just seek to deal with the symptom. As such, counter-measures are more robust, and will more likely prevent the problem from recurring.

## How to Use the 5 Whys

1- Assemble a Team

ther together people who are familiar with the specifics of the problem, and with the process that you're trying to fix. Include someone to act as a facilitator , who can keep the team focused on identifying effective counter-measures.


2-Define the Problem

If you can, observe the problem in action. Discuss it with your team and write a brief, clear problem statement that you all agree on. 

3- Ask the First "Why?


Asking "Why?" sounds simple, but answering it requires serious thought. Search for answers that are grounded in fact: they must be accounts of things that have actually happened, not guesses at what might have happened.

This prevents 5 Whys from becoming just a process of deductive reasoning, which can generate a large number of possible causes and, sometimes, create more confusion as you chase down hypothetical problems.

4-Ask "Why?" Four More Times

Try to move quickly from one question to the next, so that you have the full picture before you jump to any conclusions.