$$\underline{\Huge\text{PROBABILITY}}$$
# CHAPTER 2: PROBABILITY
# 2.0 INTRODUCTION
Probability is the important concept in mathematics. It is all about chances on how likely events are to happen. At its simplest, it is concerned with the roll of a dice, or the fall of the cards in a game.

# 2.1 ELEMENTARY PROBABILITY
A probability gives the likelihood that an event will occur. It is quantified as a positive number between 0 (the event is impossible) and 1 (the event is certain). Thus, the higher the probability of a given event, the more likely it is to occur.

Probability can be expressed in a number of ways. An approach is to observe a number of particular events out of a total number of events is known as relative frequency.

## 2.1.1 Relative Frequency
Relative frequency is discussed about how often something happens divided by all outcomes. For example, suppose we are interested in the outcome number 3 when we toss a dice. After 18 tosses, we had two 3s. That means, a relative frequency is $\frac{2}{18}=0.11$.

Another example, suppose that there are two blue pens, a black pen and a grey pen. We are interested in choosing a black pen. Thus, the relative frequency is $\frac{1}{4}=0.25$.

Thus, we can come out with the formula for relative frequency, that is:

> [!formula]
> $\text{Relative frequency} = \frac{\text{Number of times outcome occurs}}{\text{Total number of trials}}$ 

Now, we discuss about the limiting value of the relative frequency. For example, if number 1, 2, 3, 4, 5 and 6 on a dice have the same chance of appearing when the dice is tossed, then the limiting value of the relative frequency will be $\frac{1}{6}$. The limiting value of the relative frequency is also referred to probability.

# 2.2 PROBABILITY
Probability is a mathematical language for quantifying uncertainty. In this chapter we introduce the basic concepts underlying probability theory. We begin with the definition of basic terms in probability.

| Experiment | Outcomes | Sample Space | Event |
| :--- | :--- | :--- | :--- |
| Tossing a coin once | Head, Tail | $S=\{Head,Tail\}$ | Event A to get a head, $A=\{Head\}$ |
| Tossing a coin twice | HH, HT, TH, TT | $S=\{HH,HT,TH,TT\}$ | Event B to get at least one head, $B=\{HH,HT\}$ |
| Rolling a die once | 1,2,3,4,5,6 | $S=\{1,2,3,4,5,6\}$ | Event C to get odd numbers, $C=\{1,3,5\}$ |
| 30 cards which are marked with number from 1 to 30 are placed in a box | $1,2,3,...,30$ | $S=\{1,2,3,...,30\}$ | Event D to get prime numbers, $D=\{2,3,5,7,11,13,17,19,23,29\}$ |
| Taking a driving test | Pass, Fail | $S=\{Pass,Fail\}$ | Event E to fail a test, $E=\{Fail\}$ |


> [!definition]- Definitions
> * **Experiment**: A trial that produces possible outcomes.
> * **Outcome**: The results of an experiment.
> * **Event**: The set of outcomes of the experiment.
> * **Sample space**: The collection of all the outcomes and is denoted by S. The sample space can be represented in set notation, Venn diagram, tree diagram and Cartesian graph.
> * **Equally likely outcomes**: Each outcome for an experiment has an equal probability of occurrence.
> * **Random selections**: The selection of outcomes from the sample space in which each outcome has an equal chance of being selected.

# 2.3 CLASSICAL DEFINITION OF PROBABILITY
Suppose S is a sample space and each outcome in S is equally likely to occur. If A is an event (a subset of S) then the probability of an event A occurring is denoted by $P(A)$, where:

> [!formula] 
> $P(A) = \frac{\text{number of outcomes in } A}{\text{number of outcomes in } S} = \frac{n(A)}{n(S)}$ 

> [!example]- Example 2.1
> Consider an experiment in rolling a dice. Find the probability of getting an odd number.
> > [!continue]- Solution
> > When rolling a die, there are six possible outcomes. The sample space is $S=\{1,2,3,4,5,6\}$, then $n(S)=6$. Suppose A is the event of getting an odd number, $A=\{1,3,5\}$, then $n(A)=3$.
> > 
> > The probability of getting an odd number, $P(A)=\frac{n(A)}{n(S)}=\frac{3}{6}=\frac{1}{2}$.

> [!example]- Example 2.2
> Suppose that there are two dice are tossed, find:
> a) the probability of the sum of two numbers is 8,
> b) the probability of the sum of two numbers is multiple of 5,
> c) the probability that both numbers drawn are prime number.
> > [!continue]- Solution
> > List the sample space, S when two dice are tossed.
> > $S = \{ (1,1), (1,2), (1,3), (1,4), (1,5), (1,6), (2,1), (2,2), (2,3), (2,4), (2,5), (2,6), (3,1), (3,2), (3,3), (3,4), (3,5), (3,6), (4,1), (4,2), (4,3), (4,4), (4,5), (4,6), (5,1), (5,2), (5,3), (5,4), (5,5), (5,6), (6,1), (6,2), (6,3), (6,4), (6,5), (6,6) \}$ .
> > $n(S)=36$.
> > 
> > a) Let A be the event of the sum of two numbers is 8.
> > $A=\{(2,6),(6,2),(3,5),(5,3),(4,4)\}$ , $n(A)=5$.
> > $P(A)=\frac{n(A)}{n(S)}=\frac{5}{36}$.
> > 
> > b) Let B be the event of the sum of two numbers is multiple of 5.
> > $B=\{(1,4),(4,1),(2,3),(3,2),(4,6),(6,4),(4,6),(5,5)\}$. *(Note: source contains a typo repeating (4,6), the intended set has $n(B)=7$)*.
> > $n(B)=7$.
> > $P(B)=\frac{n(B)}{n(S)}=\frac{7}{36}$.
> > 
> > c) Let C be the event of both numbers drawn are prime number.
> > $C=\{(2,2),(2,3),(3,2),(2,5),(3,3),(5,2),(3,5),(5,3),(5,5)\}$ , $n(C)=9$.
> > $P(C)=\frac{n(C)}{n(S)}=\frac{9}{36}=\frac{1}{4}$.

> [!example]- Example 2.3
> There are red and blue balls in a box. A ball is drawn at random from the box. The probability of drawing a red ball is $\frac{7}{12}$. Find,
> a) the probability of drawing a blue ball,
> b) the number of red balls in the box if there are 10 blue balls in the box.
> > [!continue]- Solution
> > a) Let R be the event drawing a red ball, $P(R)=\frac{7}{12}$. Let B be the event drawing a blue ball, we want to find $P(B)$.
> > We know that $P(B)+P(R)=1$.
> > Thus, $P(B)=1-\frac{7}{12}=\frac{5}{12}$.
> > 
> > b) There are 10 blue balls in the box, thus $n(B)=10$, we need to find $n(R)$. We have
> > $P(B)=\frac{5}{12}=\frac{n(B)}{n(S)}\Rightarrow\frac{5}{12}=\frac{10}{n(S)}\Rightarrow n(S)=24$.
> > $n(R)=24-10=14$.

> [!example]- Example 2.4
> There are 48 beads consists of red, yellow, and blue colour in a bag. A bead is drawn at random and the probability of drawing a red bead is $\frac{1}{6}$.
> a) Find the number of red beads in the bag.
> b) If there are 24 yellow beads in the bag, find the probability of drawing a blue bead.
> > [!continue]- Solution
> > a) There are 48 beads, $n(S)=48$. The probability of drawing a red bead is $\frac{1}{6}$, $P(R)=\frac{1}{6}$.
> > We want to find $n(R)$.
> > $P(R)=\frac{n(R)}{n(S)}=\frac{n(R)}{48}=\frac{1}{6}\Rightarrow n(R)=8$.
> > 
> > b) There are 24 yellow beads, $n(Y)=24$. We want to find the probability of drawing a blue bead, $P(B)$. We know that, $n(R)+n(Y)+n(B)=48$.
> > $n(B)=48-n(R)-n(Y)=48-8-24=16$.
> > $P(B)=\frac{n(B)}{n(S)}=\frac{16}{48}=\frac{1}{3}$.

> [!sq]- Problem 2.1
> A bag contains 3 blue balls, 4 red balls and 5 white balls. A ball is drawn at random. Find the probability that:
> a) the ball is blue,
> b) the ball is red,
> c) the ball is not white.
> > [!continue]- Solution
> > Total number of balls, $n(S) = 3 + 4 + 5 = 12$.
> > a) Let B be the event drawing a blue ball. $n(B) = 3$.
> > $P(B) = \frac{3}{12} = \frac{1}{4}$.
> > b) Let R be the event drawing a red ball. $n(R) = 4$.
> > $P(R) = \frac{4}{12} = \frac{1}{3}$.
> > c) Let W be the event drawing a white ball. $n(W) = 5$.
> > $P(W) = \frac{5}{12}$.
> > $P(\text{not white}) = 1 - P(W) = 1 - \frac{5}{12} = \frac{7}{12}$. (Alternatively, probability of picking blue or red = $\frac{3+4}{12} = \frac{7}{12}$).

> [!sq]- Problem 2.2
> A fair dice is tossed. Find the probability of:
> a) getting a number of multiple 3,
> b) getting a number of not multiple 3.
> > [!continue]- Solution
> > The sample space for tossing a fair dice is $S = \{1, 2, 3, 4, 5, 6\}$, so $n(S) = 6$.
> > a) Let A be the event getting a multiple of 3. $A = \{3, 6\}$, so $n(A) = 2$.
> > $P(A) = \frac{2}{6} = \frac{1}{3}$.
> > b) Let B be the event getting a number not a multiple of 3. $B = \{1, 2, 4, 5\}$, so $n(B) = 4$.
> > $P(B) = \frac{4}{6} = \frac{2}{3}$.

> [!sq]- Problem 2.3
> Two fair coins are tossed, find the probability that exactly one head is obtained.
> > [!continue]- Solution
> > The sample space for tossing two fair coins is $S = \{HH, HT, TH, TT\}$, so $n(S) = 4$.
> > Let A be the event of getting exactly one head. $A = \{HT, TH\}$, so $n(A) = 2$.
> > $P(A) = \frac{2}{4} = \frac{1}{2}$.

> [!sq]- Problem 2.4
> A number from 1 to 11 is chosen at random. What is the probability of choosing an odd number? 
> > [!continue]- Solution
> > The sample space is $S = \{1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11\}$, so $n(S) = 11$.
> > Let A be the event of choosing an odd number. $A = \{1, 3, 5, 7, 9, 11\}$, so $n(A) = 6$.
> > $P(A) = \frac{6}{11}$.

> [!sq]- Problem 2.5
> A spinner has 4 equal sectors colored yellow, blue, red and green. After spinning the spinner, what is the probability of landing on green color? 
> > [!continue]- Solution
> > The total number of equal sectors is 4.
> > Since there is exactly 1 green sector, the probability of landing on green is $\frac{1}{4}$.

> [!sq]- Problem 2.6
> A die is tossed. The event A is defined as getting a number divisible by 3. If the event B is defined as getting a number not divisible by 3, find $P(A)$ and $P(B)$.
> > [!continue]- Solution
> > Sample space $S = \{1, 2, 3, 4, 5, 6\}$, so $n(S) = 6$.
> > Event A (divisible by 3) = $\{3, 6\}$, so $n(A) = 2$.
> > $P(A) = \frac{2}{6} = \frac{1}{3}$.
> > Event B (not divisible by 3) = $\{1, 2, 4, 5\}$, so $n(B) = 4$.
> > $P(B) = \frac{4}{6} = \frac{2}{3}$.

# 2.4 BASIC PROBABILITY RULES
If the probability of an event A occurring is denoted by $P(A)$, then it must follow the following conditions:
1) Probability is measured by a number between 0 and 1 inclusive, that is $0 \le P(A) \le 1$. $P(A)=0$ means the event is impossible event. $P(A)=1$ means the event is sure or certain event.
2) A set of events that contains all the possible outcomes of an experiment is said to be exhaustive. $\sum_{i=1}^{n}P(A_{i})=1$. In the special case of event A and its complement, $A'$, the sum of their probabilities is 1 because one of them is certain to occur, $P(A)+P(A')=1$ or $P(A')=1-P(A)$.
3) Mutually exclusive events, are two events shows there is no intersections between them that is, $A \cap B = \emptyset$. For mutually exclusive events, We can use a Venn diagram to illustrate the mutually exclusive events.

