[![DOI](https://zenodo.org/badge/353823752.svg)](https://zenodo.org/badge/latestdoi/353823752)
[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


# An LGBTQ-Inclusive Problem Set in Discrete Mathematics

## About
This repository is referenced in our SIGSCE 2022 paper by the same name. Included here, in order, are:
*  the problems used in the experimental homework we deployed,
*  additional problems we developed,
*  historical factoids we developed in conjunction with our minority-affirming problems,
*  and the survey questions we used to assess student reactions to the experimental homework.

Please cite this problem set using the following [DOI](https://zenodo.org/badge/latestdoi/353823752).

### Authors
Trysten Scott Richard - TSRichard95@gmail.com
</br>Eliane S. Wiese - eliane.wiese@utah.edu
</br>Zvonimir Rakamaric - zvonimir@cs.utah.edu

### Paper Abstract
This project aims to improve LGBTQ (lesbian, gay, bisexual, trans, and queer) representation in the University of Utah's discrete mathematics course. Many practice problems in the course textbook rely on heteronormative and/or cisnormative premises. We developed alternatives that maintained the original mathematical content while including minority identities, and then deployed them in a homework assignment. Students also completed a survey on their opinions of the new questions. Most students were open to the inclusion of LGBTQ representation in their homework, and many applauded it. However, students also suggested that subtle wording was preferable, and that affirming problems should be sprinkled across the course rather than concentrated in one assignment. Our experience provides an example of framing mathematical content to support an inclusive classroom climate, and we expect that our lessons learned can inform assignments that affirm minority identities throughout the CS curriculum.

### Important Note
Some of these problems were developed before we received student feedback and do note fully reflect the guidelines for inclusive pedagogy indicated by our research. These problems have been marked with "!!" immediately before their title (e.g., "!! Problem 8") and include a brief discussion of what makes them problematic, so that interested instructors can independently evaluate their usefulness.



## Problems Used in the Inclusive Combinatorics Assignment

#### Problem 2
Charlie and her girlfriend, Amber, go to lunch at a restaurant with 7 sandwiches on the menu. There are also 5 beverages on the menu. How many possible two-sandwich, two-drink meals can they order (regardless of which of them orders first)...
* if they order different sandwiches and drinks from each other?
* if they each order without concern for what the other ordered?

#### Problem 3
A small civil rights non-profit is selecting 3 of its 15 employees to form a task force focused on voting rights.
* How many such task forces could they possibly select?
* How many possibilities are there if they assign each member of the task force a unique role?

#### !! Problem 4
!! *This problem labels people (as the only way of describing them). A better description would focus on their actions or interests.*
</br>A student club focused on diversity is forming a recruitment committee consisting of 7 of its 30 members. 10 of the club’s members identify as gay and 5 identify as asexual. How many ways are there to form a recruitment committee which includes at least three members from each of these groups?

#### !! Problem 8
!! *This problem refers to 'biological sex', which at least one student found problematic.*
</br>You conduct an experiment in which you interview a large number of families, each of which has 5 children. For each family, you write down the biological sex (M for male, F for female, I for intersex) of the children, in order from oldest to youngest.
* How many possible results are there?
* Out of all the possible results, how many have exactly two I’s?
* Out of all the possible results, how many have at least one I, one F, and two M’s?

#### Problem 9
A group of students is surveyed about race and gender identity for research purposes. The survey lists 6 categories for race and 4 categories for gender. Determine how many different survey results are possible, given each of the following constraints:
* Students are allowed to check exactly 1 box under race and 1 box under gender.
* Students are allowed to check 1 or 2 boxes under race and 1 or 2 under gender.
* Students are allowed to check as many boxes as they wish (including 0).

#### !! Problem 12
!! *This problem setup lacks substance and would likely be perceived as on-the-nose by students.*
</br>Consider the set of letters, *{L, G, B, T, Q, I, A}*:
* How many ways are there to form a string containing exactly one copy of each letter?
* Suppose all license plates in a certain state consist of three distinct consonants followed by two distinct vowels. How many such license plates can be formed from the given set?
* Suppose three letters are chosen from this set at random (repeats allowed); what are the odds that at least one of them is a vowel (rounded to four digits)?


## Additional Problems

### Combinatorics Problems

#### !! Problem C1
!! *This problem labels people (as the only way of describing them). A better description would focus on their actions or interests.*
</br>In how many ways can three men, three women, and three non-binary students stand in a circle if no two people of the same gender identity are allowed to stand next to each other?

#### Problem C2
Jon wants to choose a different three-letter name for herself to better match her pronouns. How many consonant-vowel-consonant options does she have to choose from?

#### Problem C3
A group of 12 high school students is attending queer prom together. If they want to arrange themselves into 6 couples, how many possible couple arrangements can they choose from?

#### Problem C4
The organizers of a LGBTQ rally are making pride flags. Five people all choose different flag designs from among ten; how many possible combinations of flags might they end up with?

### Formal Proof Problems

#### Problem F1
Suppose 100 high school students attend a queer prom. Use the Pigeonhole Principle to prove that at least 9 of them share the same birth month.

### Graph Theory Problems

#### Problem G1
The graph below depicts connections in a blockchain network used to trade NFTs. Nodes represent individual users; an edge between two users means that they are contacts on the network. Thus, any walk along this graph represents a possible sequence of transactions for a hypothetical NFT.
* Find a sequence of 5 transactions which involves someone selling the NFT before buying it back from the same person they sold it to.
* Is the walk you found above a trail? Why or why not?
* Is the walk you found above a cycle? Why or why not?

<img src="https://user-images.githubusercontent.com/59627709/120771925-fe1b8e00-c4dc-11eb-89c3-9578ebbd7c07.jpg" width="730" height="370">

#### Problem G2
Robin has drawn two different family trees (labeled A and B below), both of which represent familial relationships between all seven members of their household. They live with their adoptive parents, Maya and Imani; their uncle, Kai; their grandparents, Carmen and Bo; and their great-grandmother, Ana.
* In tree A, what does a horizontal dashed line represent?
* In tree B, what does a horizontal solid line represent?
* In general, what's the difference between solid and dashed lines in these two trees?
* Why does Maya's node have three solid edges in tree B, but only one in tree A?
* Which representation of Robin's household do you prefer? Why?

<img src="https://user-images.githubusercontent.com/59627709/122342618-168aa000-cf02-11eb-8a7e-ec0a597848e3.jpg" width="730" height="370">
<img src="https://user-images.githubusercontent.com/59627709/122342712-299d7000-cf02-11eb-9d62-cf2fd8f650dc.jpg" width="730" height="370">

### Probability Problems

#### Problem P1
Three people are on a date together and decide to play an ice-breaking game in which they try to guess each other’s favorite seasons. (They write their guesses down all at once so the game isn’t spoiled when the answers are revealed.) What are the odds that:
* At least one of their six guesses is correct?
* Exactly two of their guesses are correct?

#### Problem P2
Imagine you attend a civil rights rally, looking for a friend who has volunteered their time to the event. You know that they will be at one of the 12 informational booths for half of the event, and another for the rest. If you only manage to visit 6 of the booths (dividing your time at each equally), what are your chances of finding them?

#### !! Problem P3
!! *This problem labels people (as the only way of describing them). A better description would focus on their actions or interests.*
</br>A club of 200 students is forming a committee with 10 members. Given that 15% of club members identify as queer, what are the odds that a randomly selected committee reflects this ratio within a 10% margin?

#### Problem P4
Suppose you attend a drag show in which two of your friends are performing. There are also two other performers scheduled that night, but you don’t know what order they’ll be in and you only have time to stay for half of the show. What are the odds that:
* You’ll see both of your friends perform?
* You’ll see just one of your friends perform?

#### !! Problem P5
!! *This problem trivializes an important issue by introducing it without addressing it.*
</br>Imagine you are conducting an on-campus survey to measure student awareness of the legacy of colonialism and slavery. The survey consists of five true/false historical questions, and you survey six students. Suppose, for simplicity, that every student has a 50/50 chance of answering each question correctly. What are the odds that:
* A given student scores 100%?
* A given student scores at least 80%?
* Two or more students score at least 60%?
* Also, is it possible for all students to get different scores? Why or why not?

#### Problem P6
Your local gay bar is hosting a trivia night; you decide to test your psychic abilities by participating and answering each question blindly. Suppose you answer 5 multiple-choice questions, each with four possible answers. What are your odds of:<br/>
* Answering none of the questions correctly?
* Answering at least three of the questions correctly?
* Answering three questions correctly in a row?

#### !! Problem P7
!! *This problem lacks explicit context and may feel like spotlighting to racial minority students.*
</br>A recent Stanford University study on racial bias in police traffic stops found that, among the US municipalities it analyzed, “the annual per-capita stop rate for black drivers was 0.20 compared to 0.14 for white  drivers. For Hispanic drivers … 0.09”. Now, imagine a US city in which 40% of the population is black, 35% is white, and 25% is Hispanic. Working from the data provided by the aforementioned study, what is the approximate likelihood that a given driver stopped by the police in this city is black?<br/>
[SOURCE](https://5harad.com/papers/100M-stops.pdf)

#### Problem P8
Recent census data has concluded that approximately 1.44% of US couples living together are “same-sex”. Of these, about 53.66% are legally married, which accounts for roughly 0.88% of married households in the country. Given a randomly selected US couple living in the same household (of any sexual orientation), what is the approximate likelihood that they are married?<br/>
[SOURCE](https://www.census.gov/newsroom/press-releases/2019/same-sex-households.html)

### Set Logic Problems

#### Problem S1 *(pairs with Factoid 6)*
Imagine you've created an algorithm for automatically writing sappy love letters. Such an algorithm might work (sort of like the game *Mad Libs*) by generating letter templates and replacing blank spaces with words drawn from collections of amorous terminology. For example, consider the template sentence, *S = "My LABEL, you have made me the most ADJECTIVE LABEL in the PLACE."* where *LABEL* is any member of the set *L = {dear, wife, husband, partner}*, *ADJECTIVE* is any member of the set *A = {enamored, overjoyed, fortunate}*, and *PLACE* is any member of the set *P = {world, galaxy, entirety of spacetime}*.
* How many different possible variations of the given example sentence, *S*, could your algorithm produce?
* How does your above answer change depending on whether repeated words are allowed?


## Affirming CS/Math History Factoids

#### Factoid 1
George Boole was husband to Mary Everest Boole, a self-taught English mathematician and teacher who lived during the 19th and 20th Centuries. As an advocate for educational methods which were progressive at the time, she used fables and stories to teach algebra. She also invented curve-stitching for similar purposes, which has since evolved into string art.

#### Factoid 2
The function f(x)=3(x^2)+5 describes a parabola. If you lived in Alexandria during the age of Rome, you might have learned about parabolas and other conic sections from Hypatia's exegesis on Apollonius' *Conics*. Hypatia was a Greek scholar and teacher, as well as the first female mathematician whose life is well-documented.

#### Factoid 3
The Bernoulli number sequence was the subject of the first published algorithm, written by Ada Lovelace in 1840 to be run on Charles Babbage's Analytical Engine, an early version of the modern computer.

#### Factoid 4
Turing machines share their namesake with the Turing test, which has inspired science fiction stories from *Blade Runner* to *I, Robot*. Both are named after the 'father of artificial intelligence', Alan Turing, whom Queen Elizabeth II posthumously pardoned in 2013 - more than half a century after he was prosecuted for homosexual acts and sentenced to chemical castration by the UK government.

#### Factoid 5
Alan Turing's work on the Halting Problem played a pivotal role in demonstrating the undecidability of mathematics. [This](https://www.youtube.com/watch?v=HeQX2HjkcNo) video discusses Turing's work on undecidability in the context of Kurt Godel's famous incompleteness proof; taken together, they raise profound questions about the nature of logic and reason.

#### Factoid 6 *(pairs with Problem S1)*
This problem was inspired by the [Strachey love letter algorithm](https://en.wikipedia.org/wiki/Strachey_love_letter_algorithm), written in 1952 for the Manchester Mark 1. Its author, Christopher Strachey was a British computer scientist during the mid-20th Century who pioneered the idea of time-sharing. He also developed an early version of checkers for the Manchester Ferranti.


## Class Survey Questions

#### Question 1
Did you notice that some of the problems on your most recent homework emphasized inclusiveness regarding gender and sexual orientation?
* Yes
* No
* Unsure

#### Question 2
How did these inclusive problems make you feel?
* Very Uncomfortable
* Somewhat Uncomfortable
* Neutral
* Somewhat Comfortable
* Very Comfortable

Consider this problem scenario described in your textbook:<br/>
*“An organization has 10 male and 7 female members. In how many ways can the organization elect a president, vice president, and secretary if all three officers may not be of the same sex?”*

By comparison, consider this similar problem scenario described in your most recent homework:<br/>
*“A student club focused on diversity is forming a recruitment committee consisting of 7 of its 30 members. 10 of the club’s members identify as gay and 5 identify as asexual. How many ways are there to form a recruitment committee which includes at least three members from each of these groups?”*

#### Question 3
Which of the above problems do you think is harder to solve?
* Textbook Version
* Homework Version
* Neither

#### Question 4
Which of the above problems do you prefer overall?
* Textbook Version
* Homework Version
* Neither

#### Question 5
Why do you prefer the version you chose? (Enter N/A for neither preference)
* (OPEN RESPONSE)

#### Question 6
Finish the following statement (Select all that apply): "Compared to our usual problems, I thought the inclusive problems on our most recent homework were..."
* easier to solve
* harder to solve
* more fun to solve
* less fun to solve
* more realistic
* less realistic
* more representative of my identity/community
* less representative of my identity/community
* Other...

#### Question 7
How would you feel about seeing more problems focused on inclusiveness in future homework assignments?
* Very Negative
* Somewhat Negative
* Neutral
* Somewhat Positive
* Very Positive

#### Question 8
What is your age?
* (SHORT ANSWER)

#### Question 9
What is your gender identity? (e.g., Woman, Transgender, Genderqueer, etc.)
* (SHORT ANSWER)

#### Question 10
What is your sexual orientation? (e.g., Gay, Straight, Asexual, etc.)
* (SHORT ANSWER)

#### Question 11
Which aspects of your identity are important to you? (Select all that apply)
* Age
* Gender
* Sexual Orientation
* Race/Ethnicity
* Religion/Spirituality
* Political Affiliation
* Other...

#### Question 12
How would you say your identity is treated in the School of Computing, with respect to your age?
* Very Maligned
* Somewhat Maligned
* Neutral
* Somewhat Affirmed
* Very Affirmed
* This aspect of my identity is unimportant to me

#### Question 13
How would you say your identity is treated in the School of Computing, with respect to your gender?
* Very Maligned
* Somewhat Maligned
* Neutral
* Somewhat Affirmed
* Very Affirmed
* This aspect of my identity is unimportant to me

#### Question 14
How would you say your identity is treated in the School of Computing, with respect to your sexual orientation?
* Very Maligned
* Somewhat Maligned
* Neutral
* Somewhat Affirmed
* Very Affirmed
* This aspect of my identity is unimportant to me

#### Question 15
How would you say your identity is treated in the School of Computing, with respect to your racial heritage?
* Very Maligned
* Somewhat Maligned
* Neutral
* Somewhat Affirmed
* Very Affirmed
* This aspect of my identity is unimportant to me

#### Question 16
How would you say your identity is treated in the School of Computing, with respect to your religious beliefs?
* Very Maligned
* Somewhat Maligned
* Neutral
* Somewhat Affirmed
* Very Affirmed
* This aspect of my identity is unimportant to me

#### Question 17
How would you say your identity is treated in the School of Computing, with respect to your political affiliation?
* Very Maligned
* Somewhat Maligned
* Neutral
* Somewhat Affirmed
* Very Affirmed
* This aspect of my identity is unimportant to me

#### Question 18
How would you say your identity is treated in the School of Computing, in general?
* Very Maligned
* Somewhat Maligned
* Neutral
* Somewhat Affirmed
* Very Affirmed
* This issue is unimportant to me

#### Question 19
Any additional feedback for the CS 2100 staff regarding inclusiveness?
* (OPEN RESPONSE)

*Note that some of the above questions are strictly multiple-choice, whereas others ask respondents to “Select all that apply”.*
