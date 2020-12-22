---
layout: post
title:  "How to Get Out of 101 Purgatory"
date:   2020-10-25 10:07:14 +0000
categories: Launch School
---
*A Guide to Launch School's Written Assessment (Unabridged Version)*

Dear fellow Launch School-ers,

Let me assuage your fears around escaping purgatory (read: RB109) by instructing you how to ascend to the pearlescent gates of heav- er, RB120...

In all seriousness, I wanted to capture my experience preparing for and taking the RB109 written assessment because the approach I took feels like a conglomeration of strategies I gleaned from other Launch School students. I'm expecting that your blog posts upon passing RB109 will be a more refined reincarnation of past reflections on the topic. Spiritual references aside, it can feel discouraging to spend weeks in 109 and having a specific plan in place can help to concretize the process.

*If you're not looking for this level of detail about the RB109 written assessment (1765 words, to be exact), check out the abridged version of this post here, where I've condensed it down to just the checklist and some pointers.*

I've divided up this reflection into four main areas:

1. **Exam Content** - Additional details on the structure of the exam
2. **Logistics** - How to navigate the exam and manage your time
3. **Preparation** - How and what I studied
4. **Looking Ahead** - Lessons learned from the process of preparing for the exam and plans for retaining knowledge

*Exam Content*
- The exam was 21 questions long. I've heard it can vary from 20 - 23 questions, so be prepared for this. Questions varied in length, but most were just a few lines of code and on par with the code examples shown throughout the RB101 course (see [Christian Larwood's study guide](https://docs.google.com/document/d/16XteFXEm3lFbcavrXDZs45rNEc1iBxSYC8e4pLhT0Rw/edit?usp=sharing) for a compilation of code examples shown throughout the course and in various related blog posts).
- There are a handful of questions that ask you to thoroughly explain every line of code, but most questions will reference specific lines and/or provide what the code outputs and ask you to explain why the code returns and/or outputs what it does. Most of the time you will not need to write out a full explanation of each line of code for every problem. It's more important to be able to succinctly explain the underlying concept and use certain lines to demonstrate how the concept works.
- Questions are grouped by topic (e.g., local variables, collections, etc.). I started in the middle of the exam with "collections" since this seemed like the longest portion and potentially the most challenging (i.e., would take the most brain power). I think this ended up being a good strategy and this left easier questions toward the end.

*Logistics*
- You have 3 hours to complete the exam without being penalized. It took me 2 hrs 25 mins to write clear, complete answers to all 21 questions. I think I could've completed the exam in 2 hours if I had answered all questions without stopping to think about the exact phrasing I wanted to use and then circling back to "refactor" my responses in the remaining hour. Looking back, I am satisfied with the approach that I took and I still had 35 minutes to read through my work and check for formatting errors, etc. I submitted with 2 minutes remaining and I think it is generally a good strategy to use most of the allotted time.
- I set an overall timer for 2 hours and 40 minutes (to allow for 15-20 minutes of review at the end) with 40 minute interval timers (to confirm that I had completed at least 5 problems after each interval). I also wrote down the time that I started the exam, though this is visible to you at any time at the top of the assessment page. Remember, there are no timers built-in to the exam; you will **not** get a notification when you are nearing the end of the exam or when you've reached the end of the three hour window. It's up to you to keep track of your time!
- I kept track of the questions I answered fully on paper and made note of any I wanted to return to if I wasn't 100% satisfied with my initial answer. This was very helpful and gave me a good sense of how much of the exam I had completed as I was working through it.
- I was planning on writing my answers in Notion and then copying them over to the exam, because I had practiced using markdown in Notion. However, when I tried this on the first question I answered, the markdown syntax did not copy over. So I typed up my responses in the answer boxes on the exam using markdown syntax and then copied the answer over into Notion as a backup. This isn't entirely necessary, as you can save your response to any question in the exam at any point.
- Once you submit the exam, the questions and your responses are saved and available for you to review at any time. Launch School staff are excellent about grading your assessment within 24 hours of your submission.

*Preparation*
- I spent two 25-27 hour weeks preparing for the written assessment. I felt like I had seen a lot of the technically precise language throughout 101, but I didn't spend any time using this language (especially not in written form) until I reached 109. I also didn't regularly study with others until 109, so I think all of these factors contributed to why I spent more time than I would've liked studying for the written assessment.
- I created a master checklist of everything I wanted to complete before taking the written assessment and then revisited it daily, using it as a guide for what I spent time on by creating a "mini" task list for that day.
    - [ ]  Re-read through all links in the study guide.
        - Take notes while reading and/or review previous notes on the topic.
        - Make note of topics to review and any outstanding questions.
    - [ ]  Create a repository of relevant code snippets (from RB101 content & quizzes, related blog posts, study sessions, etc.).[^bignote]
    - [ ]  Make a list of common phrases used to describe code/concepts.[^bignote] e.g.,
        - On `line n`, local variable `var_name` is initialized to a [String] object `value`.
        - On `line n`,  the `method_name` method  is called and and the local variable `var_name`(which references an [Integer] object with a value of `value`) is passed to it as an argument.
    - [ ]  Take notes on the "Specific Topics of Interest" listed in the study guide.
        - Pay particular attention to `each`, `map`, `select`
            - Have exact definitions for each method in your own words.
            - Understand what they do for different types of collections (e.g., Hash vs. Array).
        - Pay particular attention to `Array#sort`.
        - Re-read through the documentation for other useful collection methods (see [RB101 Lesson 4: Ruby Collections - More Methods](https://launchschool.com/lessons/85376b6d/assignments/d86be6b5)).
    - [ ]  Keep track of all your questions and make sure you get answers to them (from other students, TAs, your own research, etc.).
    - [ ]  Go through all of the examples in Christian Larwood's written assessment study guide.
        - Write down timed solutions for each.
        - Practice using pre-fabricated lines of code.
        - Refactor answers and save commonly used phrases in personal repository.
    - [ ]  Create a high-level strategy for answering each question.[^bignote]
    - [ ]  Make note of useful markdown syntax and practice using it. [^bignote]

[^bignote]: I created a lengthy repository of code snippets from as many Launch School-specific sources as possible, but again Christian's study guide is comprehensive so this step isn't really necessary.

[^bignote]: I did attempt to use the pre-fabricated phrases in practice, but quickly found it to be too cumbersome deal with copying and pasting and then overwriting certain words. Since this didn't work for me in practice, I didn't implement this strategy on the exam. However, it was probably the most useful exercise I underwent to prepare for the exam. It helped me to notice recurring patterns as I was studying and to have these phrases etched into my mind prior to the exam.

[^bignote]: My high-level strategy for approaching each problem looked like this:

Strategy for Each Question

1. **Read** through the code & understand what it does.
2. **Run** the code. Does it produce the results you think it does?
3. **Answer** the questions asked and explain why.
    1. Point to specific lines that support your answer to the question(s). You do not have to explain all lines of code, only the relevant ones.
    2. Be precise & concise.
    3. Demonstrate that you understand what is happening and the underlying concept.
4. **Save** a copy of the answer offline (in Notion).
5. **Track** status of answer on paper.
    - Complete (check mark)
    - Partial (~)
    - Skipped (circle question number)

I practiced this strategy prior to the exam and generally stuck with it on the exam, though I didn't find the need to test the code snippets in IRB.

 [^bignote]: The formatting and markdown syntax that I learned and implemented on the exam is as follows:

- (` `) backticks to indicate line numbers, variable names, method names, etc.

    e.g., `var_name`

- (** **) double asterisks to bold important words

    e.g., **variable shadowing**

- (* *) single asterisks to italicize words/phrases for additional emphasis

    e.g., *evaluates to true*

- Add an empty line between paragraphs to visually create separation.

Again, not really necessary, but it helped to me to visually confirm I was hitting the points I wanted to make and hopefully made the answers more pleasurable to grade.

- In addition to attending two TA-led study sessions and a handful of group study sessions, I exchanged code snippets with a few students on Slack, responding to them when I could. Occasionally this would lead me down a rabbit-hole, but for the most part, it was really helpful to receive feedback from others and it kept me actively practicing. The examples that you receive from the TAs are indicative of the types of questions you will receive on the exam.
- In some of my one-on-one study sessions with another student, we would dedicate an hour to one or two short examples, first trying to come up with our own solutions, then providing feedback on each other's solution, and finally spending time rewording our individual solutions to be as precise as possible. This was also incredibly useful; I think instead of doing a mix of timed problems and untimed problems, I would've spent more time upfront not timing myself on problems to get the syntax right and to extract commonly used phrases from those practice sessions and then being stricter about timing myself.

*Looking Ahead*
- I spent two 25-27 hour weeks preparing for the written assessment. I felt like I had seen a lot of the technically precise language throughout 101, but I didn't spend any time using this language (especially not in written form) until I reached 109. I also didn't regularly study with others until 109, so I think all of these factors contributed to why I spent more time than I would've liked studying for the written assessment.
- I created a master checklist of everything I wanted to complete before taking the written assessment and then revisited it daily, using it as a guide for what I spent time on by creating a "mini" task list for that day.
  *Master Checklist*
    - [ ]  Re-read through all links in the study guide.
        - Take notes while reading and/or review previous notes on the topic.
        - Make note of topics to review and any outstanding questions.
    - [ ]  Create a repository of relevant code snippets (from RB101 content & quizzes, related blog posts, study sessions, etc.).[^bignote]
    - [ ]  Make a list of common phrases used to describe code/concepts.[^bignote] e.g.,
        - On `line n`, local variable `var_name` is initialized to a [String] object `value`.
        - On `line n`,  the `method_name` method  is called and and the local variable `var_name`(which references an [Integer] object with a value of `value`) is passed to it as an argument.
    - [ ]  Take notes on the "Specific Topics of Interest" listed in the study guide.
        - Pay particular attention to `each`, `map`, `select`
            - Have exact definitions for each method in your own words.
            - Understand what they do for different types of collections (e.g., Hash vs. Array).
        - Pay particular attention to `Array#sort`.
        - Re-read through the documentation for other useful collection methods (see [RB101 Lesson 4: Ruby Collections - More Methods](https://launchschool.com/lessons/85376b6d/assignments/d86be6b5)).
    - [ ]  Keep track of all your questions and make sure you get answers to them (from other students, TAs, your own research, etc.).
    - [ ]  Go through all of the examples in Christian Larwood's written assessment study guide.
        - Write down timed solutions for each.
        - Practice using pre-fabricated lines of code.
        - Refactor answers and save commonly used phrases in personal repository.
    - [ ]  Create a high-level strategy for answering each question.[^bignote]
    - [ ]  Make note of useful markdown syntax and practice using it. [^bignote]

[^bignote]: I created a lengthy repository of code snippets from as many Launch School-specific sources as possible, but again Christian's study guide is comprehensive so this step isn't really necessary.

[^bignote]: I did attempt to use the pre-fabricated phrases in practice, but quickly found it to be too cumbersome deal with copying and pasting and then overwriting certain words. Since this didn't work for me in practice, I didn't implement this strategy on the exam. However, it was probably the most useful exercise I underwent to prepare for the exam. It helped me to notice recurring patterns as I was studying and to have these phrases etched into my mind prior to the exam.

[^bignote]: My high-level strategy for approaching each problem looked like this:

Strategy for Each Question

1. **Read** through the code & understand what it does.
2. **Run** the code. Does it produce the results you think it does?
3. **Answer** the questions asked and explain why.
    1. Point to specific lines that support your answer to the question(s). You do not have to explain all lines of code, only the relevant ones.
    2. Be precise & concise.
    3. Demonstrate that you understand what is happening and the underlying concept.
4. **Save** a copy of the answer offline (in Notion).
5. **Track** status of answer on paper.
    - Complete (check mark)
    - Partial (~)
    - Skipped (circle question number)

I practiced this strategy prior to the exam and generally stuck with it on the exam, though I didn't find the need to test the code snippets in IRB.

 [^bignote]: The formatting and markdown syntax that I learned and implemented on the exam is as follows:

- (` `) backticks to indicate line numbers, variable names, method names, etc.

    e.g., `var_name`

- (** **) double asterisks to bold important words

    e.g., **variable shadowing**

- (* *) single asterisks to italicize words/phrases for additional emphasis

    e.g., *evaluates to true*

- Add an empty line between paragraphs to visually create separation.

Again, not really necessary, but it helped to me to visually confirm I was hitting the points I wanted to make and hopefully made the answers more pleasurable to grade.

- In addition to attending two TA-led study sessions and a handful of group study sessions, I exchanged code snippets with a few students on Slack, responding to them when I could. Occasionally this would lead me down a rabbit-hole, but for the most part, it was really helpful to receive feedback from others and it kept me actively practicing. The examples that you receive from the TAs are indicative of the types of questions you will receive on the exam.
- In some of my one-on-one study sessions with another student, we would dedicate an hour to one or two short examples, first trying to come up with our own solutions, then providing feedback on each other's solution, and finally spending time rewording our individual solutions to be as precise as possible. This was also incredibly useful; I think instead of doing a mix of timed problems and untimed problems, I would've spent more time upfront not timing myself on problems to get the syntax right and to extract commonly used phrases from those practice sessions and then being stricter about timing myself.

*Looking Ahead*

- Be deliberate about using technically precise terminology as you progress through course content. Whether you're thinking about a concept in your head or verbalizing it by yourself or with others, pay attention to the words you use. This will likely save you some study time when you reach the assessment portion of the course.
- Study with others regularly, regardless of where you are in the curriculum. Do not underestimate what you can gain from learning together. Often times questions will arise during study sessions that may not have previously crossed your mind, and developing your own answers to these questions will solidify your knowledge of the concept.
- Continue to maintain and expand upon your current knowledge of key concepts. Establish weekly study sessions with others, practice coding challenges on a regular basis, and consider teaching what you've learned to those who are progressing through RB101.

Though I would suggest focusing your efforts on one assessment at a time, I wouldn't completely abandon solving RB101-109 small problems, katas on Codewars, or any other strategies that you've implemented and are working for you as you study for the written assessment.

Good luck, happy studying, and stay tuned for a follow-up guide to the interview assessment.