## 2.4.1 Venn Diagrams
The graphical representation which can be helpful in illustrating multiple events. A Venn Diagram is clever because it shows lots of information. Note that $U=\{A,A'\}$ where $A'$ is the complement of A which implies A does not occur.

Suppose A and B are two events associated with a particular statistical experiment. Then, we have:
1. $A \cup B$ read as A union B means A or B. This implies either A or B or both occurs.
2. $A \cap B$ read as A intersect B means A and B. This implies both A and B occurs.

### 2.4.1.1 De Morgan Rules
* $P(A' \cap B') = P(A \cup B)'$ 
* $P(A' \cup B') = P(A \cap B)'$ 
* $P(A \cap B') = P(A \cup B) - P(B) = P(A) - P(A \cap B)$ 

### 2.4.1.2 Additive Rule of Probability
For any two events A and B, the additive rule of probability is defined as:
$P(A \cup B) = P(A) + P(B) - P(A \cap B)$.
$P(A \cup B)$ is also denoted as P(A or B or both).

### 2.4.1.3 Mutually Exclusive Events
Two or more events are said to be mutually exclusive if they cannot occur at the same time. In other words, events that have no outcomes in common are said to be mutually exclusive events or disjoint events. If two events A and B are mutually exclusive, then the probability of the occurrence of A or B is the sum of their individual probabilities. Additional probability rules for two mutually exclusive events are, $P(A \cup B) = P(A) + P(B)$. Since, $P(A \cap B) = 0$.

For example, when we roll a die, the event of getting even number is {2,4,6} and the event of getting factor of 5 is {1,5}. Both of these events are mutually exclusive because they have no common favourable outcomes. It is not possible to roll a number that is even and a factor of 5. We say that the intersection of these two sets is empty.
Therefore, $P(\text{even or factor of 5}) = P(\text{even}) + P(\text{factor of 5})$.

## 2.4.2 Tree Diagram
A tree diagram consists of a number of branches that illustrate all the possible outcome of a sequence of experiments or event where each event can occur in a finite number of ways. The diagram can be helpful in showing the outcomes of a sequence of statistical experiments. Each outcome is represented by a branch of a tree, with its probability written alongside the branch.

i. How do we calculate the overall probabilities? We multiply probabilities along the branches.
ii. We add probabilities down columns.

> [!example]- Example 2.5
> Amna is answering two True/False questions in a quiz.
> a) Draw a tree diagram for the possible answers she could give.
> b) Find the probability of getting:
> i. both correct answers,
> ii. one correct answer.
> > [!continue]- Solution
> > a) (Tree Diagram representation)
> > 
> > * First answer (Correct = C, Wrong = W), each with probability $\frac{1}{2}$.
> > * Second answer (Correct = C, Wrong = W), each with probability $\frac{1}{2}$.
> > 
> > b)i) $P(\text{both correct})=\frac{1}{2}\times\frac{1}{2}=\frac{1}{4}$.
> > b)ii) $P(\text{one correct})=(\frac{1}{2}\times\frac{1}{2})+(\frac{1}{2}\times\frac{1}{2})=\frac{1}{2}$.

> [!example]- Example 2.6
> Suppose that a die is rolling. Let A be the event of getting even numbers and B be the event of getting odd numbers. Show that, A and B are mutual exclusive event.
> 
> > [!continue]- Solution
> > We know that, $S=\{1,2,3,4,5,6\}$, such that $A=\{2,4,6\}$ and $B=\{1,3,5\}$. Therefore, $A\cap B=\emptyset$. Hence, A and B are mutual exclusive event.
> > The probability of getting A and B are $P(A)=\frac{3}{6}=0.5$ and $P(B)=\frac{3}{6}=0.5$ respectively. Thus, $P(A)+P(B)=1$. Shown.
> > 
> > ![[Pasted image 20260214155914.png]]

> [!example]- Example 2.7
> Two fair coins are tossed simultaneously. Find the probability of getting,
> a) exactly two heads,
> b) at least one head.
> 
> > [!continue]- Solution
> > $S=\{HH,HT,TH,TT\}$, $n(S)=4$.
> > 
> > ![[Pasted image 20260214155931.png]]
> > 
> > a) Let A be the event getting exactly two heads, 
> > $A=\{HH\}$, $n(A)=1$
> > $P(A)=\frac{1}{4}$
> > 
> > b) Let B be the event getting at least one head,
> > $B=\{HH,HT,TH\}$, $n(B)=3$
> > $P(B)=\frac{3}{4}$

> [!example]- Example 2.8
> Given A and B are 2 events where $P(A)=\frac{1}{3}$, $P(B)=\frac{5}{9}$ and $P(A\cap B)=\frac{1}{6}$. Find:
> i. $P(A\cup B)$,
> ii. $P(A^{\prime}\cap B^{\prime})$.
> 
> > [!continue]- Solution
> > i. $P(A\cup B)=P(A)+P(B)-P(A\cap B)=\frac{1}{3}+\frac{5}{9}-\frac{1}{6}=\frac{13}{18}$
> > ii. From De Morgan rule, 
> > $P(A^{\prime}\cap B^{\prime})=P(A\cup B)^{\prime}=1-P(A\cup B)=1-\frac{13}{18}=\frac{5}{18}$.

> [!example]- Example 2.9
> An integer is selected randomly from a set of integers {1,2,3,4,5,6,7,8,9,10,11,12}. Find the probability that the integer is,
> a) an even number or is divisible by 3,
> b) an even number and is not divisible by 3.
> 
> > [!continue]- Solution
> > Let $A=\{2,4,6,8,10,12\}$, $B=\{3,6,9,12\}$.
> > 
> > a) By using the additive rule of probability:
> > $P(A\cup B)=P(A)+P(B)-P(A\cap B)=\frac{6}{12}+\frac{4}{12}-\frac{2}{12}=\frac{2}{3}.$
> > 
> > b) By using De Morgan:
> > $P(A\cap B^{\prime})=P(A)-P(A\cap B)=\frac{6}{12}-\frac{2}{12}=\frac{1}{3}$

> [!example]- Example 2.10
> There are 100 form six students, of whom 20 are taking Biology subject, 15 are taking Chemistry subject and 8 are taking both Biology and Chemistry subject. Find:
> a) P(taking both Biology and Chemistry).
> b) P(taking Biology or Chemistry or both).
> 
> > [!continue]- Solution
> > We can use a Venn diagram to solve probability problems. Let B be the event of student taking Biology subject and C be the event of student taking Chemistry subject:
> > 
> > ![[Pasted image 20260214155951.png]]
> > 
> > a) P(taking both Biology and Chemistry) $=P(B\cap C)=\frac{8}{100}=\frac{2}{25}$
> > b) P(taking Biology or Chemistry or both) $=P(B\cup C)=\frac{12+8+7}{100}=\frac{27}{100}.$

> [!example]- Example 2.11
> In a junior school class of 28 pupils, 7 are in a sports team and the school band. There are 16 pupils involved in sports team and 10 pupils in the school band team. Find the probability that a pupil chosen at random,
> a) is only in the school band,
> b) is in either a sports team or the school band,
> c) is in neither a sports team nor the school band.
> 
> > [!continue]- Solution
> > We can use a Venn diagram to solve probability problems. Let T be the event of pupils in sport team and B be the event of pupils in school band.
> > 
> > ![[Pasted image 20260214160010.png]]
> > 
> > a) The probability that a pupil chosen at random is only in the school band, $P(B)=\frac{3}{28}$
> > b) The probability that a pupil chosen at random is in either a sports team or the school band, $P[(T\cap B^{\prime})\cup(T^{\prime}\cap B)\cup(T\cap B)]=\frac{9+7+3}{28}=\frac{19}{28}$ *(Note: corrected formula representation for union based on context)*
> > c) The probability that a pupil chosen at random is in neither a sports team nor the school band, $P(T\cap B)^{\prime}=P(T\cup B)^{\prime}=\frac{9}{28}$ *(Note: corrected De Morgan notation $P(T^{\prime}\cap B^{\prime})$)*

> [!example]- Example 2.12
> After SPM, the probability that Ammar will follow a matriculation program is $\frac{3}{5}$ whereas the probability that he will continue his studies in Form 6 is $\frac{1}{4}$. Find, the probability that after SPM, Ammar will follow a matriculation program or continue his studies in Form 6.
> 
> > [!continue]- Solution
> > The probability that Ammar will follow a matriculation program, $P(M)=\frac{3}{5}$.
> > The probability that he will continue his studies in Form 6, $P(Form~6)=\frac{1}{4}$.
> > The probability that Ammar will follow a matriculation program or will continue his studies in Form 6,
> > $P(M \text{ or } Form~6) = P(M\cup Form~6) = P(M)+P(Form~6)-P(M\cap Form~6)=\frac{3}{5}+\frac{1}{4}-0=\frac{17}{20}$

> [!example]- Example 2.13
> Given that C and D are two events where $P(C)=0.1$, $P(D)=0.2$ and $P(C\cup D)=0.3$.
> a) Determine whether C and D are two mutually exclusive events.
> b) Determine $P(C^{\prime})$ and $P(C^{\prime}\cap D^{\prime})$.
> 
> > [!continue]- Solution
> > a) If C and D are mutually exclusive events, then $P(C\cup D)=P(C)+P(D)$.
> > $P(C\cup D)=P(C)+P(D)$
> > $0.3=0.2+0.1$ (They are mutually exclusive).
> > b) Complement: $P(C^{\prime})=1-P(C)=1-0.1=0.9$
> > De Morgan: $P(C^{\prime}\cap D^{\prime})=P(C\cup D)^{\prime}=1-P(C\cup D)=1-0.3=0.7$.

> [!example]- Example 2.14
> A bag contains 4 red marbles, 2 white marbles and 8 black marbles. What is the probability that a marble picked from the bag at random is either red or white?
> 
> > [!continue]- Solution
> > Let R be the event that red marble is picked and W be the event that white marble is picked.
> > $P(R\cap W^{\prime})\cup P(W\cap R^{\prime})$
> > $=[P(R)-P(R\cap W)]+[P(W)-P(W\cap R)]=(\frac{4}{14}-0)+(\frac{2}{14}-0)=\frac{3}{7}.$

> [!example]- Example 2.15
> One student feels that the probability he will get a grade D in a statistics course is $\frac{1}{8}$ and the probability he will fail in that course is $\frac{1}{16}$. What is the probability he will get a grade better than D?
> 
> > [!continue]- Solution
> > Let D be the event of getting grade D and F be the event of failing. The probability he will get a grade better than D is denoted as $P(D\cup F)^{\prime}$.
> > $P(D\cup F)^{\prime} = 1-P(D\cup F)=1-[P(D)+P(F)-P(D\cap F)]=1-(\frac{1}{8}+\frac{1}{16}-0)=\frac{13}{16}.$

> [!sq]- Problem 2.7
> In a science class of 50 students, 27 are boys and 23 are girls. During Test 1, 14 boys and 15 girls made an A grade. If a student is chosen at random from the class, what is the probability of choosing a girl or an A student?
> 
> > [!continue]- Solution
> > Let $G$ be the event of choosing a girl, and $A$ be the event of choosing an A student.
> > Total students $n(S) = 50$.
> > $n(G) = 23$, so $P(G) = \frac{23}{50}$.
> > Total A students $n(A) = 14 + 15 = 29$, so $P(A) = \frac{29}{50}$.
> > Number of girls who are A students $n(G \cap A) = 15$, so $P(G \cap A) = \frac{15}{50}$.
> > $P(G \cup A) = P(G) + P(A) - P(G \cap A) = \frac{23}{50} + \frac{29}{50} - \frac{15}{50} = \frac{37}{50}$.

