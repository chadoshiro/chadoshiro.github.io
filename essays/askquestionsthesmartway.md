---
layout: essay
type: essay
title: Ask Questions The Smart Way
# All dates must be YYYY-MM-DD format!
date: 2020-01-28
labels:
  - Software Engineering 
  - Learning
  - Smart Questions
---

<img class="ui medium right floated rounded image" src="../images/huh.png">

Asking questions can be a very daunting task. You don’t know if you are asking the right question or even going to get a response. Maybe you don’t want to be a distraction or burden to one of your co-workers for constantly asking them for help. In this field of work though, it is important to be able to ask questions, especially when you have been stuck for a while on the same problem. Asking a “loser” question like “Is this right?” might not give you the answer you were looking for. Instead, asking a “smart” question could give you the answer that you were trying to figure out. This is a great way to not only get an answer back fast and correct, but it helps you to understand how to ask questions in the future that will help you get the answers you are seeking. Image retrieved [here](https://www.kindpng.com/imgv/hxhJxhm_ink-question-mark-zen-ish-calligraphy-hd-png/).

## "Smart" Questions
Asking a smart question may take a while to write up, but it will be the best chance for you to get a response that is clear and helpful. Before asking a question, you have to make sure that you have done a few things before even thinking about asking. Like Raymond said in his essay, you should at least try to find the answer by searching it up on the internet, reading the manual or a FAQ, or even asking a friend that is skilled at coding. Here is an example of a ["smart" question](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array).

```
Q: Why is processing a sorted array faster than processing an unsorted array?

int main()
{
    // Generate data
    const unsigned arraySize = 32768;
    int data[arraySize];

    for (unsigned c = 0; c < arraySize; ++c)
        data[c] = std::rand() % 256;

    // !!! With this, the next loop runs faster.
    std::sort(data, data + arraySize);
...
    
My first thought was that sorting brings the data into the cache, but then I thought how silly that was because the array was just generated.

What is going on?
Why is processing a sorted array faster than processing an unsorted array?

```
In this example, you can see that this person actually wanted to learn and also tried to figure out the answer before asking the question right away. They put code in their question and talked about how they tried it in C++ and Java to try to see if it would be faster or not. This shows that they actually tried to figure out what was going on and didn’t ask a question online right away. Also it was great of them to ask the two questions at the end. It shows that they are willing to learn from it and grow as a coder. This was a great example of a “smart” question and you know it because there are a ton of answers from advanced coders and there are also 25225 upvotes.

## "Loser" Questions
On the other hand, asking a “loser” question won’t give you the answer that you are looking for. In fact, you might not get an answer at all. It could just irritate and annoy the people that are trying to help you. A “loser” question could be just a broad question that has no background to the situation, which will result in not getting the right answer. It could also be where you immediately ask how to solve the problem without showing that you’ve actually tried solving the problem and finding the solution elsewhere. Remember that these people aren’t obligated to give you an answer. Out of their own kindness, they help people who need it. By asking “loser” questions you are showing them that you aren't worth helping. Here is an example of a ["loser" question](https://stackoverflow.com/questions/65948921/is-this-an-infinite-loop-beginner-level).

```
Q: Is this an infinite loop? beginner level

let I = 3;
while (i) {
  alert(I--);
}

Javascript the question asked what is the last value alerted by this code? and it shows the answer of 1. But I believe this is an infinite loop, and tested in console, resulting in laptop burning, had to shut down browser. Am I wrong or the solution was wrong? Thanks
```
This is a perfect example of what not to do. First off his question is if he was wrong or if the solution was wrong. This shows that he doesn’t care about understanding why he was either right or wrong. He just wants the answer and nothing else. Also he doesn’t show that he tried to find the answer somewhere else like asking a friend or searching it up on the internet. These experts aren’t going to want to answer your question if you don’t really want to learn from it. This is why at the time I am writing this there are no answers and there is also one downvote. 

## My Takeaways 
As a “newbie” in this field of work, it can be very daunting to ask for help. You might overthink what you want to ask and not think that it’s valid because you might think that it’s a bad question. Even if it’s a simple question that has a simple answer, if you put in the work to get the right answer and it shows when you ask for help online, people will be willing to help you. It shows them that you are dedicated and willing to learn and grow as a coder. Not putting in that extra bit of effort won’t get you far. At most, you’ll get an answer that won’t help you at all. You won’t be able to grow and improve your skills and you’ll just be wasting people’s time with your bad questions. It’s not hard to try and find the answer on your own, but if you are stuck and have tried everything then take the time to think about what you need to know and figure out. It doesn’t hurt to ask questions the smart way.


