
## Overview
This course introduces the design of intelligent agents, including the fundamental problem-solving and knowledge-representation paradigms of artificial intelligence. Topics to be covered include the AI programming language LISP, state-space and problem reduction methods, brute-force and heuristic search, two-player games, and recent developments in game AI. For knowledge representation and reasoning, we will cover propositional and first-order logic and their inference algorithms. Finally, the course covers probabilistic approaches to AI, such as Bayesian networks to improve the agent’s performance with experience.

### Prerequisites
This course requires knowledge of basic computer science, algorithms and complexity (CS180), and programming principles.
### Textbook

Stuart Russell and Peter Norvig. Artificial Intelligence: A Modern Approach. (3rd Edition), Pearson 2009.

### Programming Language
LISP

## Logistics
<!--University of California, Los Angeles  -->
- Time: **Tuesday and Thursday 2:00PM - 3:50PM**
- Location: **[Zoom Link]**  
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Teaching Assistant: 
    - [Jinghui Chen](http://web.cs.ucla.edu/~jhchen/) (Email: jinghuic at ucla dot edu)
    - Shirley Chen (Email: shirleychen at cs dot ucla dot edu)
    - Yue Wu (Email: wuy at cs dot ucla dot edu)
    
- Office hours: 
    - The instructor's office hour is Wednesday 2:00pm-3:00pm on ([Zoom Link](https://ucla.zoom.us/j/95922207026?pwd=TmQ2THJoWVlENmhObVpUNWFJWDhhQT09)). 
    - The TA's office hour is: 
        - Jinghui Chen, Tuesday 4:00PM - 6:00PM ([Zoom Link](https://ucla.zoom.us/j/99792354291?pwd=TksxSU15Rm4xTzJ5OXg1MVpvdTJ4Zz09))
        - Shirley Chen, Wednesday 9:00PM - 11:00PM ([Zoom Link](https://ucla.zoom.us/j/91975431421?pwd=YlBsUXJldVZUSWVyTGZ6eFhBWDM2dz09))
        - Yue Wu, Thursday 4:00PM - 6:00PM ([Zoom Link](https://ucla.zoom.us/j/97555631173?pwd=L3dqYUppamdQK3huZGF6Nzh1L0E5UT09))
- Course Website: [https://uclaml.github.io/CS161-Winter2021/](https://uclaml.github.io/CS161-Winter2021/)
- Course Forum: [https://piazza.com/ucla/winter2021/cs161/home](https://piazza.com/ucla/winter2021/cs161/home)
(If you haven’t already, [sign up here](piazza.com/ucla/winter2021/cs161).)






## Grading Policy
 
Grades will be computed based on the following factors:

- Homework 20%
- Quiz 5%
- Midterm 35%
- Final 40%

## Schedule

| #  | Date  | Topics  |  Reading | Homework  |
|---|---|---|---|---|
| 1  | 1/5  |  [About Course](https://www.dropbox.com/s/6v49m2i9g6f18h3/Lecture0.pdf?dl=0), [Introduction: What is AI?](https://www.dropbox.com/s/o9wft7ybkmhqgxr/Lecture1.pdf?dl=0) |  Chapter 1,2 |   |
| 2 | 1/7 | [LISP](https://www.dropbox.com/s/9rqb830n8gr84tt/Lecture2.pdf?dl=0) | | |
| 3 | 1/12 | [Problem solving as search & Uninformed search strategies](https://www.dropbox.com/s/lwwxo28aee5bshv/Lecture3.pdf?dl=0) | Chapter 3 | |
| 4 | 1/14 | [Uninformed search strategies](https://www.dropbox.com/s/lwwxo28aee5bshv/Lecture3.pdf?dl=0) | Chapter 3 | HW1 Out |
| 5 | 1/19 | [Informed search strategies](https://www.dropbox.com/s/dvqksgu4ozo2pcc/lecture4.pdf?dl=0)| Chapter 3 |  |
| 6 | 1/21 | [Local Search Algorithms](https://www.dropbox.com/s/irybdjzo0tg29ac/lecture5.pdf?dl=0) | Chapter 4 | HW1 Due, HW2 Out|
| 7 | 1/26 | [Local Search Algorithms](https://www.dropbox.com/s/irybdjzo0tg29ac/lecture5.pdf?dl=0) | Chapter 4 | |
| 8 | 1/28 | [Constraint satisfaction](https://www.dropbox.com/s/kl3ynj8fnqe0v19/lecture6.pdf?dl=0) | Chapter 6 | HW2 Due, HW3 Out|
| 9 | 2/2 | [Constraint satisfaction](https://www.dropbox.com/s/kl3ynj8fnqe0v19/lecture6.pdf?dl=0) | Chapter 6 | |
| 10 | 2/4 | [Constraint satisfaction](https://www.dropbox.com/s/kl3ynj8fnqe0v19/lecture6.pdf?dl=0) | Chapter 6 |  |
| 11 | 2/9 | [Game playing](https://www.dropbox.com/s/iwm7wz5gf47s5hx/Lecture7.pdf?dl=0) | Chapter 5 | HW3 Due, Hw4 Out |
| 12 | 2/11 | [Game playing](https://www.dropbox.com/s/iwm7wz5gf47s5hx/Lecture7.pdf?dl=0) | Chapter 5 | |
|  | 2/16 | [Midterm Exam](https://www.dropbox.com/s/lhk376z72t6acfy/CS161%20Study%20Guide.docx?dl=0) | | |
| 13 | 2/18 | [Propositional logic](https://www.dropbox.com/s/yy88ndocrit0cgg/Lecture8.pdf?dl=0) | Chapter 7 | HW4 Due (extended), HW5 Out |
| 14 | 2/23 | [Propositional logic](https://www.dropbox.com/s/yy88ndocrit0cgg/Lecture8.pdf?dl=0) | Chapter 7 |  |
| 15 | 2/25 | [Propositional logic](https://www.dropbox.com/s/yy88ndocrit0cgg/Lecture8.pdf?dl=0) | Chapter 7 |  |
| 16 | 3/2 | [First-order logic: representation](https://www.dropbox.com/s/7g5o5vfof4jd1e4/Lecture9.pdf?dl=0) | Chapter 8 | HW5 Due|
| 17 | 3/4 | [First-order logic: inference](https://www.dropbox.com/s/ihnmk8u1mvjqr4o/Lecture10.pdf?dl=0) | Chapter 9 |  |
| 18 | 3/9 | [Reasoning under uncertainty](https://www.dropbox.com/s/cg7fuk1jhrnu2xs/Lecture11.pdf?dl=0) | Chapter 12 | HW6 Out  |
| 19 | 3/11 | [Bayesian Networks](https://www.dropbox.com/s/g1wc0vmyyt0o9zc/Lecture12.pdf?dl=0) | Chapter 13 | |
|  | 3/16 | Final Exam | |  |
|  | 3/19 | | |  HW6 Due |

## Academic Integrity Policy
Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 

## Homework
There will be 6 homework assignments during the semester as we cover the corresponding material. Homework consists of both problem solving and LISP programming. The lowest homework score will be dropped for you.

Unless otherwise indicated, you may talk to other students about the homework problems but each student must hand in their own answers and write their own code in the programming part. You also must indicate on each homework with whom you collaborated and cite any other sources you use including Internet websites. Students should never see another student's solution before submitting their own. Students cannot use old solution sets for this class or solution manual to the textbook under any circumstances.Homework assignments will be submitted through CCLE. 

Please submit your homework on time. Homework is worth full credit before the due date. It is worth zero credit after the due date.

## Quiz

There will be 6 in-class online quiz (on CCLE) for the purpose of reviewing the newly learned concepts. The quizzes are open textbook. We will drop the lowest quiz score for you.

## Exams

There will be one midterm and then final. The exam is online (on CCLE) and open book and note. You are not allowed to discuss with other people.