> [!sq]- Problem 2.8
> A glass of jar contains 2 red, 4 green, 3 blue and 5 yellow marbles. If a single marble is chosen at random from the jar, what is the probability that it is red or blue?
> 
> > [!continue]- Solution
> > Total marbles $n(S) = 2 + 4 + 3 + 5 = 14$.
> > Let $R$ be the event of picking a red marble, and $B$ be the event of picking a blue marble.
> > $n(R) = 2$ and $n(B) = 3$.
> > Since a marble cannot be both red and blue, the events are mutually exclusive ($P(R \cap B) = 0$).
> > $P(R \cup B) = P(R) + P(B) = \frac{2}{14} + \frac{3}{14} = \frac{5}{14}$.

> [!sq]- Problem 2.9
> On festival day, the probability of a person having a car accident is 0.08. The probability of a person driving while used handphone is 0.22 and probability of a person having a car accident while used handphone is 0.14. Find the probability of a person driving while used handphone or having a car accident.
> 
> > [!continue]- Solution
> > Let $A$ be the event of having a car accident, and $H$ be the event of driving while using a handphone.
> > $P(A) = 0.08$
> > $P(H) = 0.22$
> > $P(A \cap H) = 0.14$
> > $P(H \cup A) = P(H) + P(A) - P(A \cap H) = 0.22 + 0.08 - 0.14 = 0.16$.

> [!sq]- Problem 2.10
> The probability of a student owning a vehicle is 0.7, of owing a handphone is 0.81 and of owning both is 0.56. If a student is chosen at random, find the probability that the student owns a handphone or a vehicle.
> 
> > [!continue]- Solution
> > Let $V$ be the event of owning a vehicle, and $H$ be the event of owning a handphone.
> > $P(V) = 0.7$
> > $P(H) = 0.81$
> > $P(V \cap H) = 0.56$
> > $P(H \cup V) = P(H) + P(V) - P(V \cap H) = 0.81 + 0.7 - 0.56 = 0.95$.

## 2.5 MULTIPLICATIVE RULE OF PROBABILITY
The multiplication rule in probability allows we to calculate the joint probability of multiple events occurring together using known probabilities of those events individually. There are two forms of this rule, the specific and general multiplication rules.

### 2.5.1 Independent Events
When events are independent, you can use the specific multiplication rule. Two events are said to be independent if either can occur without being affected by the occurrence of the other. Examples of this are making selections with replacement and performing separate actions, such as rolling two dice.

The multiplication law for independent events is:
> [!formula] 
> $P(A\cap B) = P(A \text{ and } B) = P(A) \times P(B)$

The tree diagram for independent events of A and B:
![[Pasted image 20260214160033.png]]

> [!example]- Example 2.16
> Suppose two events A and B are independent. Given $P(A)=0.4$ and $P(B)=0.25$. Calculate:
> a) $P(A\cap B)$.
> b) $P(A\cup B)$.
> 
> > [!continue]- Solution
> > a) $P(A\cap B)=P(A)\times P(B)=0.4\times0.25=0.1$
> > b) $P(A\cup B)=P(A)+P(B)-P(A\cap B)=0.4+0.25-0.1=0.55$.

> [!example]- Example 2.17
> A bag contains 3 black balls and 5 white balls. Rayd picks a ball at random from the bag and replaces it back in the bag. He mixes the balls in the bag and then picks another ball at random from the bag.
> a) Construct a probability tree of the problem.
> b) Calculate the probability that Rayd picks:
> i. two black balls,
> ii. a black ball in his second draw.
> 
> > [!continue]- Solution
> > a) 
> > ![[Pasted image 20260214160100.png]]
> > 
> > b)i) To find the probability of getting two black balls, first locate the B branch and then follow the second B branch. Since these are independent events, we can multiply the probability of each branch.
> > $P(\text{two black balls})=\frac{3}{8}\times\frac{3}{8}=\frac{9}{64}.$
> > 
> > b)ii) There are two outcomes where the second ball can be black. Either (B, B) or (W, B):
> > $P(\text{second ball is black ball})=\frac{3}{8}\times\frac{3}{8}+\frac{5}{8}\times\frac{3}{8}=\frac{24}{64}=\frac{3}{8}$

> [!example]- Example 2.18
> Bag A contains 10 marbles of which 2 are red and 8 are black. Bag B contains 12 marbles of which 4 are red and 8 are black. A ball is drawn at random from each bag.
> a) Draw a probability tree diagram to show all the outcomes the experiment.
> b) Find the probability that:
> i. both are red,
> ii. both are black,
> iii. one black and one red,
> iv. at least one red.
> 
> > [!continue]- Solution
> > a) 
> > ![[Pasted image 20260214160118.png]]
> > 
> > b)i) $P(\text{both are red})=\frac{1}{5}\times\frac{1}{3}=\frac{1}{15}.$
> > b)ii) $P(\text{both are black})=\frac{4}{5}\times\frac{2}{3}=\frac{8}{15}.$
> > b)iii) $P(\text{one black and one red})=\frac{1}{5}\times\frac{2}{3}+\frac{4}{5}\times\frac{1}{3}=\frac{2}{5}.$
> > b)iv) $P(\text{at least one red})=1-\frac{8}{15}=\frac{7}{15}.$
> > Alternatively, $P(\text{at least one red}) = \frac{1}{15} + \frac{2}{15} + \frac{4}{15} = \frac{7}{15}.$ *(Note: reconstructed formula based on fractions)*.

> [!example]- Example 2.19
> Ahmad spins 2 spinners, one of which is labelled A, B and C and the other is labelled X, Y and Z. Find:
> a) the probability that the spinners stop at C and X,
> b) the probability that the spinners do not stop at C and X,
> c) the probability that the first spinner does not stop at A.
> 
> > [!continue]- Solution
> > a) $P(C\cap X)=\frac{1}{3}\times\frac{1}{3}=\frac{1}{9}.$
> > 
> > ![[Pasted image 20260214160142.png]]
> > 
> > b) P(spinner does not stop C and X) $= 1-\frac{1}{9}=\frac{8}{9}$
> > 
> > c) P(first spinner does not stop at A) $= 2(\frac{1}{3}\times\frac{1}{3}+\frac{1}{3}\times\frac{1}{3}+\frac{1}{3}\times\frac{1}{3})=\frac{2}{3}$

> [!sq]- Problem 2.11
> Jannah has a basket with 7 blue candies and 3 yellow candies in it. She picks up a candy at random from the basket, but does not replace it back. Then she picks again at random. Draw a tree diagram to represent this situation and use it to calculate the probabilities that she picks:
> a) two yellow candies,
> b) at least one blue candy,
> c) one sweet candy of each colour,
> d) no red sweets.
> 
> > [!continue]- Solution
> > [EditHere - Tree diagram: First draw Blue (7/10) or Yellow (3/10). If Blue, second draw is Blue (6/9) or Yellow (3/9). If Yellow, second draw is Blue (7/9) or Yellow (2/9)]
> > 
> > a) $P(\text{two yellow candies}) = P(Y \cap Y) = \frac{3}{10} \times \frac{2}{9} = \frac{6}{90} = \frac{1}{15}$.
> > b) $P(\text{at least one blue candy}) = 1 - P(\text{no blue candies}) = 1 - P(Y \cap Y) = 1 - \frac{1}{15} = \frac{14}{15}$.
> > c) $P(\text{one of each colour}) = P(B \cap Y) + P(Y \cap B) = \left(\frac{7}{10} \times \frac{3}{9}\right) + \left(\frac{3}{10} \times \frac{7}{9}\right) = \frac{21}{90} + \frac{21}{90} = \frac{42}{90} = \frac{7}{15}$.
> > d) $P(\text{no red sweets}) = 1$. (Since there are only blue and yellow candies, it is certain no red sweets will be picked).

### 2.5.2 Conditional Probability Events
In this section, we examine how the information "an event B has occurred" affects the probability assigned to event A. We will use the notation $P(A|B)$ to represent the conditional probability of A given that the event B has occurred. B is the "conditioning event".

For any two events A and B with $P(B)>0$, the conditional probability of A given that the event B has occurred is defined by:
> [!formula] 
> $P(A|B) = \frac{P(A\cap B)}{P(B)}$

When we have dependent events, we must use the general multiplication rule. The general multiplication rule formula is:
> [!formula] 
> $P(A\cap B) = P(A \text{ and } B) = P(A) \times P(B|A)$
> or
> $P(B\cap A) = P(B \text{ and } A) = P(B) \times P(A|B)$

The conditional probability addresses the question of whether one event is dependent on another one. If the probability of event B is not affected by the occurrence of event A, we say that B is independent of A. If, on the other hand, the probability of event B is affected by the occurrence (or not) of event A, we say that B is dependent on A.

If A and B are independent events, then:
> [!formula] 
> $P(A|B) = \frac{P(A\cap B)}{P(B)} = \frac{P(A)\times P(B)}{P(B)} = P(A)$

This is also applied for $P(B|A)$. That is, $P(B|A)=P(B)$.

Concepts and notations for conditional probabilities and intersections can now be related to tree diagrams, as shown below.

Tree diagram notation for events A and B:
![[Pasted image 20260214160222.png]]
* $P(A)\times P(B|A)=P(A\cap B)$
* $P(A)\times P(\overline{B}|A)=P(A\cap\overline{B})$
* $P(\overline{A})\times P(B|\overline{A})=P(\overline{A}\cap B)$
* $P(\overline{A})\times P(\overline{B}|\overline{A})=P(\overline{A}\cap\overline{B})$

> [!example]- Example 2.20
> Suppose that of all individuals buying a certain digital camera, 60% include an optional memory card in their purchase, 40% include an extra battery, and 30% include both a card and battery. Given that the selected individual purchased an extra battery, find the probability that an optional card was also purchased.
>
> > [!continue]- Solution
> > Consider randomly selecting a buyer and let:
> > A = {memory card purchased} and B = {battery purchased}.
> > Then, $P(A)=0.6$, $P(B)=0.4$ and $P(A\cap B)=0.3$.
> > We have $P(A|B)=\frac{P(A\cap B)}{P(B)}=\frac{0.3}{0.4}=0.75$.

> [!example]- Example 2.21
> A child is selected at random from a group of 11 boys and 9 girls, and one of the girls is called Rose. Find the probability that Rose is selected, given that a girl is selected.
>
> > [!continue]- Solution
> > $P(Rose|Girl)=\frac{P(Rose\cap Girl)}{P(Girl)}=\frac{\frac{1}{9}\times\frac{9}{20}}{\frac{9}{20}}=\frac{1}{9}.$

> [!example]- Example 2.22
> Two dice are thrown. What is the probability that the total is 7, given that the total is a prime number?
>
> > [!continue]- Solution
> > $P(\text{total is 7})=\frac{6}{36}$, $P(\text{total is prime number})=\frac{15}{36}.$
> > $P(\text{total is 7}\cap\text{total is prime number})=\frac{6}{36}$
> > $P(\text{total is 7}|\text{total is prime number})=\frac{P(\text{total is 7}\cap\text{total is prime number})}{P(\text{total is prime number})}=\frac{\frac{6}{36}}{\frac{15}{36}}=\frac{2}{5}.$

> [!example]- Example 2.23
> Suppose there are 10 marbles in an urn. 7 are red and 3 are blue. Two marbles are taken without replacement. Find the probability:
> a) the first marble is blue,
> b) the second marble is also blue, given that the first marble is blue.
>
> > [!continue]- Solution
> > a) $n(S)=10,$ $n(B)=3$, $P(B_{1})=\frac{3}{10}$
> > b) $P(B_{2}|B_{1})=\frac{P(B_{2}\cap B_{1})}{P(B_{1})}=\frac{\frac{3}{10}\times\frac{2}{9}}{\frac{3}{10}}=\frac{2}{9}.$

