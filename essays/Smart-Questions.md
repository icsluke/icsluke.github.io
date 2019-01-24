---
layout: essay
type: essay
title: Studying to Know the Question
# All dates must be YYYY-MM-DD format!
date: 2019-01-24
labels:
  - Stack Overflow
  - Smart Questions
  - Learning
---

For years I have laughed at silly questions and answers people ask over the internet. My favorite one is "Am I pregant?" Whether it is the internet or real life, we all ask questions like "Am i pegnent? Help!!" Stress, urgency, and plain ignorance may lead us to ask a question that may be worded wrong or have easy to find answers. Learning to understand how to ask a question and understand why people may give you the answer they say. This is true in life and in software engineering. Learning to ask a smart question leads you to a quick and detailed answer that will help you through the various coding and formatting problems throughout our careers.

### "Are bytes real?"
We all can say bytes are real because we learned about them through various ICS courses, many scientists confirmed the existence of the byte through studies, and we have created bytes through our programs and were able to see them through an interface. This user on stack overflow questioned if bytes are real saying:

> *"Everyone knows that byte is 8 bits... But where exactly is it specified? I mean, phisically you don't really use bytes, but bits."*

To ask a good question we should always google it first. This person should have googled the history of the byte and read up from various computer science sources about the how the byte was created and used. If he doesn't google about the byte or read up on technical manuals or papers, he can search other forums for posts with the same question and answer. The people who did answer this question with very snarky answers. One guy said :

> *Why do we humans count in base 10? Is 10 any more real than base 2, or base 16? If we only had 8 digits on our hands, would we count in base 8? What is the definition of anything? Who says how long a metre is? –*

We see how asking slightly vague and easy to answer questions are answered with vague and smart alek answers.

### Effective questions produce insightful answers
Throughout my life I learned that asking thoughtful questions evokes a better reaction from others as they would be required to think harder and smarter, thus giving you a more knowledgable and thorough answer. Looking through stack overflow I found a post about someone asking about pyspark. He asked:

> *Multiple pyspark “window()” calls shows error when doing a “groupBy()”*
> (A few lines of codes of the situation)... *The error is: "Multiple time window expressions would result in a cartesian product of rows, therefore they are currently not supported." Is there some way to achieve the desired behavior?*

The people who are brief and detailed in their question and problem will be greeted with much better answers, as he was specfic about his error, and how he asked the question evokes thoughtful thinking for answers. Other users commented their answers with one of them giving a hint that is technical enough toward what should be achieved: 

> *"Your code is not creating sub-windows; it's creating a cross product of 12 sec windows with 2 sec windows. The typical pattern for addressing your problem is to build the lowest granularity window (2secs) and then aggregate up."*

Another answer given showed a solution with code and a brief but detailed explanation on how to achieve the desired results. 

> *...This solution only works if there is at most one call to window, meaning multiple time windows are not allowed. Doing a quick search on the spark github shows there's a hard limit of <= 1 windows..."*

The user who gave this answer was very thoughtful and made it easy to understand with a summary and code, so even if you were clueless in the beginning, you can at least follow along and understand why the answer he got is the way it is.

I hope that all software engineers and people of the world learn to ask smart questions as it doesn't waste your time or the person who is answerings' time. You also can learn many insightful things trying to find the answer for yourself before formulating a question. It's the journey, not the destination to the answer.