> [!example]- Example 2.24
> A survey was done on the issue of fuel subsidy due to the recent hike in petrol prices. 121 people were surveyed and the results are shown in the table below. *(Note: Text says 99, but data adds to 121)*
> 
> | Respondents | Agree (B) | Disagree ($B^{\prime}$) |
> | :--- | :--- | :--- |
> | Aged $\le$ 35 years (A) | 3 | 33 |
> | Aged > 35 years ($A^{\prime}$) | 80 | 5 |
> 
> Find the probability of selecting:
> a) a respondent aged is above 35 years old.
> b) a respondent aged above 35 years old and agree with the fuel subsidy.
> c) a respondent who agree with the fuel subsidy given he or she is above 35 years old.
> d) a respondent who is above 35 years old or disagree with the fuel subsidy. *(Note: Solved in source as $B'|A$ instead of $A' \cup B'$)*
>
> > [!continue]- Solution
> > a) $P(A^{\prime})=\frac{85}{121}$
> > b) $P(A^{\prime}\cap B)=\frac{80}{121}$
> > c) $P(B|A^{\prime})=\frac{P(B\cap A^{\prime})}{P(A^{\prime})}=\frac{\frac{80}{121}}{\frac{85}{121}}=\frac{16}{17}.$
> > d) $P(B^{\prime}|A)=\frac{P(B^{\prime}\cap A)}{P(A)}=\frac{\frac{33}{121}}{\frac{36}{121}}=\frac{11}{12}.$

> [!sq]- Problem 2.12
> In an annual sales promotion, an emporium offers 20 prizes to be won by 20 lucky winners. The prizes comprise of 4 cars, 6 motorcycles and 10 television sets. Suraya, Sarah and Haleza are three lucky winners. If one person is entitled to win only one prize, calculate the probability that:
> a) either Suraya or Haleza or both won a car,
> b) Suraya won a car and Sarah won either a motorcycle or a television set,
> c) both Sarah and Haleza won a car given that Suraya won a car,
> d) Suraya won a television set given that Haleza won either a car or a motorcycle.
>
> > [!continue]- Solution
> > Let $C, M, T$ denote Car, Motorcycle, and TV. Total prizes = 20 (4C, 6M, 10T).
> > 
> > a) $P(\text{Suraya } C \cup \text{Haleza } C) = P(\text{Suraya } C) + P(\text{Haleza } C) - P(\text{Suraya } C \cap \text{Haleza } C)$
> > $= \frac{4}{20} + \frac{4}{20} - \left(\frac{4}{20} \times \frac{3}{19}\right) = \frac{1}{5} + \frac{1}{5} - \frac{3}{95} = \frac{38}{95} - \frac{3}{95} = \frac{35}{95} = \frac{7}{19}.$
> > 
> > b) $P(\text{Suraya } C \cap \text{Sarah } (M \cup T)) = P(\text{Suraya } C) \times P(\text{Sarah } (M \cup T) | \text{Suraya } C)$
> > $= \frac{4}{20} \times \frac{6+10}{19} = \frac{1}{5} \times \frac{16}{19} = \frac{16}{95}.$
> > 
> > c) $P(\text{Sarah } C \cap \text{Haleza } C | \text{Suraya } C) = \frac{3}{19} \times \frac{2}{18} = \frac{6}{342} = \frac{1}{57}.$
> > 
> > d) $P(\text{Suraya } T | \text{Haleza } (C \cup M))$. Since Haleza took a C or M, all 10 TVs are still available among the remaining 19 prizes.
> > $= \frac{10}{19}.$

> [!sq]- Problem 2.13
> Given that H and K are two independent events such that $P(H)=0.2$ and $P(K)=0.6$
> a) Find $P(H\cup K)$
> b) Calculate $P(H^{\prime}|K^{\prime})$.
>
> > [!continue]- Solution
> > a) Since H and K are independent, $P(H\cap K) = P(H)P(K) = 0.2 \times 0.6 = 0.12$.
> > $P(H\cup K) = P(H) + P(K) - P(H\cap K) = 0.2 + 0.6 - 0.12 = 0.68$.
> > 
> > b) Since H and K are independent, $H^{\prime}$ and $K^{\prime}$ are also independent.
> > $P(H^{\prime}|K^{\prime}) = P(H^{\prime}) = 1 - P(H) = 1 - 0.2 = 0.8$.

> [!sq]- Problem 2.14
> Nizam and Redzuan play each other in an online football match, which consists of up to three games. The winner is the first person to win two games. The probability that Nizam wins the first game is 0.7. Whenever Nizam wins a game, the probability he wins the next is 0.6. Whenever Redzuan wins a game, the probability he wins the next is 0.8. *(Find the probability that Nizam wins the match)*.
>
> > [!continue]- Solution
> > Let N denote Nizam wins and R denote Redzuan wins. Match ends when a player reaches 2 wins.
> > Nizam wins the match in these scenarios: (N, N), (N, R, N), (R, N, N).
> > 
> > $P(N_1, N_2) = P(N_1) \times P(N_2|N_1) = 0.7 \times 0.6 = 0.42$.
> > $P(N_1, R_2, N_3) = P(N_1) \times P(R_2|N_1) \times P(N_3|R_2) = 0.7 \times 0.4 \times 0.2 = 0.056$.
> > $P(R_1, N_2, N_3) = P(R_1) \times P(N_2|R_1) \times P(N_3|N_2) = 0.3 \times 0.2 \times 0.6 = 0.036$.
> > $P(\text{Nizam wins}) = 0.42 + 0.056 + 0.036 = 0.512$.

## 2.6 BAYES' THEOREM
We use Bayes theorem when we want to find the probability of A given B but we are known the opposite probability, the probability of B given A. The formula of Bayes theorem is as follows:

> [!formula] 
> $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$

**Proof:**
$P(B\cap A)=P(A\cap B)$
$P(B|A)P(A)=P(A|B)P(B)$
$P(B|A)=\frac{P(A|B)P(B)}{P(A)}.$

The important of Bayes' theorem is tells us how to 'invert' conditional probabilities, that is to find $P(A|B)$ from $P(B|A)$. In practice, $P(B)$ is often computed using the law of total probability. To find $P(B)$, we can use $P(B)=P(A)\times P(B|A)+P(A^{\prime})\times P(B|A^{\prime})$.

![[Pasted image 20260214160357.png]]


> [!example]- Example 2.25
> There are 12 red balls and 8 green balls in a bucket. Two balls are taken out in sequence without replacement. By using a tree diagram, find the probability that
> a) the first ball is red,
> b) the second one is red if the first is red,
> c) the second one is red if the first is green,
> d) the second ball is red, and
> e) the first one is red if the second is red.
>
> > [!continue]- Solution
> > ![[Pasted image 20260214160422.png]]
> > 
> > 
> > a) $P(R_{1})=\frac{12}{20}=\frac{3}{5}$
> > b) $P(R_{2}|R_{1})=\frac{\frac{11}{19}\times\frac{12}{20}}{\frac{3}{5}}=\frac{11}{19}.$
> > c) $P(R_{2}|G_{1})=\frac{\frac{12}{19}\times\frac{8}{20}}{\frac{8}{20}}=\frac{12}{19}.$
> > d) $P(R_{2})=P(R_{1})\times P(R_{2}|R_{1})+P(G_{1})\times P(R_{2}|G_{1})=\frac{12}{20}\times\frac{11}{19}+\frac{8}{20}\times\frac{12}{19}=\frac{3}{5}$
> > e) $P(R_{1}|R_{2})=\frac{P(R_1 \cap R_2)}{P(R_2)}=\frac{\frac{11}{19}\times\frac{12}{20}}{\frac{3}{5}}=\frac{11}{19}.$

> [!example]- Example 2.26
> It is estimated that 50% of emails are spam emails. Some software has been applied to filter these spam emails before they reach your inbox. A certain brand of software claims that it can detect 99% of spam emails, and the probability for a false positive (a non-spam email detected as spam) is 5%. Now if an email is detected as spam, then what is the probability that it is in fact a non-spam email?
>
> > [!continue]- Solution
> > Let A be the event that an email is detected as spam, and B be the event that an email is spam.
> > $P(B)=0.5,$ $P(B^{\prime})=0.5,$ $P(A|B)=0.99$, $P(A|B^{\prime})=0.05$.
> > $P(B^{\prime}|A)=\frac{P(A|B^{\prime})P(B^{\prime})}{P(A)}=\frac{0.05\times0.5}{(0.5\times0.99)+(0.5\times0.05)}=\frac{5}{104}.$

> [!example]- Example 2.27
> Aisyah is travelling to work by route A or route B. The probability that she chooses route A is $\frac{1}{4}$. The probability that she late for work if she goes via route A is $\frac{2}{3}$ and the corresponding probability if she goes via route B is $\frac{1}{3}$.
> a) What is the probability that Aisyah is late for work on Monday?
> b) Given that Aisyah is late for work, what is the probability that she went via route B?
>
> > [!continue]- Solution
> > ![[Pasted image 20260214160443.png]]
> > 
> > 
> > a) $P(L)=P(A)\times P(L|A)+P(B)\times P(L|B)$
> > $=\frac{1}{4}\times\frac{2}{3}+\frac{3}{4}\times\frac{1}{3}=\frac{5}{12}$
> > 
> > b) $P(B|L)=\frac{P(L|B)P(B)}{P(L)}=\frac{\frac{1}{3}\times\frac{3}{4}}{\frac{5}{12}}=\frac{3}{5}.$

> [!example]- Example 2.28
> At a certain university, 4% of men are over 6 feet tall and 1% of women are over 6 feet tall. The total student population is divided in the ratio 3:2 in favour of women. If a student is selected at random from among all those over six feet tall, what is the probability that the student is a woman?
>
> > [!continue]- Solution
> > Let $M=$ Male student, $F=$ Female student and $T=6$ feet tall students.
> > Thus, we have $P(M) = 2/5$, $P(F)=3/5$, $P(T|M)=4/100$ and $P(T|F)=1/100$. We need to find $P(F|T)$.
> > Using Bayes' theorem we have:
> > $P(F|T)=\frac{P(T|F)P(F)}{P(T|F)P(F)+P(T|M)P(M)}$
> > $=\frac{\frac{1}{100}\times\frac{3}{5}}{\frac{1}{100}\times\frac{3}{5}+\frac{4}{100}\times\frac{2}{5}}=\frac{3}{11}.$

> [!example]- Example 2.29
> A factory production line is manufacturing bolts using three machines, A, B and C. Of the total output, machine A is responsible for 25%, machine B for 35% and machine C for the rest. It is known from previous experience with the machines that 5% of the output from machine A is defective, 4% from machine B and 2% from machine C. A bolt is chosen at random from the production line and found to be defective. What is the probability that it came from machine A?
>
> > [!continue]- Solution
> > Let $D=$ defect bolt, $A=$ is from machine A, $B=$ bolt is from machine B and $C=$ bolt is from machine C. We have $P(A)=0.25,$ $P(B)=0.35$, $P(C)=0.40$.
> > 
> > Also, $P(D|A)=0.05$, $P(D|B)=0.04$ and $P(D|C)=0.02$. We need to find $P(A|D)$.
> > A statement of Bayes' theorem for three events A, B and C is,
> > $P(A|D)=\frac{P(D|A)P(A)}{P(D|A)P(A)+P(D|B)P(B)+P(D|C)P(C)}$
> > $=\frac{0.05\times0.25}{0.05\times0.25+0.04\times0.35+0.02\times0.40}=0.362.$

> [!example]- Example 2.30
> Only 1 in 1000 adults is afflicted with a rare disease for which a diagnostic test has been developed. The test is such that when an individual actually has the disease, a positive result will occur 99% of the time, whereas an individual without the disease will show a positive test result only 2% of the time. If a randomly selected individual is tested and the result is positive, what is the probability that the individual has the disease?
>
> > [!continue]- Solution
> > Let $A=$ individual have disease, $A^{\prime}=$ do not have disease and $B=$ positive test result.
> > Thus, we have $P(A)=0.001$, $P(A^{\prime})=0.999$, $P(B|A)=0.99$, $P(B|A^{\prime})=0.02$. We need to find $P(A|B)$.
> > Hence by the Bayes' formula we have,
> > $P(A|B)=\frac{P(B|A)\times P(A)}{P(B)}=\frac{0.99\times0.001}{(0.001\times0.99)+(0.999\times0.02)}=0.0472.$

> [!sq]- Problem 2.15
> An engineering company advertises a job in three newspapers, A, B and C. It is known that these papers attract undergraduate engineering readerships in the proportions 2:3:1. The probabilities that an engineering undergraduate sees and replies to the job advertisement in these papers are 0.002, 0.001 and 0.005 respectively. Assume that the undergraduate sees only one job advertisement.
> a) If the engineering company receives only one reply to it advertisements, calculate the probability that the applicant has seen the job advertised in place B.
> b) If the company receives two replies, what is the probability that both applicants saw the job advertised in paper A?
>
> > [!continue]- Solution
> > Proportions are 2:3:1, so $P(A)=\frac{2}{6}=\frac{1}{3}$, $P(B)=\frac{3}{6}=\frac{1}{2}$, $P(C)=\frac{1}{6}$.
> > Let $R$ be the event of receiving a reply. $P(R|A)=0.002$, $P(R|B)=0.001$, $P(R|C)=0.005$.
> > Total probability of a reply $P(R) = \left(\frac{1}{3}\right)(0.002) + \left(\frac{1}{2}\right)(0.001) + \left(\frac{1}{6}\right)(0.005) = \frac{0.004 + 0.003 + 0.005}{6} = \frac{0.012}{6} = 0.002$.
> > 
> > a) $P(B|R) = \frac{P(R|B)P(B)}{P(R)} = \frac{0.001 \times \frac{1}{2}}{0.002} = \frac{0.0005}{0.002} = 0.25$.
> > 
> > b) First find $P(A|R)$ for one applicant:
> > $P(A|R) = \frac{P(R|A)P(A)}{P(R)} = \frac{0.002 \times \frac{1}{3}}{0.002} = \frac{1}{3}$.
> > Assuming the two applicants are independent, the probability that BOTH saw it in paper A is $P(A|R) \times P(A|R) = \frac{1}{3} \times \frac{1}{3} = \frac{1}{9}$.

## 2.7 COUNTING RULES
If an event or operation can take place in m ways, and for each of these, the second event or operation can take place in n ways, and then there is a total of $m\times n$ ways of events or operations that can take place. This technique is also known as the multiplication principles. This principle can be extended to cover more than two successive events.

### 2.7.1 Permutation - Multiplication Principles
A permutation is arrangement of a group of objects in a particular order. The order of the objects is taken into consideration. For example, if you have 7 shirts and 5 pants, how many different of shirts and pants can you dress up in? The answer is $7\times5=35$ different of shirts and pants.

> [!example]- Example 2.31
> If there are 4 ways from Johor to Pulau Penang and 2 ways from Pulau Pinang to Pulau Langkawi, how many ways can we go for a journey from Johor to Pulau Langkawi through Pulau Pinang.
>
> > [!continue]- Solution
> > ![[Pasted image 20260214160509.png]]
> > 
> > There are 8 ways for a journey from Johor to Pulau Langkawi through Pulau Pinang.

> [!example]- Example 2.32
> A coin and a dice are tossed together. How many different outcomes are possible?
>
> > [!continue]- Solution
> > For tossing a coin, there are two possible outcomes that are head and tail and denoted as H-head and T-tail. For tossing a dice, there are 6 possible outcomes, {1,2,3,4,5,6}. The number of different possible outcomes is $2\times6=12$. The possible outcomes are:
> > 
> > | Experiment  | Die 1 | 2   | 3   | 4   | 5   | 6   |
> > | :---------- | :---- | :-- | :-- | :-- | :-- | :-- |
> > | Coin H-head | H1    | H2  | H3  | H4  | H5  | H6  |
> > | T-tail      | T1    | T2  | T3  | T4  | T5  | T6  |

> [!example]- Example 2.33
> A shop stocks T-shirts in three sizes: small, medium, large. They are available in four colours: black, red, yellow, green. If the sizes are denoted by S, M, L and the colours are denoted by B, R, Y, G make a list of all the different labels needed to distinguish the T-shirts and find the number of different labels.
>
> > [!continue]- Solution
> > The possible outcomes are:
> > $\{(S,B),(S,R),(S,Y),(S,G),(M,B),(M,R),(M,Y),(M,G),(L,B),(L,R),(L,Y),(L,G)\}$.
> > The number of different possible outcomes is $3\times4=12$.
> > ![[Pasted image 20260214160536.png]]

> [!example]- Example 2.34
> Suppose Aisyah have 3 hats, Hat A, B and C and 2 coats, Coat 1 and 2, in her closet. Assuming that she feels comfortable with wearing any hat with any coat. How many different choices are possible she has?
>
> > [!continue]- Solution
> > Each path on the tree diagram corresponds to a choice of hat and coat. Each of the three branches in step 1 is followed by two branches in step 2, giving us $3\times2=6$ distinct paths.
> > ![[Pasted image 20260214160923.png]]

> [!example]- Example 2.35
> Suppose Ammar want to purchase a tablet computer. He can choose either large or small screen, a 64GB, 128GB or 256GB storage capacity, and a black or white cover. How many different options he has?
>
> > [!continue]- Solution
> > The multiplication principle stated that we can simply multiply the number of options in each category. Thus, there are 12 possible options ($2\times3\times2$). Here are the options:
> > 
> > 1. L-64-B
> > 2. L-64-W
> > 3. L-128-B
> > 4. L-128-W
> > 5. L-256-B
> > 6. L-256-W
> > 7. S-64-B
> > 8. S-64-W
> > 9. S-128-B
> > 10. S-128-W
> > 11. S-256-B
> > 12. S-256-W

### 2.7.2 Permutation - Different Objects
We will now consider the method for finding a number of permutations on the letters A, B and C using the multiplication principle. How many arrangements of the letters A, B and C are there?

Let us consider the number of ways of arranging $n$ letters without repetition.
* If we have 1 letter, there is just one arrangement. Example: A.
* If we have 2 letters, there are two different arrangements. Example: AB and BA.
* If we have 3 letters, the different arrangements are:
  * For choosing the first letter, there are 3 ways.
  * For choosing the second letter, there are 2 ways.
  * For choosing the third letter, there is only 1 way.

![[Pasted image 20260214160616.png]]


Hence, there are $3\times2\times1=6$ ways of arranging the letters A, B and C. Let us consider the following example by using a tree diagram.

If we want to arrange 4 letters, we should be able to see, there will be 24 different ways, which found from $4\times3\times2\times1=24$.

But, if there are 500 different objects, the number of ways would be $500\times499\times...\times2\times1$. This is tedious to write. So, we use the notation $500!$, that is 500 factorials.

In general, the number of permutations of $n$ different objects, taken all at a time without repetition is:
> [!formula] 
> ${}^{n}P_{n}=n\times(n-1)\times(n-2)\times(n-3)\times...\times2\times1=n!$

Symbol $n!$ means the products of all the integers from 1 to $n$ inclusive and called $n$ factorial.

If repetition is allowed, means a letter can be used more than once, we can choose from all 3 letters for each letter of the place. Hence, if repetition is allowed, there are $3\times3\times3=27$ ways of arranging the letters A, B and C.

> [!example]- Example 2.36
> How many three-digit numbers can be made from the integers 2,3,4 without repetition?
> 
> > [!continue]- Solution
> > The number of arrangements is, $3!={}^{3}P_{3}=3\times2\times1=6$.
> > 
> > ![[Pasted image 20260214160637.png]]

> [!example]- Example 2.37
> How many different ways of arranging 3-digit numbers from digit 5 and 6 with repetition?
> 
> > [!continue]- Solution
> > From the tree diagram below, there will be 8 different ways which is found from $2\times2\times2=8$.
> > 
> > ![[Pasted image 20260214160649.png]]

> [!example]- Example 2.38
> In how many ways can ten instructors be assigned to ten sections of a course in Statistics?
> 
> > [!continue]- Solution
> > The number of arrangements is, $10!={}^{10}P_{10}=10\times9\times...\times3\times2\times1=3628800$.

> [!example]- Example 2.39
> Three people, Ammar, Amna and Aisyah must be scheduled for job interviews. In how many different orders of scheduled can be done?
> 
> > [!continue]- Solution
> > The number of different orders can be done is, $3!={}^{3}P_{3}=3\times2\times1=6$.
> > 
> > ![[Pasted image 20260214160702.png]]

> [!example]- Example 2.40
> A Four-digit PIN is selected. What is the probability that there are no repeated digits?
> 
> > [!continue]- Solution
> > We can choose from digit 0 to 9 for 4 times.
> > Therefore, $n(S)=10\times10\times10\times10=10000$. But there is no repetition from the digits. Thus, $n(A)=10\times9\times8\times7=5040$.
> > Hence, the probability that there are no repeated digits is $P(A)=\frac{n(A)}{n(S)}=\frac{5040}{10000}=0.5040$.

> [!example]- Example 2.41
> Find the number of ways the letter 'JOURNALIST'.
> 
> > [!continue]- Solution
> > $10!={}^{10}P_{10}=10\times9\times...\times3\times2\times1=3628800$.

> [!example]- Example 2.42
> Find the number of ways 6 customers can be seated in a row of six chairs.
> 
> > [!continue]- Solution
> > $6!={}^{6}P_{6}=6\times5\times4\times3\times2\times1=720$.

### 2.7.3 Permutation - r Objects Taken From n Different Objects
A permutation of $r$ objects taken from $n$ different objects without repetition is an arrangement of the objects in a specific order. For example, there are 12 permutations for the letters A, B, C and D taken 2 at time.

![[Pasted image 20260214160731.png]]


Using the multiplication principle, the number of permutations of 4 objects taken two at a time, is $4\times3=12$.

In general, the number of permutations of $n$ objects taken $r$ at a time, 
$=n(n-1)(n-2)...(n-r+1)$
$=\frac{n(n-1)(n-2)...(n-r+1)(n-r)(n-r-1)...\times3\times2\times1}{(n-r)(n-r-1)...\times3\times2\times1}=\frac{n!}{(n-r)!}.$

The number of permutations of $r$ objects chosen from a set of $n$ different objects is denoted by,
> [!formula] 
> ${}^{n}P_{r}=\frac{n!}{(n-r)!}$

where $0\le r\le n$.

> [!example]- Example 2.43
> Suppose Amna have 4 different flags. Find how many different signals could she make using,
> a) 2 flags,
> b) 2 or 3 flags.
> 
> > [!continue]- Solution
> > a) The number of different signals can be made using 2 flags is, 
> > ${}^{4}P_{2}=\frac{4!}{(4-2)!}=12$.
> > b) The number of different signals can be made using 2 or 3 flags is, 
> > ${}^{4}P_{2}+{}^{4}P_{3}=\frac{4!}{(4-2)!}+\frac{4!}{(4-3)!}=12+24=36$.

> [!example]- Example 2.44
> Find how many arrangements of the letters of the word BEGIN are there is,
> a) 3 letters are used,
> b) all of the letters are used.
> 
> > [!continue]- Solution
> > a) The number of arrangement if 3 letters use, ${}^{5}P_{3}=60$.
> > b) The number of arrangement if all of the letters are used, ${}^{5}P_{5}=120$.

> [!example]- Example 2.45
> A relay team has 5 members. How many ways can a coach arrange 4 of them to run $4\times100$ m race?
> 
> > [!continue]- Solution
> > The numbers of arrangements the coach can make is ${}^{5}P_{4}=120$.

> [!example]- Example 2.46
> Seven people get into a train but only 4 seats are available. How many different ways for seating of 4 people?
> 
> > [!continue]- Solution
> > The numbers of different ways for seating of 4 people are ${}^{7}P_{4}=840$.

> [!sq]- Problem 2.17
> How many three digits numbers can be made from the integers 2, 3, 4, 5, 6 if:
> a) Each integer is used only once?
> b) There is no restriction on the number of times each integer can be used?
> 
> > [!continue]- Solution
> > The number of available integers is $n=5$. We need to form 3-digit numbers ($r=3$).
> > a) Without repetition: ${}^{5}P_{3} = 5 \times 4 \times 3 = 60$ ways.
> > b) With repetition: $5 \times 5 \times 5 = 125$ ways.

> [!sq]- Problem 2.18
> Find in how many ways can the letter H, A, S, M and R be arranged when:
> a) all the 5 letters are taken at a time without repetition,
> b) 4 of the letters are taken at a time without repetition.
> 
> > [!continue]- Solution
> > The total number of letters is $n=5$.
> > a) 5 letters taken at a time: ${}^{5}P_{5} = 5! = 120$ ways.
> > b) 4 letters taken at a time: ${}^{5}P_{4} = 5 \times 4 \times 3 \times 2 = 120$ ways.

> [!sq]- Problem 2.19
> Find how many arrangements of the letters of the word BEGIN are there if:
> a) 3 letters are used,
> b) all of the letters are used.
> 
> > [!continue]- Solution
> > The word BEGIN has $n=5$ distinct letters.
> > a) 3 letters used: ${}^{5}P_{3} = 5 \times 4 \times 3 = 60$ arrangements.
> > b) All letters used: ${}^{5}P_{5} = 5! = 120$ arrangements.

### 2.7.4 Permutation - With Conditions
Permutation problems sometimes involve conditions. For example, in certain situations, objects may be arranged in a line where two or more objects must be placed together, or certain objects must be placed in certain positions.

> [!example]- Example 2.47
> How many different four-digit numbers which can be formed from the digits 5, 6, 7 and 8?
> a) if no repetitions are allowed,
> b) if the first digit must be 7.
> 
> > [!continue]- Solution
> > a) Total number of digits $=4$. Thus, the total number four-digit can be formed without repetition ${}^{4}P_{4}=4!=24$.
> > b) The total number four-digit can be formed if the first digit must be 7 is,
> > $1 \times {}^{3}P_{3}=6$. *(Note: First position is fixed to '7' (1 way), remaining 3 positions take the 3 remaining digits).*

> [!example]- Example 2.48
> A car registration number consists of 3 different letters (no repetition), followed by 2 digits (repetition allowed), where the first digit cannot be zero. How many different registration numbers can be formed?
> 
> > [!continue]- Solution
> > The first letter can be selected from 26 letters.
> > The second letter can be selected from 25 letters because the letters cannot be the same (no repetition).
> > The third letters selected from 24 letters.
> > The first digit can be selected from 9 digits from 1 to 9 because first digit cannot be zero.
> > The second digit can be selected from 10 digits from 0 to 9 where the digit can be repeated.
> > The total number of different registration numbers can be formed is,
> > $26\times25\times24\times9\times10=1404000$.

> [!example]- Example 2.49
> The letters of the alphabet are combined randomly to form 3-letter code where repetition allowed.
> a) how many 3-letter codes begin with a consonant followed by 2 vowels?
> b) how many 3-letter codes contain exactly one consonant?
> c) how many 3-letter codes begin with a consonant and end with a vowel?
> (Note: The vowels are a, e, i, o and u while the rest of the letters are consonants)
> 
> > [!continue]- Solution
> > a) The first letter can be selected from 21 consonants. The second letter can be selected from 5 vowels. The third letter can be selected from 5 vowels. The total number can be formed is, $21\times5\times5=525$.
> > 
> > b) There are 3 ways:
> > C V V ($21\times5\times5=525$)
> > OR
> > V C V ($5\times21\times5=525$)
> > OR
> > V V C ($5\times5\times21=525$)
> > The total number can be formed is $525+525+525=1575$.
> > 
> > c) C V V ($21\times5\times5=525$)
> > OR
> > C C V ($21\times21\times5=2205$)
> > The total number can be formed is $2205+525=2730$.

> [!example]- Example 2.50
> How many four-digit numbers can be formed out of 0, 1, 2, 3, 5, 7 and 9?
> a) without repetition?
> b) with repetition (can use more than once)?
> 
> > [!continue]- Solution
> > a) The number of ways four-digit numbers can be formed without repetition is, $7\times6\times5\times4=840$.
> > b) The number of ways four-digit numbers can be formed with repetition is, $7\times7\times7\times7=2401$.

> [!example]- Example 2.51
> How many four-digit odd counting numbers can be formed if no repetition of digits is permitted?
> 
> > [!continue]- Solution
> > 
> > | 4-digit | 0,1,2,3,4,5,6,7,8,9 |
> > | :--- | :--- |
> > | Conditions: | Odd, no repetition |
> > | Start where | One's box |
> > | One's box choices | 1, 3, 5, 7, 9: 5 ways |
> > | Thousand's box choices | Remove one's box and 0: 8 ways |
> > | Hundred's box choices | Remove one's and thousand's box and can use 0: 8 ways |
> > | Ten's box choices | Remove one's, thousand's and hundred's box: 7 ways |
> > 
> > The number of ways four-digit odd counting numbers can be formed if no repetition of digits is permitted is $5\times8\times8\times7=2240$.

> [!example]- Example 2.52
> How many odd counting numbers can be formed from the digits 3, 4 and 5 if no repetition is allowed?
> 
> > [!continue]- Solution
> > Using 3, 4 and 5, we can form 1 to 3 digits numbers:
> > * **1-digit**: 3 or 5, 2 ways
> > * **2-digit**: Right box: 3 or 5, 2 ways. Left box: 4 or 3, 2 ways. $2\times2=4$
> > * **3-digit**: Right box: 3 or 5, 2 ways. Middle box: 4 or 3, 2 ways. Left box: 4, 1 way. $2\times2\times1=4$
> > 
> > The number of ways odd counting numbers can be formed from 3, 4 and 5 without repetition is, $2+4+4=10$.

> [!example]- Example 2.53
> How many 3-digit numbers can be made from the integers 2, 3, 4, 5, 6 if,
> a) each integer is used once only?
> b) there is no restriction on the number of times each integer can be used?
> 
> > [!continue]- Solution
> > a) We have 5 choices from 3-digit places, ${}^{5}P_{3}=60$.
> > b) No restriction, repetition allowed, $5\times5\times5=125$.

> [!example]- Example 2.54
> Find the number of arrangements of 4 digits taken from the set {1,2,3,4}. In how many ways can these numbers be arranged so that,
> a) the numbers begin with digit 1,
> b) the number do not begin with digit 1.
> 
> > [!continue]- Solution
> > Total number arrangements of 4 digits are ${}^{4}P_{4}=24$.
> > a) If the arrangements begin with digit 1, then the number of ways the 3 remaining digits can be arranged as, ${}^{1}P_{1}\times{}^{3}P_{3}=6$.
> > b) The arrangements do not begin with digit $1 = 24 - 6 = 18$ ways.
> > ![[Pasted image 20260214160826.png]]
> > Alternative for part b:
> > ![[Pasted image 20260214160858.png]]
> > 
> > (Starts with 2, 3, or 4 $\rightarrow$ ${}^{1}P_{1}\times^{3}P_{3}=6$ each). The arrangements do not begin with digit 1, $6+6+6=18$.

> [!example]- Example 2.55
> Four sisters and two brothers are arranged in different ways in a straight line for several photographs to be taken. How many different arrangements are possible if,
> a) there are no restrictions,
> b) the two brothers must be separated.
> 
> > [!continue]- Solution
> > a) The number of arrangements is possible if there are no restrictions, ${}^{6}P_{6}=720$.
> > 
> > b) The number of arrangements with two brothers next to each other, $2!\times5!=240$.
> > The number of arrangements with two brothers separated, $720-240=480$.
> > 
> > Alternative for part b:
> > Let S represent the sisters and _ represent the spaces for the brothers. Consider the arrangement: _ S _ S _ S _ S _
> > Number of arrangements for the sisters: ${}^{4}P_{4}=24$
> > Number of arrangements for the brothers: ${}^{5}P_{2}=20$ (5 spaces available for 2 brothers)
> > The number of arrangements is possible if the two brothers must be separated is, $24\times20=480$.

> [!example]- Example 2.56
> Arrange 6 boys and 3 girls in a straight line so that the girls are separated. In how many ways can this be done?
> 
> > [!continue]- Solution
> > Let B represent the boys and _ represent the spaces for the girls. Consider the arrangement: _ B _ B _ B _ B _ B _ B _
> > Number of arrangements for the boys: ${}^{6}P_{6}=720$.
> > Number of arrangements for the girls: ${}^{7}P_{3}=210$ (7 spaces available for 3 girls). *(Note: Text says "3 brothers" but context implies girls).*
> > Total number of arrangements of 6 boys and 3 girls where the girls are separated, $720\times210=151200$.

> [!example]- Example 2.57
> There are 10 students out of whom 6 are females. How many possible arrangements are there if
> a) they are arranged in a row,
> b) male always sit together on one side and female sit together on the other side.
> 
> > [!continue]- Solution
> > a) $10!=3628800$.
> > b) $2!\times6!\times4!=34560$.

> [!example]- Example 2.58
> In how many ways can 4 girls and 5 boys sit in a row if the boys and girls must sit alternate next to each other?
> 
> > [!continue]- Solution
> > The number of possible arrangements is there if the boys and girls must sit alternate next to each other is:
> > B G B G B G B G B
> > $5!\times4!=2880$.

> [!example]- Example 2.59
> Find the number of odd three-digit counting numbers that are less than 600 where repetition permitted.
> 
> > [!continue]- Solution
> > 
> > | 3-digit | 0,1,2,3,4,5,6,7,8,9 |
> > | :--- | :--- |
> > | Conditions: | Odd, less than 600, repetition allowed |
> > | Start where | Does not matter |
> > | One's box choices | 1, 3, 5, 7, 9: 5 ways |
> > | Ten's box choices | 0,1,2,3,4,5,6,7,8,9: 10 ways |
> > | Hundred's box choices | 1,2,3,4,5: 5 ways |
> > 
> > The number of ways odd three digit counting numbers that are less than 600 is, $5\times10\times5=250$.

> [!example]- Example 2.60
> How many three-digit counting numbers are there that are less than 300 such that all the digits are even where repetition allowed? 
>
> > [!continue]- Solution
> > | 3-digit | 0,1,2,3,4,5,6,7,8,9 |
> > | :--- | :--- |
> > | **Conditions:** | Less than 300, repetition allowed, all digits are even |
> > | **Start where** | Does not matter |
> > | **One's box choices** | 0,2,4,6,8: 5 ways |
> > | **Ten's box choices** | 0,2,4,6,8: 5 ways |
> > | **Hundred's box choices** | 2: 1 way |
> > 
> > The number of ways three digit counting numbers that are all even and less than 300 is, $5\times5\times1=25$.

> [!example]- Example 2.61
> Four-digit numbers are to be formed from the digits 0, 1, 2, 3, 4, 5 and 6 without repetition. How many numbers can be formed if each number: 
> a) is less than 5000,
> b) begins with the digit 4 or 6,
> c) is between 2000 and 6000,
> d) is an odd number.
>
> > [!continue]- Solution
> > **a) Less than 5000**
> > 
> > | 4-digit | 0,1,2,3,4,5,6 |
> > | :--- | :--- |
> > | **Conditions:** | No repetition, less than 5000 |
> > | **Start where** | Does not matter |
> > | **Thousand's box choices** | 1,2,3,4: 4 ways |
> > | **Hundred's box choices** | 0,1,2,3,5,6: 6 ways |
> > | **Ten's box choices** | 0,1,2,3,5: 5 ways |
> > | **One's box choices** | 0,1,2,3: 4 ways |
> > 
> > The number of ways 4 digit counting numbers that are less than 5000 is $4\times6\times5\times4=480$.
> > 
> > **b) Begins with digit 4 or 6**
> > 
> > | 4-digit | 0,1,2,3,4,5,6 |
> > | :--- | :--- |
> > | **Conditions:** | No repetition, start with 4 or 6 |
> > | **Start where** | Thousand's box |
> > | **Thousand's box choices** | 4: 1 way OR 6: 1 way |
> > | **Hundred's box choices** | 0,1,2,3,5,6: 6 ways OR 0,1,2,3,4,5: 6 ways |
> > | **Ten's box choices** | 0,1,2,3,5: 5 ways OR 0,1,2,3,5: 5 ways |
> > | **One's box choices** | 0,1,2,3: 4 ways OR 0,1,2,3: 4 ways |
> > 
> > The number of ways 4 digit counting numbers that begins with the digit 4 or 6 is, $(1\times6\times5\times4)+(1\times6\times5\times4)=240$.
> > 
> > **c) Between 2000 and 6000**
> > 
> > | 4-digit | 0,1,2,3,4,5,6 |
> > | :--- | :--- |
> > | **Conditions:** | No repetition, between 2000 and 6000 |
> > | **Start where** | Thousand's box |
> > | **Thousand's box choices** | 2,3,4,5: 4 ways |
> > | **Hundred's box choices** | 0,1,3,4,5,6: 6 ways |
> > | **Ten's box choices** | 0,1,3,4,5: 5 ways |
> > | **One's box choices** | 0,1,3,4: 4 ways |
> > 
> > The number of ways 4 digit counting numbers that are between 2000 and 6000 is, $4\times6\times5\times4=480$.
> > 
> > **d) Odd number**
> > 
> > | 4-digit | 0,1,2,3,4,5,6 |
> > | :--- | :--- |
> > | **Conditions:** | No repetition, odd number |
> > | **Start where** | One's box |
> > | **One's box choices** | 1: 1 way OR 3: 1 way OR 5: 1 way |
> > | **Thousand's box choices** | 2,3,4,5,6: 5 ways OR 1,2,4,5,6: 5 ways OR 1,2,3,4,6: 5 ways |
> > | **Hundred's box choices** | 0,3,4,5,6: 5 ways OR 0,2,4,5,6: 5 ways OR 0,2,3,4,6: 5 ways |
> > | **Ten's box choices** | 3,4,5,6: 4 ways OR 2,4,5,6: 4 ways OR 2,3,4,6: 4 ways |
> > 
> > The number of ways 4 digit counting numbers that are odd number is, $(1\times5\times5\times4)+(1\times5\times5\times4)+(1\times5\times5\times4)=300$.

### 2.7.5 Permutation - n Different Objects Comprising Of Identical Objects
We have studied permutations where all of the objects involved were distinct. What happens if some of the objects are indistinguishable? For example, suppose there is a sheet of 12 stickers. If all of the stickers were distinct, there would be 12!. However, 4 of the stickers are identical stars, and 3 are identical moons. Because all of the objects are not distinct, many of the 12! permutations we counted are duplicates . 

The general formula for this situation is as follows:
> [!formula] Formula
> $\frac{n!}{r_{1}!r_{2}!...r_{k}!}$ 

> [!example]- Example 2.62
> How many ways can you arrange the letters of the word STATISTICS? 
>
> > [!continue]- Solution
> > Permutations are indistinguishable objects. There are 3 S's, 3 T's and 2 I's in 10 letters, so there are $\frac{10!}{3!3!2!}=50400$.

> [!example]- Example 2.63
> How many different arrangements are possible in the word BOOKKEEPER? 
>
> > [!continue]- Solution
> > There are 2 O's, 2 K's and 3 E's in 10 letters, so there are, $\frac{10!}{2!2!3!}=151200$.

> [!example]- Example 2.64
> How many different ways can 3 red, 4 yellow and 2 blue bulbs be arranged in a string of Christmas tree lights with 9 sockets? 
>
> > [!continue]- Solution
> > There are 3 red, 4 yellow and 2 blue bulbs in 9 sockets, so there are, $\frac{9!}{3!4!2!}=1260$.

> [!example]- Example 2.65
> A classroom has eight students in it. Three students are wearing red shirts, two are wearing white shirts, two are wearing blue shirts, and one is wearing a green shirt. If the students line up at the door for lunch break, how many ways could the shirt colours be arranged? 
>
> > [!continue]- Solution
> > The number of ways could the shirt colours be arranged is, $\frac{8!}{3!2!2!}=1680$.

> [!example]- Example 2.66
> In how many of the possible permutations of the letters of the word ADDING are the two D's? 
> a) together,
> b) separated.
>
> > [!continue]- Solution
> > a) There are 5 different items A DD ING which can be arranged in $5!=120$.
> > b) Number of arrangements with D's separated = Number of arrangements without restriction - Number of arrangements with D's together,
> > $\frac{6!}{2!}-5!=360 - 120 = 240$ .

### 2.7.6 Combination
A combination is a selection of objects with no consideration given to the order or arrangement of the object. So, while ABC and ACB are different permutations, they are the same combination of letters .

Basic comparison between permutation and combination:

| $n$ | $r$ | Combination | No of combination | Permutation | No of permutation |
| :--- | :--- | :--- | :--- | :--- | :--- |
| A, B | 2 | AB | 1 | AB, BA | 2 |
| A, B, C | 2 | AB, AC, BC | 3 | AB, BA, AC, CA, BC, CB | 6 |
| A, B, C | 3 | ABC | 1 | ABC, ACB, BAC, BCA, CAB, CBA | 6 | 

> [!example]- Example 2.67
> Determine whether each of the following is a permutation or combination.
> a) The arrangement of the letters in word OCTOBER.
> b) 5 pictures places in a row.
> c) 3 story books picked from a rack.
> d) A team of 9 players chosen from a group of 20.
> e) Types of food in a plate taken for lunch consist of rice, vegetables, chicken curry and prawn paste sambal.
> f) Answering questions for Mathematics paper 1.
>
> > [!continue]- Solution
> > P, C, C, P, C, P. *(Note: based on source text exactly).*

### 2.7.7 Combination r Objects Taken From n Different Objects
The number of combinations of $r$ objects from $n$ different objects is denoted by ${}^{n}C_{r}$ where:
> [!formula] Formula
> ${}^{n}C_{r}=\frac{n!}{r!(n-r)!}$ 
> The other notation for ${}^{n}C_{r}$ is $\binom{n}{r}$.

> [!example]- Example 2.68
> There are 4 red balls and 5 blue balls in a bag. 2 balls are picked at random from the bag. Calculate the probability that the 2 balls are of the same colour. 
>
> > [!continue]- Solution
> > The total number of selections of 2 balls from 9 balls is, ${}^{9}C_{2}=36$.
> > The number of selections of both red balls is, ${}^{4}C_{2}=6$.
> > The number of selections of both blue balls is, ${}^{5}C_{2}=10$.
> > Probability that the 2 balls are of the same colour,
> > $P(\text{both red or both blue}) = P(\text{both red}) + P(\text{both blue}) = \frac{6}{36} + \frac{10}{36} = \frac{4}{9}$.

> [!example]- Example 2.69
> There are four letters are to be chosen randomly from the word COMPUTER. Find the probability, 
> a) all the four letters chosen are consonant,
> b) the letter C must be chosen.
>
> > [!continue]- Solution
> > a) $n(S)=^{8}C_{4}=70$, $n(A)=^{5}C_{4}=5$.
> > $P(A)=\frac{5}{70}=\frac{1}{14}$.
> > 
> > b) $n(S)=^{8}C_{4}=70$, $n(B)=^{1}C_{1}\times^{7}C_{3}=35$.
> > $P(B)=\frac{35}{70}=\frac{1}{2}$.

> [!example]- Example 2.70
> A quiz team of four is chosen from group of 15 students. In how many ways could the team be chosen? 
>
> > [!continue]- Solution
> > Therefore, the team can be chosen in, ${}^{15}C_{4}=\frac{15!}{4!(15-4)!}=1365$ ways.

### 2.7.8 Combination - A Set of Objects with Conditions

> [!example]- Example 2.71
> If there are 8 girls and 7 boys in a class, in how many ways could a group be chosen so that there are 2 girls and 2 boys in the group? 
>
> > [!continue]- Solution
> > Two girls can be chosen in ${}^{8}C_{2}$ ways.
> > AND
> > Two boys can be chosen in ${}^{7}C_{2}$ ways.
> > By using multiplication principle, number of ways of selecting the group is, ${}^{8}C_{2}\times^{7}C_{2}=588$ .

> [!example]- Example 2.72
> A school committee consists of 6 girls and 4 boys. A social sub-committee consisting of 4 students is to be formed. In how many ways could the group be chosen if there are to be more girls than boys in the group? 
>
> > [!continue]- Solution
> > If there are to be more girls than boys in the group then the group will either have;
> > 4 girls and no boys can be chosen in ${}^{6}C_{4}\times^{4}C_{0}=15$ ways OR
> > 3 girls and 1 boy can be chosen in ${}^{6}C_{3}\times^{4}C_{1}=80$ ways.
> > Therefore, the number of ways of choosing the group if there are more girls than boys is, $15+80=95$ ways .

> [!example]- Example 2.73
> A student is required to answer 6 out of 8 questions in an examination. 
> a) In how many ways can the student select the questions?
> b) If the student must answer the first 3 questions, in how many ways can he select rest of the questions?
>
> > [!continue]- Solution
> > a) The number of ways student select the questions, ${}^{8}C_{6}=28$ ways.
> > b) If the first 3 questions are compulsory, then the student has to select 3 more from the last 5 questions. So, he has only $^{5}C_{3}=10$ ways .

> [!example]- Example 2.74
> A team of 7 players is to be chosen from a group of 12 players. One of the seven is then to be selected as a captain and another one is to be a vice-captain. In how many ways can this be done? 
>
> > [!continue]- Solution
> > A captain can be chosen in ${}^{7}C_{1}$ ways.
> > A vice-captain can be chosen in ${}^{6}C_{1}$ ways.
> > The number of ways 7 students selected from 12 students is ${}^{12}C_{7}$ ways.
> > Hence, the number of ways is ${}^{7}C_{1}\times^{6}C_{1}\times^{12}C_{7}=33264$ .

> [!example]- Example 2.75
> A committee of 5 persons is to be formed from 10 persons consisting of 4 boys, 4 girls, one male teacher and one female teacher. Find the number of ways to form the committee if: 
> a) the committee must include both teachers,
> b) the committee must have at least 3 males, and
> c) the committee must include the male teacher, 2 boys and 2 females.
>
> > [!continue]- Solution
> > **a)** If male teacher is in the committee that is ${}^{1}C_{1}$.
> > If female teacher is in the committee that is ${}^{1}C_{1}$.
> > There are now 3 persons left to choose from the remaining 8 persons that is ${}^{8}C_{3}$. *(Note: Source typo says ${}^{8}C_{2}$, but context implies 3 persons to make 5)*.
> > Hence, the number of ways is ${}^{1}C_{1}\times^{1}C_{1}\times^{8}C_{3}=56$ .
> > 
> > **b)** There are 5 males and 5 females.
> > 3 males and 2 females chosen in ${}^{5}C_{3}\times^{5}C_{2}=100$ ways OR
> > 4 males and 1 female chosen in ${}^{5}C_{4}\times^{5}C_{1}=25$ ways OR
> > 5 males and 0 female chosen in ${}^{5}C_{5}\times^{5}C_{0}=1$ way. *(Note: Source typo says ${}^{5}C_{0}\times^{5}C_{1}$, corrected for logic)*.
> > Total numbers of ways $100+25+1=126$ .
> > 
> > **c)** The male teacher is already included that is ${}^{1}C_{1}=1$ way.
> > The 2 boys can be chosen in ${}^{4}C_{2}=6$ ways.
> > The 2 females can be chosen in ${}^{5}C_{2}=10$ ways.
> > Hence, the number of ways to form the required committee is $1\times6\times10=60$ ways .

> [!sq]- Problem 2.20
> Out of 7 consonants and 4 vowels, how many words of 3 consonants and 2 vowels can be formed? 
> 
> > [!continue]- Solution
> > Selecting 3 consonants from 7: ${}^{7}C_{3} = 35$ ways.
> > Selecting 2 vowels from 4: ${}^{4}C_{2} = 6$ ways.
> > Total combinations of letters = $35 \times 6 = 210$.
> > To form a "word", the 5 selected letters can be arranged in $5! = 120$ ways.
> > Total words that can be formed = $210 \times 120 = 25200$.

> [!sq]- Problem 2.21
> From a group of 7 men and 6 women, five persons are to be selected to form a committee so that at least 3 men are there in the committee. In how many ways can it be done? 
> 
> > [!continue]- Solution
> > The committee could consist of:
> > * 3 Men and 2 Women: ${}^{7}C_{3} \times {}^{6}C_{2} = 35 \times 15 = 525$ ways.
> > * 4 Men and 1 Woman: ${}^{7}C_{4} \times {}^{6}C_{1} = 35 \times 6 = 210$ ways.
> > * 5 Men and 0 Women: ${}^{7}C_{5} \times {}^{6}C_{0} = 21 \times 1 = 21$ ways.
> > Total number of ways = $525 + 210 + 21 = 756$.

> [!sq]- Problem 2.22
> A bag contains 2 white balls, 3 black balls and 4 red balls. In how many ways can 3 balls be drawn from the bag, if at least one black ball is to be included in the draw? 
> 
> > [!continue]- Solution
> > Total number of balls = 9. Total ways to draw 3 balls = ${}^{9}C_{3} = 84$.
> > Number of ways to draw NO black balls (drawing from the 6 non-black balls) = ${}^{6}C_{3} = 20$.
> > Ways with at least one black ball = Total ways - Ways with no black balls
> > Ways = $84 - 20 = 64$.

> [!sq]- Problem 2.23
> In how many different ways can the letters of the word 'CORPORATION' be arranged so that the vowels always come together? 
> 
> > [!continue]- Solution
> > The word CORPORATION has 11 letters: 6 consonants (C, R, P, R, T, N) and 5 vowels (O, O, A, I, O).
> > Treat the 5 vowels as a single grouped unit. This unit plus the 6 consonants gives 7 units to arrange.
> > Arrangement of the 7 units (with 2 identical R's) = $\frac{7!}{2!} = 2520$ ways.
> > Arrangement of the 5 vowels internally (with 3 identical O's) = $\frac{5!}{3!} = 20$ ways.
> > Total different arrangements = $2520 \times 20 = 50400$ ways.

---

# 2.8 EXERCISE 2

> [!sq]- Question 1
> A fair die is rolled. Find the probabilities of 
> a) obtaining even numbers,
> b) obtaining a 1 or 6,
> c) obtaining a number less than 3.
> 
> > [!continue]- Solution
> > Sample space $S = \{1,2,3,4,5,6\}$, $n(S) = 6$.
> > a) Even numbers $\{2,4,6\}$, $n(A) = 3$. Probability = $\frac{3}{6} = \frac{1}{2}$.
> > b) $\{1, 6\}$, $n(B) = 2$. Probability = $\frac{2}{6} = \frac{1}{3}$.
> > c) Less than 3 $\{1, 2\}$, $n(C) = 2$. Probability = $\frac{2}{6} = \frac{1}{3}$.

> [!sq]- Question 2
> A box contains six red marbles numbered 1 to 6 and ten blue marbles numbered 1 to 10. A marble is drawn at random from the box. Find the probability that the given event occurs. 
> a) The marble is red.
> b) The marble is odd numbered.
> c) The marble is red or odd numbered.
> d) The marble is blue and even numbered.
> 
> > [!continue]- Solution
> > Total marbles $n(S) = 16$.
> > a) Red marbles $n(R) = 6$. $P(\text{Red}) = \frac{6}{16} = \frac{3}{8}$.
> > b) Odd red: {1,3,5}, Odd blue: {1,3,5,7,9}. Total odd $n(O) = 8$. $P(\text{Odd}) = \frac{8}{16} = \frac{1}{2}$.
> > c) $P(R \cup O) = P(R) + P(O) - P(R \cap O) = \frac{6}{16} + \frac{8}{16} - \frac{3}{16} = \frac{11}{16}$.
> > d) Blue and even: {2,4,6,8,10}. $n(B \cap E) = 5$. $P(\text{Blue and Even}) = \frac{5}{16}$.

> [!sq]- Question 3
> In a group of 50 people, 25 own a cat, 15 own a rabbit and five own both a cat and a rabbit. If a person is chosen at random, find the probability that they 
> a) own a cat or a rabbit,
> b) own either a cat or a rabbit but not both,
> c) own a cat given that they own a rabbit.
> 
> > [!continue]- Solution
> > $n(S)=50, n(C)=25, n(R)=15, n(C \cap R)=5$.
> > a) $P(C \cup R) = P(C) + P(R) - P(C \cap R) = \frac{25 + 15 - 5}{50} = \frac{35}{50} = \frac{7}{10}$.
> > b) Own exactly one = $(n(C) - 5) + (n(R) - 5) = 20 + 10 = 30$. $P(\text{only one}) = \frac{30}{50} = \frac{3}{5}$.
> > c) $P(C|R) = \frac{P(C \cap R)}{P(R)} = \frac{5}{15} = \frac{1}{3}$.

> [!sq]- Question 4
> A company is managing two independent tasks. The probability that one of the tasks can be completed before its deadline is 0.3. Find the probability that 
> a) both tasks can be completed before the deadline,
> b) none of the tasks can be completed before the deadline,
> c) one of the tasks can be completed before the deadline,
> d) at least one of the tasks can be completed before the deadline.
> 
> > [!continue]- Solution
> > Let $P(T_1)=0.3$ and $P(T_2)=0.3$.
> > a) $P(\text{both}) = P(T_1 \cap T_2) = 0.3 \times 0.3 = 0.09$.
> > b) $P(\text{none}) = P(T_1^{\prime} \cap T_2^{\prime}) = 0.7 \times 0.7 = 0.49$.
> > c) $P(\text{exactly one}) = P(T_1 \cap T_2^{\prime}) + P(T_1^{\prime} \cap T_2) = (0.3 \times 0.7) + (0.7 \times 0.3) = 0.21 + 0.21 = 0.42$.
> > d) $P(\text{at least one}) = 1 - P(\text{none}) = 1 - 0.49 = 0.51$.

> [!sq]- Question 5
> In how many ways can the letter P, E, R, A, K be arranged without repetition when 
> a) all the 5 letters are taken at a time,
> b) 3 of the letters are taken at a time.
> 
> > [!continue]- Solution
> > a) ${}^{5}P_{5} = 5! = 120$ ways.
> > b) ${}^{5}P_{3} = 5 \times 4 \times 3 = 60$ ways.

> [!sq]- Question 6
> In how many ways can 6 girls and 4 boys be seated in a row if 
> a) the girls and boys can sit anywhere,
> b) the boys must sit together.
> 
> > [!continue]- Solution
> > a) 10 people in total. $10! = 3628800$ ways.
> > b) Treat the 4 boys as 1 unit. 1 unit of boys + 6 girls = 7 units.
> > Arrangements of 7 units = $7!$. Internal arrangements of 4 boys = $4!$.
> > Total ways = $7! \times 4! = 5040 \times 24 = 120960$.

> [!sq]- Question 7
> 7a) Seven chair are arranged in a straight line. In how many ways can three girls sit on these seven chairs? 
> 7b) Arrange 6 boys and 3 girls in a straight line so that the girls are separated. In how many ways can this done. 
> 
> > [!continue]- Solution
> > 7a) We need to select and arrange 3 chairs out of 7 for the girls. ${}^{7}P_{3} = 7 \times 6 \times 5 = 210$ ways.
> > 7b) Arrange the 6 boys: $6! = 720$ ways. This creates 7 spaces between and at the ends of the boys (_ B _ B _ B _ B _ B _ B _). Arrange the 3 girls in these 7 spaces: ${}^{7}P_{3} = 210$ ways.
> > Total ways = $720 \times 210 = 151200$.

> [!sq]- Question 8
> Four-digit numbers are to be formed from the digit 0, 1, 2, 3. 4. 5 and 6 without repetition. How many numbers can be formed if each number 
> a) is less than 5000?
> b) begin with digit 4 or 6?
> c) is between 2000 and 6000?
> d) is an odd number?
> 
> > [!continue]- Solution
> > Digits available: 0, 1, 2, 3, 4, 5, 6 (7 digits).
> > a) First digit must be 1, 2, 3, or 4 (4 choices). Remaining 3 digits chosen from 6 remaining: ${}^{6}P_{3} = 120$. Total = $4 \times 120 = 480$.
> > b) First digit is 4 or 6 (2 choices). Remaining 3 digits: ${}^{6}P_{3} = 120$. Total = $2 \times 120 = 240$.
> > c) First digit must be 2, 3, 4, or 5 (4 choices). Remaining 3 digits: ${}^{6}P_{3} = 120$. Total = $4 \times 120 = 480$.
> > d) Last digit must be 1, 3, or 5 (3 choices). First digit cannot be 0 and cannot be the last digit (5 choices). Remaining 2 digits chosen from remaining 5: ${}^{5}P_{2} = 20$. Total = $3 \times 5 \times 20 = 300$.

> [!sq]- Question 9
> A class contains 9 boys and 3 girls. Find the number of ways a teacher can select a committee of 4; 
> a) there are to be 2 boys and 2 girls,
> b) there is to be exactly one girl.
> 
> > [!continue]- Solution
> > a) Select 2 boys from 9 and 2 girls from 3: ${}^{9}C_{2} \times {}^{3}C_{2} = 36 \times 3 = 108$ ways.
> > b) Select 1 girl from 3 and 3 boys from 9: ${}^{3}C_{1} \times {}^{9}C_{3} = 3 \times 84 = 252$ ways.

> [!sq]- Question 10
> A box contains 6 blue balls and 4 red balls. Find the number of ways 2 ball can be drawn from the box; 
> a) there is no restriction,
> b) they are different colours,
> c) they are to be same colour.
> 
> > [!continue]- Solution
> > a) Total 10 balls. Draw 2: ${}^{10}C_{2} = 45$ ways.
> > b) 1 blue and 1 red: ${}^{6}C_{1} \times {}^{4}C_{1} = 6 \times 4 = 24$ ways.
> > c) 2 blue or 2 red: ${}^{6}C_{2} + {}^{4}C_{2} = 15 + 6 = 21$ ways.

> [!sq]- Question 11
> A candidate is answering a paper in which he can choose 4 questions out of 6. 
> a) In how many ways can this be done?
> b) If the paper is divided into section A and B, each with 3 questions and candidates must choose two questions from each section, in how many ways can this be done?
> 
> > [!continue]- Solution
> > a) ${}^{6}C_{4} = 15$ ways.
> > b) Select 2 from Section A (3) and 2 from Section B (3): ${}^{3}C_{2} \times {}^{3}C_{2} = 3 \times 3 = 9$ ways.

$^{6}C_{4}=\frac{}{}$

> [!sq]- Question 12
> Eight people, of whom A and B are husband and wife, arranged themselves at random in a straight line. What is the probability that; 
> a) A and B are next to each other,
> b) A and B occupy the end positions.
> 
> > [!continue]- Solution
> > Total unrestricted arrangements for 8 people = $8! = 40320$.
> > a) Treat A and B as 1 unit. 7 units total. Arrangements = $7! \times 2! = 10080$.
> > Probability = $\frac{10080}{40320} = \frac{1}{4}$.
> > b) A and B at the ends (2 ways: A...B or B...A). Remaining 6 people arranged in the middle in $6!$ ways. Total = $2 \times 6! = 1440$.
> > Probability = $\frac{1440}{40320} = \frac{1}{28}$.





