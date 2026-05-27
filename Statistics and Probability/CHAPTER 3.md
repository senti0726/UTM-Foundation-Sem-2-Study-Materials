# CHAPTER 3: RANDOM VARIABLES
# 3.0 INTRODUCTION
Variable was defined as a characteristics or attribute that can assume different values. Various letters of alphabet, such as x, y or z are used to represent variables.

For example, if a dice is rolled, a letter such as x, can used to represent the outcomes. Then, the value x can assume is 1, 2, 3, 4, 5 or 6 corresponding to the outcomes of rolling a single dice.

Another example, if two coins are tossed, a letter y can be used to represent the number of heads in this case 0, 1 or 2. Since the variables are associated with probability, they are called random variables.

# 3.1 CONCEPT OF RANDOM VARIABLES
In this chapter, we will discuss about how we can use a rule that assigns to each outcome of a random experiment. Let us begin with the following experiment of tossing a fair coin twice.

The outcomes of the experiment can be listed as a sample space $S=\{HH,HT,TH,TT\}$ where $H=$ Head and $T=Tail$, then can also represented as a variable say, X.

Suppose we are concerned with the number of heads obtained. Thus, each point in the sample space will be assigned a numerical value of 0, 1, 2 and can be tabulated as follows:

| Possible outcomes | HH | HT | TH | TT |
| :--- | :--- | :--- | :--- | :--- |
| Number of Head, X | 2 | 1 | 1 | 0 |


Therefore, the possible values of X are 0, 1, 2. These values are actually random values specified by the possible outcomes obtained from the experiment. These random values are known as random variables.

> [!definition]- Definition:
> A random variable is a function that assigns a numerical value to each simple event in a sample. Capital letters denote random variables such as X or Y and the corresponding small letters, x or y represent particular values of a random variable. A random variable can be discrete or continuous.

> [!example]- Example 3.1
> A coin is thrown for 2 times. State the random variable that can represents the number of heads appear .
>
> > [!continue]- Solution
> > The sample space, $S=\{HH,HT,TH,TT\}$. If X represents the number of heads appear then the possible values of X are $x=\{0,1,2\}$.

> [!example]- Example 3.2
> In order to test the understanding of a student on the concept of statistics, the student is required to answer 2 questions . For a correct answer, he is given 2 marks and 1 mark is subtracted for a wrong answer. If a random variable X represents the total marks obtained, find the possible values of X.
>
> > [!continue]- Solution
> > Let C be the event the answer is correct and W be the event the answer is wrong. The sample space, $S=\{CC,CW,WC,WW\}$ .
> > If X represents the total marks obtained, the possible values of X are $x=\{4,1,-2\}$.

Random variables are classified into discrete and continuous variables. The main difference between the two categories is the type of possible values that each variable can take.
 

## 3.2 DISCRETE RANDOM VARIABLES
A discrete random variable assumes values that can be counted. In other words, the consecutive values of a discrete random variable are separated by a certain gap.

A random variable that assumes countable values and takes positive integer values only is called discrete random variable . Some examples of discrete random variables are:
1. The number of cars sold by a dealer during a given month.
2. The number of employees working in a company.
3. The number of customers in a bank during any given hour.
4. The number of complaints received at the office of an airline on a given day.
5. The number of heads obtained in three tosses of a coin.

A discrete probability distribution is a formula or table which lists all the possible values of discrete random variable with their corresponding probabilities . The probability distribution can be presented in the form of table, function and graph.

For example, the probability distribution for X is summarized in below table:

| X | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $P(X=x)$ | 0.009 | 0.017 | 0.217 | 0.391 | 0.198 | 0.103 | 0.039 | 0.018 | 0.008 |


The discrete probability distribution for X is summarized in below graph:
 ![[Pasted image 20260214150709.png]]

### 3.2.1 Probability Distribution Function
The function that assigns the probabilities to the values is known as probability distribution function of X. Sometimes, the probability distribution function can be expressed as a formula.

A probability distribution of the discrete random variables X, for each possible outcome x will follow below properties:
i. $f(x) \ge 0$.
ii. $\sum_{x} f(x) = 1$.
iii. $P(X=x) = f(x)$.

> [!example]- Example 3.3
> A fair dice is rolled. If X represents the number on the die, show that X is a discrete random variable .
>
> > [!continue]- Solution
> > The possible values of X are $x=\{1,2,3,4,5,6\}$. Thus, the probability for each of values to appear is $\frac{1}{6}$ .
> > That is, $\sum_{i=1}^{6}P(X=x_{i})=\frac{1}{6}(6)=1$, hence X is a discrete random variable.
> > 
> > Since $P(X=1)=\frac{1}{6}$, $P(X=2)=\frac{1}{6}$, $P(X=3)=\frac{1}{6}$, $P(X=4)=\frac{1}{6}$, $P(X=5)=\frac{1}{6}$, $P(X=6)=\frac{1}{6}$ .
> > 
> > The probability distribution of X is:
> > 
> > | X | 1 | 2 | 3 | 4 | 5 | 6 |
> > | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
> > | $P(X=x)$ | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ |

> [!example]- Example 3.4
> If two dice are rolled and a letter Y is used to represent the sum of `the` number shown on dice . Construct the probability distribution function of Y.
>
> > [!continue]- Solution
> > Suppose we roll two dice. The outcomes are as follows:
> > `{(1,1), (1,2), (1,3), (1,4), (1,5), (1,6),` 
> > `(2,1), (2,2), (2,3), (2,4), (2,5), (2,6),` 
> > `(3,1), (3,2), (3,3), (3,4), (3,5), (3,6),` 
> > `(4,1), (4,2), (4,3), (4,4), (4,5), (4,6),` 
> > `(5,1), (5,2), (5,3), (5,4), (5,5), (5,6),` 
> > `(6,1), (6,2), (6,3), (6,4), (6,5), (6,6)}` 
> > 
> > We have $Y=\{2,3,4,5,6,7,8,9,10,11,12\}$, and we will make a table of the probabilities for the sum of the number shown on dice . The probability distribution of Y is:
> > 
> > | $y$ | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
> > | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
> > | $P(Y=y)$ | $\frac{1}{36}$ | $\frac{2}{36}$ | $\frac{3}{36}$ | $\frac{4}{36}$ | $\frac{5}{36}$ | $\frac{6}{36}$ | $\frac{5}{36}$ | $\frac{4}{36}$ | $\frac{3}{36}$ | $\frac{2}{36}$ | $\frac{1}{36}$ |

> [!example]- Example 3.5
> The probability distribution function of a discrete random variable X is given by $P(X=x)=k(4-x)$ for $x=0,1,2,3$ . Find the value of the constant k.
>
> > [!continue]- Solution
> > $\sum P(X=x)=1$ 
> > $k(4-0)+k(4-1)+k(4-2)+k(4-3)=1$ 
> > $10k=1$ 
> > $k=\frac{1}{10}$.

> [!example]- Example 3.6
> The probability distribution function of a discrete random variable X is given by $P(X=x)=kx^{2}$ for $x=0,1,2,3,4$ .
> i. Find the value of the constant k .
> ii. Obtain the probability distribution of X.
>
> > [!continue]- Solution
> > i. $\sum P(X=x)=1$ 
> > $k(0)^{2}+k(1)^{2}+k(2)^{2}+k(3)^{2}+k(4)^{2}=1$ 
> > $30k=1$ 
> > $k=\frac{1}{30}$.
> > 
> > ii. The probability distribution of X,
> > 
> > | x | 0 | 1 | 2 | 3 | 4 |
> > | :--- | :--- | :--- | :--- | :--- | :--- |
> > | $P(X=x)=kx^{2}$ | 0 | $\frac{1}{30}$ | $\frac{4}{30}$ | $\frac{9}{30}$ | $\frac{16}{30}$ |
> > 
> > *Note on inequalities provided in text:*
> > $P(|X-2|<1)=P(-1<X-2<1)$
> > $=P(1<X<3)$
> > $=P(X=2)=\frac{2}{15}$.
> > 
> > If $|x|<a \longrightarrow -a<x<a$ 
> > If $|x|\le a \longrightarrow -a\le x\le a$ 
> > If $|x|>a \longrightarrow x<-a$ or $x>a$ 
> > If $|x|\ge a \longrightarrow x\le-a$ or $x\ge a$ 

> [!example]- Example 3.7
> The discrete random variable Y has a probability, $P(Y=y)=\frac{12-y}{36}$ for $x=0,2,4,6$ .
> i. Construct a probability distribution table of Y.
> ii. $P(Y>2)$.
> iii. Draw a graph for the probability distribution of Y.
>
> > [!continue]- Solution
> > i. The probability distribution of Y,
> > 
> > | Y | 0 | 2 | 4 | 6 |
> > | :--- | :--- | :--- | :--- | :--- |
> > | $P(Y=y)=\frac{12-y}{36}$ | $\frac{1}{3}$ | $\frac{5}{18}$ | $\frac{2}{9}$ | $\frac{1}{6}$ |
> > 
> > ii. $P(Y>2)=P(Y=4)+P(Y=6)=\frac{2}{9}+\frac{1}{6}=\frac{7}{18}$.
> > 
> > iii.  
> > ![[Pasted image 20260214150750.png]]

> [!example]- Example 3.8
> The discrete random variable W has a probability,
> $P(W=w)=\begin{cases}a,&w=0,1\\ a+b,&w=2\\ b,&w=3,4\end{cases}$ 
> If $P(W\le2)=\frac{5}{9}$, find the values of a and b. Hence, draw a graph for the probability distribution of W .
>
> > [!continue]- Solution
> > Given that $P(W\le2)=\frac{5}{9}$, that is $P(W=0)+P(W=1)+P(W=2)=\frac{5}{9}$.
> > $a+a+a+b=\frac{5}{9} \Rightarrow 3a+b=\frac{5}{9}$ 
> > 
> > We have $\sum P(W=w)=1$, then $3a+3b=1$.
> > $\frac{5}{9}+2b=1 \Rightarrow b=\frac{2}{9}$.
> > $3a+\frac{2}{9}=\frac{5}{9} \Rightarrow a=\frac{1}{9}$.
> > 
> > The probability distribution of W:
> > 
> > | W | 0 | 1 | 2 | 3 | 4 |
> > | :--- | :--- | :--- | :--- | :--- | :--- |
> > | $P(W=w)$ | $\frac{1}{9}$ | $\frac{1}{9}$ | $\frac{3}{9}$ | $\frac{2}{9}$ | $\frac{2}{9}$ |
> > 
> > The graph for the probability distribution of W:
> > 
> >  ![[Pasted image 20260214150818.png]]

> [!example]- Example 3.9
> The discrete random variable U has a probability,
> $P(U=u)=\begin{cases}\frac{u}{2k},&u=2,3,5\\ \frac{u}{5k},&u=7,8,10\\ 0,&otherwise.\end{cases}$  *(Note: typos fixed based on context of solution)*
> i. Find the value of k.
> ii. Construct the probability table of U.
> iii. Find $P(4<U\le8)$.
>
> > [!continue]- Solution
> > i. $\sum P(U=u)=1$ 
> > $\frac{2}{2k}+\frac{3}{2k}+\frac{5}{2k}+\frac{7}{5k}+\frac{8}{5k}+\frac{10}{5k}=1$ 
> > $\frac{10}{k}=1$ 
> > $k=10$ 
> > 
> > ii. The probability table of U:
> > 
> > | U | 2 | 3 | 5 | 7 | 8 | 10 |
> > | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
> > | $P(U=u)$ | 0.10 | 0.15 | 0.25 | 0.14 | 0.16 | 0.20 |
> > 
> > iii. $P(4<U\le8)=P(U=5)+P(U=7)+P(U=8)$.
> > $=0.25+0.14+0.16=0.55$.

> [!example]- Example 3.10
> A bag contains 4 red towels and 3 yellow towels. The towels are to be drawn at random one by one without replacement until a piece of red towel is obtained. If X is the total number of towels drawn from the bag,
> i. Obtain the probability distribution of X .
> ii. Find $P(1<X\le3)$.
>
> > [!continue]- Solution
> > The random variable X takes the values 1, 2, 3 and 4. Let R represents the event 'a red towel is drawn', and Y represent the event 'a yellow towel is drawn'.
> > 
> >  ![[Pasted image 20260214150907.png]]
> > 
> > i. The possible values of X are $x=\{1,2,3,4\}$.
> > $P(X=1)=\frac{4}{7}$ 
> > $P(X=2)=\frac{3}{7}\times\frac{4}{6}=\frac{2}{7}$ 
> > $P(X=3)=\frac{3}{7}\times\frac{2}{6}\times\frac{4}{5}=\frac{4}{35}$ 
> > $P(X=4)=\frac{3}{7}\times\frac{2}{6}\times\frac{1}{5}\times1=\frac{1}{35}$ 
> > 
> > The probability distribution of X:
> > 
> > | X | 1 | 2 | 3 | 4 |
> > | :--- | :--- | :--- | :--- | :--- |
> > | $P(X=x)$ | $\frac{4}{7}$ | $\frac{2}{7}$ | $\frac{4}{35}$ | $\frac{1}{35}$ |
> > 
> > ii. $P(1<X\le3)=P(X=2)+P(X=3)$ 
> > $=\frac{2}{7}+\frac{4}{35}=\frac{14}{35}$ 

> [!example]- Example 3.11
> Let x be the number of students participating in statistics competition. The probability distribution function for x is given by $P(X=x)=\frac{x}{45}$ for $x=1,2,3,4,5,6,7,8$ . What is the probability of the number of participants being as follows? 
> i. fewer than 5 students, 
> ii. at most 5 students, 
> iii. exactly 5 students, 
> iv. more than 5 students, 
> v. at least 5 students, 
> vi. between 5 and 7 students, 
> vii. at least 5 but fewer than 7 students, 
> viii. more than 5 but not more 7 students, 
> ix. at least 5 and most 7 students. 
>
> > [!continue]- Solution
> > i. $P(fewer~than~5)=P(X<5)$ 
> > $=P(X=1)+P(X=2)+P(X=3)+P(X=4)$ 
> > $=\frac{1}{45}+\frac{2}{45}+\frac{3}{45}+\frac{4}{45}$ 
> > $=\frac{2}{9}$.
> > [!continue]- Solution (Continued from Example 3.11)
> > **ii. at most 5 students**
> > $P(\text{at most } 5) = P(X \le 5)$
> > $= P(X=1) + P(X=2) + P(X=3) + P(X=4) + P(X=5)$
> > $= \frac{1}{45} + \frac{2}{45} + \frac{3}{45} + \frac{4}{45} + \frac{5}{45} = \frac{15}{45} = \frac{1}{3}$.
> > 
> > **iii. exactly 5 students**
> > $P(\text{exactly } 5) = P(X=5) = \frac{5}{45} = \frac{1}{9}$.
> > 
> > **iv. more than 5 students**
> > $P(\text{more than } 5) = P(X > 5)$
> > $= P(X=6) + P(X=7) + P(X=8)$
> > $= \frac{6}{45} + \frac{7}{45} + \frac{8}{45} = \frac{21}{45} = \frac{7}{15}$.
> > 
> > **v. at least 5 students**
> > $P(\text{at least } 5) = P(X \ge 5)$
> > $= P(X=5) + P(X=6) + P(X=7) + P(X=8)$
> > $= \frac{5}{45} + \frac{6}{45} + \frac{7}{45} + \frac{8}{45} = \frac{26}{45}$.
> > 
> > **vi. between 5 and 7 students**
> > $P(\text{between 5 and 7}) = P(5 < X < 7)$
> > $= P(X=6) = \frac{6}{45} = \frac{2}{15}$.
> > 
> > **vii. at least 5 but fewer than 7 students**
> > $P(\text{at least 5 but fewer than 7}) = P(5 \le X < 7)$
> > $= P(X=5) + P(X=6) = \frac{5}{45} + \frac{6}{45} = \frac{11}{45}$.
> > 
> > **viii. more than 5 but not more than 7 students**
> > $P(\text{more than 5 but not more than 7}) = P(5 < X \le 7)$
> > $= P(X=6) + P(X=7) = \frac{6}{45} + \frac{7}{45} = \frac{13}{45}$.
> > 
> > **ix. at least 5 and at most 7 students**
> > $P(\text{at least 5 and at most 7}) = P(5 \le X \le 7)$
> > $= P(X=5) + P(X=6) + P(X=7) = \frac{5}{45} + \frac{6}{45} + \frac{7}{45} = \frac{18}{45} = \frac{2}{5}$.

> [!sq]- Problem 3.1
> Let the probability function of a discrete random variable X be $f(x)=c(x^{2}+4)$ for $x=0,1,2,3$. If it is a probability distribution, find
> i. the value of c,
> ii. $P(X=1)$
> iii. $P(X\ge2)$.
>
> > [!continue]- Solution
> > **i. Value of c:**
> > $\sum f(x) = 1$
> > $c(0^2+4) + c(1^2+4) + c(2^2+4) + c(3^2+4) = 1$
> > $c(4) + c(5) + c(8) + c(13) = 1$
> > $30c = 1 \Rightarrow c = \frac{1}{30}$.
> > 
> > **ii. $P(X=1)$:**
> > $P(X=1) = \frac{1}{30}(1^2+4) = \frac{5}{30} = \frac{1}{6}$.
> > 
> > **iii. $P(X\ge2)$:**
> > $P(X\ge2) = P(X=2) + P(X=3) = \frac{1}{30}(8) + \frac{1}{30}(13) = \frac{21}{30} = \frac{7}{10}$.

> [!sq]- Problem 3.2
> Determine whether the following is a probability distribution.
> 
> | X | 0 | 1 | 2 | 3 |
> | :--- | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | 0.13 | 0.27 | 0.20 | 0.40 |
> 
> | y | 5 | 6 | 7 | 8 |
> | :--- | :--- | :--- | :--- | :--- |
> | $P(Y=y)$ | 0.40 | 0.10 | 0.60 | -0.10 |
>
> > [!continue]- Solution
> > **For X:**
> > $\sum P(X=x) = 0.13 + 0.27 + 0.20 + 0.40 = 1.00$. 
> > Since $\sum P(X=x) = 1$ and all $P(X=x) \ge 0$, it **is** a probability distribution.
> > 
> > **For Y:**
> > $P(Y=8) = -0.10$. 
> > Since a probability cannot be negative, it **is not** a probability distribution.

> [!sq]- Problem 3.3
> The table show the probability distribution function of the number of statistical workbooks sold per week in a bookstore based on past data. Let X denote the number of statistical workbooks sold per week.
> 
> | X | 0 | 1 | 2 | 3 | 4 |
> | :--- | :--- | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | 0.10 | w | 0.20 | 0.20 | 0.25 |
> 
> a) Find the value of w.
> b) Find the probability that the number of statistical workbooks sold during a given week is:
> i. exactly 2,
> ii. 2 to 4,
> iii. more than 2.
>
> > [!continue]- Solution
> > **a) Value of w:**
> > $\sum P(X=x) = 1$
> > $0.10 + w + 0.20 + 0.20 + 0.25 = 1$
> > $w + 0.75 = 1 \Rightarrow w = 0.25$.
> > 
> > **b) Probabilities:**
> > i. $P(X=2) = 0.20$.
> > ii. $P(2 \le X \le 4) = P(X=2) + P(X=3) + P(X=4) = 0.20 + 0.20 + 0.25 = 0.65$.
> > iii. $P(X > 2) = P(X=3) + P(X=4) = 0.20 + 0.25 = 0.45$.

> [!sq]- Problem 3.4
> Given that
> $P(W=w) = \begin{cases} \frac{-w+12}{40} & , w=0,2,4,6,8 \\ 0 & , \text{elsewhere} \end{cases}$
> i. Show that $P(W=w)$ is a probability distribution function for a discrete random variable W.
> ii. Find the probability distribution of W in a table form.
> iii. Find $P(W\ge3)$.
> iv. Find $P(1<W\le5)$.
>
> > [!continue]- Solution
> > **ii. Probability Distribution Table:**
> > 
> > | W | 0 | 2 | 4 | 6 | 8 |
> > | :--- | :--- | :--- | :--- | :--- | :--- |
> > | $P(W=w)$ | $\frac{12}{40}$ | $\frac{10}{40}$ | $\frac{8}{40}$ | $\frac{6}{40}$ | $\frac{4}{40}$ |
> > 
> > **i. Show it is a probability distribution:**
> > To show it's a probability distribution, $\sum P(W=w)$ must equal 1 and all $P(W=w) \ge 0$.
> > $\sum P(W=w) = \frac{12+10+8+6+4}{40} = \frac{40}{40} = 1$. 
> > All probabilities are positive. Shown.
> > 
> > **iii. $P(W\ge3)$:**
> > $P(W \ge 3) = P(W=4) + P(W=6) + P(W=8) = \frac{8+6+4}{40} = \frac{18}{40} = \frac{9}{20}$.
> > 
> > **iv. $P(1<W\le5)$:**
> > $P(1 < W \le 5) = P(W=2) + P(W=4) = \frac{10}{40} + \frac{8}{40} = \frac{18}{40} = \frac{9}{20}$.

> [!sq]- Problem 3.5
> Given that $P(Y=y)=\frac{y^{2}-8}{132};$ $y=3,5,7,9$.
> i. Show that $P(Y=y)$ is a probability distribution function for a discrete random variable Y.
> ii. Find the probability distribution of Y in a table form.
> iii. Find $P(Y\ge6)$.
> iv. Find $P(4\le Y<8)$
> v. Find $P(Y\le6)$.
>
> > [!continue]- Solution
> > **ii. Probability Distribution Table:**
> > 
> > | Y | 3 | 5 | 7 | 9 |
> > | :--- | :--- | :--- | :--- | :--- |
> > | $P(Y=y)$ | $\frac{1}{132}$ | $\frac{17}{132}$ | $\frac{41}{132}$ | $\frac{73}{132}$ |
> > 
> > **i. Show it is a probability distribution:**
> > $\sum P(Y=y) = \frac{1+17+41+73}{132} = \frac{132}{132} = 1$. 
> > Since all probabilities are $\ge 0$ and sum to 1, it is a valid probability distribution function.
> > 
> > **iii. $P(Y\ge6)$:**
> > $P(Y \ge 6) = P(Y=7) + P(Y=9) = \frac{41+73}{132} = \frac{114}{132} = \frac{19}{22}$.
> > 
> > **iv. $P(4\le Y<8)$:**
> > $P(4 \le Y < 8) = P(Y=5) + P(Y=7) = \frac{17+41}{132} = \frac{58}{132} = \frac{29}{66}$.
> > 
> > **v. $P(Y\le6)$:**
> > $P(Y \le 6) = P(Y=3) + P(Y=5) = \frac{1+17}{132} = \frac{18}{132} = \frac{3}{22}$.

## 3.2.2 Cumulative Distribution Function
The corresponding cumulative frequencies are obtained from a frequency table by summing all the frequencies up to a particular value. The same idea is extended to probability distribution that is the corresponding cumulative probabilities are obtained by summing all the probabilities up to a particular value. The resulting function is known as cumulative distribution function.

> [!definition]- Definition:
> If X is a discrete random variable with probability distribution function, $P(X=x)$ for $x=x_{1},x_{2},...,x_{n}$, then the cumulative distribution function of X is denoted by $F(X)$ is given as
> 
> > [!formula] Formula
> > $F(X)=P(X\le x)=\sum_{x_{i} \le x}P(X=x_{i})$
> 
> > [!tip]- textbook wrong

If we are given the cumulative distribution function of X, that is $F(X)$, we can find the following probability by using the following concept for discrete random variables:

> [!formula] Formula
> $P(X\le a)=F(a)$
> $P(X<a)=F(a-1)$
> $P(X>a)=1-F(a)$
> $P(X\ge a)=1-F(a-1)$
> $P(X=a)=F(a)-F(a-1)$
> $P(a<X<b)=F(b-1)-F(a)$
> $P(a\le X\le b)=F(b)-F(a-1)$
> $P(a<X\le b)=F(b)-F(a)$
> $P(a\le X<b)=F(b-1)-F(a-1)$

The probability distribution can be also obtained from the distribution function. If X has values then the distribution function is as follows:

> [!formula] Formula
> $F(X)=\begin{cases} 0 & x < x_1 \\ P(X=x_1) & x_1 \le x < x_2 \\ P(X=x_1)+P(X=x_2) & x_2 \le x < x_3 \\ \vdots & \vdots \\ P(X=x_1)+...+P(X=x_n) & x \ge x_n \end{cases}$

The cumulative probability distribution function can be graphically illustrated as below:

![[Pasted image 20260214150938.png]]

> [!example]- Example 3.10 (Duplicate)
> The probability distribution function of a discrete random variable X is given by as below:
> $P(X=x)=\begin{cases}0.05,&x=1,6\\ 0.20,&x=2,5\\ 0.25,&x=3,4\\ 0,&\text{otherwise}\end{cases}$
> Find the cumulative distribution function, $F(X)$.
>
> > [!continue]- Solution
> > $x<1 \Rightarrow F(X)=0$
> > $1\le x<2 \Rightarrow F(X)=0+0.05=0.05$
> > $2\le x<3 \Rightarrow F(X)=0.05+0.20=0.25$
> > $3\le x<4 \Rightarrow F(X)=0.25+0.25=0.50$
> > $4\le x<5 \Rightarrow F(X)=0.50+0.25=0.75$
> > $5\le x<6 \Rightarrow F(X)=0.75+0.20=0.95$
> > $x\ge6 \Rightarrow F(X)=0.95+0.05=1$
> > 
> > The cumulative distribution function, $F(X)$:
> > $F(X) = \begin{cases} 0, & x<1 \\ 0.05, & 1\le x<2 \\ 0.25, & 2\le x<3 \\ 0.50, & 3\le x<4 \\ 0.75, & 4\le x<5 \\ 0.95, & 5\le x<6 \\ 1, & x\ge6 \end{cases}$

> [!example]- Example 3.11 (Duplicate)
> The probability distribution function of a discrete random variable Y is given by as below:
> 
> | y | 0 | 1 | 2 | 3 |
> | :--- | :--- | :--- | :--- |
> | $P(Y=y)$ | $\frac{1}{8}$ | $\frac{3}{8}$ | $\frac{3}{8}$ | $\frac{1}{8}$ |
> 
> i. Find the cumulative distribution function, $F(Y)$.
> ii. Sketch the graph for $F(Y)$.
>
> > [!continue]- Solution
> > **i. Cumulative distribution function, $F(Y)$:**
> > $y<0 \Rightarrow F(Y)=0$
> > $0\le y<1 \Rightarrow F(Y)=0+\frac{1}{8}=\frac{1}{8}$
> > $1\le y<2 \Rightarrow F(Y)=\frac{1}{8}+\frac{3}{8}=\frac{1}{2}$
> > $2\le y<3 \Rightarrow F(Y)=\frac{1}{2}+\frac{3}{8}=\frac{7}{8}$
> > $y\ge3 \Rightarrow F(Y)=\frac{7}{8}+\frac{1}{8}=1$
> > 
> > $F(Y) = \begin{cases} 0, & y<0 \\ \frac{1}{8}, & 0\le y<1 \\ \frac{1}{2}, & 1\le y<2 \\ \frac{7}{8}, & 2\le y<3 \\ 1, & y\ge3 \end{cases}$
> > 
> > **ii. The graph of $F(Y)$:**
> > 
> > ![[Pasted image 20260214151001.png]]

> [!example]- Example 3.12
> The cumulative distribution function $F(X)$ of a discrete random variable X is shown as below:
> $F(x)=\begin{cases}0,&x<3\\ 0.3,&3\le x<6\\ 0.7,&6\le x<8\\ 0.9,&8\le x<13\\ 1,&x\ge13\end{cases}$
> 
> Find:
> i. $P(4<x\le6)$
> ii. $P(4\le x\le6)$
> iii. $P(3\le x<8)$
> iv. $P(x>5)$
> v. $P(3<x<6)$
> vi. $P(x\ge7)$
>
> > [!continue]- Solution
> > i. $P(4<x\le6)=F(6)-F(4)=0.7-0.3=0.4$
> > ii. $P(4\le x\le6)=F(6)-F(3)=0.7-0.3=0.4$
> > iii. $P(3\le x<8)=F(7)-F(2)=0.7-0=0.7$
> > iv. $P(x>5)=1-F(5)=1-0.3=0.7$
> > v. $P(3<x<6)=F(5)-F(3)=0.3-0.3=0$
> > vi. $P(x\ge7)=1-F(6)=1-0.7=0.3$

> [!sq]- Problem 3.6
> Given the cumulative distribution table is given as:
> 
> | X | 2 | 3 | 4 | 5 | 6 |
> | :--- | :--- | :--- | :--- | :--- | :--- |
> | $F(X)$ | 0.20 | 0.30 | 0.45 | 0.75 | 1 |
> 
> Find:
> i. $P(X=4)$.
> ii. $P(X<5)$.
>
> > [!continue]- Solution
> > **i. $P(X=4)$:**
> > $P(X=4) = F(4) - F(3) = 0.45 - 0.30 = 0.15$.
> > 
> > **ii. $P(X<5)$:**
> > $P(X<5) = F(4) = 0.45$.

> [!sq]- Problem 3.7
> In a semiconductor manufacturing process, two wafers from a lot are tested. Each wafer is classified as pass or fail. Assume that the probability that a wafer passes the test is 0.8 and that wafers are independent. The random variable X is defined to be the number of wafers that passes the test.
> i. Find the probability function of X.
> ii. Compute $F(X)$
>
> > [!continue]- Solution
> > **i. Probability function of X:**
> > Let X be the number of wafers that pass. Possible values $x = 0, 1, 2$.
> > $P(X=0) = (0.2)(0.2) = 0.04$
> > $P(X=1) = (0.8)(0.2) + (0.2)(0.8) = 0.32$
> > $P(X=2) = (0.8)(0.8) = 0.64$
> > 
> > | X | 0 | 1 | 2 |
> > | :--- | :--- | :--- | :--- |
> > | $P(X=x)$ | 0.04 | 0.32 | 0.64 |
> > 
> > **ii. Compute $F(X)$:**
> > $F(x) = \begin{cases} 0, & x < 0 \\ 0.04, & 0 \le x < 1 \\ 0.36, & 1 \le x < 2 \\ 1, & x \ge 2 \end{cases}$

### 3.2.3 The Probability Distribution Function from The Cumulative Distribution Function
A probability distribution functions can be converted into a cumulative distribution function and vice versa.

> [!example]- Example 3.13
> The cumulative distribution function $F(Y)$ of a discrete random variable Y is given:
> $F(y)=\begin{cases}\frac{2}{21},&0\le y<1\\ \frac{8}{21},&1\le y<2\\ \frac{12}{21},&2\le y<3\\ \frac{17}{21},&3\le y<4\\ 1,&y\ge4\end{cases}$
> Find:
> i. Construct the probability distribution function of Y.
> ii. Sketch the graph of $f(y)$ and $F(y)$.
>
> > [!continue]- Solution
> > **i. Probability distribution function of Y:**
> > For $y=0$, $P(Y=0) = F(0) = \frac{2}{21}$
> > For $y=1$, $P(Y=1) = F(1) - F(0) = \frac{8}{21}-\frac{2}{21}=\frac{6}{21} = \frac{2}{7}$
> > For $y=2$, $P(Y=2) = F(2) - F(1) = \frac{12}{21}-\frac{8}{21}=\frac{4}{21}$
> > For $y=3$, $P(Y=3) = F(3) - F(2) = \frac{17}{21}-\frac{12}{21}=\frac{5}{21}$
> > For $y=4$, $P(Y=4) = F(4) - F(3) = 1-\frac{17}{21}=\frac{4}{21}$
> > 
> > Probability distribution table:
> > 
> > | y | 0 | 1 | 2 | 3 | 4 |
> > | :--- | :--- | :--- | :--- | :--- | :--- |
> > | $P(Y=y)$ | $\frac{2}{21}$ | $\frac{2}{7}$ | $\frac{4}{21}$ | $\frac{5}{21}$ | $\frac{4}{21}$ |
> > 
> > **ii. The graph of the probability distribution:**
> > 
> > ![[Pasted image 20260214151049.png]]
> > ![[Pasted image 20260214151101.png]]

### 3.2.4 Expected Value and Variance
The expected value of a random variable X is mean of X and denoted by $\mu$ or $E(X)$. If X is a discrete random variable with probability distribution function $P(X=x)$, then
> [!formula] Formula
> $\mu = E(X) = \sum x P(X=x)$ 

The expectation of $X^{2}$ is given as:
> [!formula] Formula
> $E(X^{2}) = \sum x^{2}P(X=x)$ 

We know that $E(X)$ is the mean of X where $E(X)=\mu$. Therefore, the variance of X is given by:
> [!formula] Formula
> $\sigma^{2} = Var(X) = E(X-\mu)^{2} = \sum(x-\mu)^{2}P(X=x) = \sum x^{2}P(X=x)-\mu^{2}$ 
> $= E(X^{2}) - [E(X)]^{2}$ 

The standard deviation is $\sigma = \sqrt{Var(X)}$.

The definition of expectation, $E(X) = \mu = \sum_{i=1}^{n}x_{i}P(X=x_{i})$ can be extended to any function of random variable such as 3X, $X^{2}$, $(X-3)^{3}$ etc. If X is a discrete random variable with probability distribution function $P(X=x)$, then the expectation of any function of $X$, is given by:
> [!formula] Formula
> $E[g(X)] = \sum_{\text{all } x}g(X)P(X=x)$ 

### 3.2.5 Properties of Expected Value and Variance
The important properties of expected value, if a and b are constants:
i. $E(a) = a$ 
ii. $E(aX) = aE(X) = a\sum xP(X=x)$ 
iii. $E(aX \pm b) = E(aX) \pm E(b) = aE(X) \pm b = a\sum x P(X=x) \pm b$ 
iv. If $g(x)$ is a function of a discrete random variable X, then the expectation of $g(x)$ is defined as $E[g(x)] = \sum g(x)P(X=x)$.

The important properties of variance, if a and b are constants:
i. $Var(a) = 0$ 
ii. $Var(aX) = a^{2}Var(X)$ 
iii. $Var(aX \pm b) = a^{2}Var(X) \pm Var(b) = a^{2}Var(X)$ 

The above properties of expected value and variance are true for both discrete and continuous random variables.

**Expected Value**

| Rules | Example |
| :--- | :--- |
| $E(c)=c$ where c is a constant. | $E(8)=8$. |
| $E(cX)=c \times E(X)$ | $E(-5X)=-5 \times E(X)=-5E(X)$. |
| $E(cY \pm d)=c \times E(Y) \pm E(d)$ where d is a constant. | $E(4Y-6)=4 \times E(Y)-E(6) = 4E(Y)-6$. *(Note: Variable corrected from X to Y to match rule)* |
| $E(c[g(x)])=c \times E[g(x)]$. | Let $g(x)=7x+2$, $E([g(x)])=E(7x+2) = 7 \times E(X)+E(2) = 7E(X)+2$. |


**Variance**

| Rules | Example |
| :--- | :--- |
| $Var(c)=0$ where c is a constant. | $Var(-3)=0$. |
| $Var(cX)=c^{2} \times Var(X)$. | $Var(-5X)=(-5)^{2} \times Var(X)=25Var(X)$. |
| $Var(cY \pm d)=c^{2} \times Var(Y) \pm Var(d)$ where d is a constant. | $Var(4Y-6)=4^{2} \times Var(Y)-Var(6) = 16Var(Y)$. *(Note: Variable corrected from X to Y to match rule)* |


> [!example]- Example 3.14
> The probability distribution of a discrete random variable X is given as follows:
> 
> | x | 1 | 2 | 3 |
> | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | $\frac{2}{7}$ | $\frac{4}{7}$ | $\frac{1}{7}$ |
> 
> Calculate:
> i. $E(X)$.
> ii. $Var(X)$.
> iii. $E(5X^{2}+X-1)$.
>
> > [!continue]- Solution
> > i. $E(X)=\sum xP(X=x)$
> > $=1(\frac{2}{7})+2(\frac{4}{7})+3(\frac{1}{7}) = \frac{13}{7}.$ 
> > 
> > ii. $Var(X)=E(X^{2})-[E(X)]^{2}$
> > $=\sum x^{2}P(X=x)-(\frac{13}{7})^{2}$
> > $=(1^{2}(\frac{2}{7})+2^{2}(\frac{4}{7})+3^{2}(\frac{1}{7}))-(\frac{13}{7})^{2}$
> > $=\frac{27}{7}-(\frac{13}{7})^{2}=\frac{20}{49}.$ 
> > 
> > iii. $E(5X^{2}+X-1)=5E(X^{2})+E(X)-E(1)$
> > $=5(\frac{27}{7})+\frac{13}{7}-1=\frac{142}{49}$  *(Note: value for $E(X^2)$ corrected from 20/49 to 27/7 based on calculation step)*.

> [!example]- Example 3.15
> The probability distribution of a discrete random variable X is given as follows:
> 
> | X | 1 | 2 | 3 |
> | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | $\frac{1}{6}$ | $\frac{2}{6}$ | $\frac{3}{6}$ |
> 
> Calculate:
> i. $E(2)$
> ii. $E(X)$.
> iii. $E(5X)$.
> iv. $E(5X+2)$
>
> > [!continue]- Solution
> > i. $E(2)=2$. 
> > 
> > ii. $E(X)=1(\frac{1}{6})+2(\frac{2}{6})+3(\frac{3}{6})=\frac{7}{3}.$ 
> > 
> > iii. $E(5X)=5E(X)=5(\frac{7}{3})=\frac{35}{3}$ 
> > 
> > iv. $E(5X+2)=E(5X)+E(2)=5E(X)+2=5(\frac{7}{3})+2=\frac{41}{3}.$ 

> [!example]- Example 3.16
> The probability distribution of a discrete random variable X is given as follows:
> 
> | x | 1 | 2 | 3 | 4 |
> | :--- | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | $\frac{1}{16}$ | $\frac{1}{2}$ | $\frac{1}{4}$ | $\frac{3}{16}$ |
> 
> Calculate:
> i. $Var(X)$.
> ii. $Var(X-2)$.
> iii. $Var(5-8X)$.
>
> > [!continue]- Solution
> > i. $Var(X)=[1^{2}(\frac{1}{16})+2^{2}(\frac{1}{2})+3^{2}(\frac{1}{4})+4^{2}(\frac{3}{16})]-[1(\frac{1}{16})+2(\frac{1}{2})+3(\frac{1}{4})+4(\frac{3}{16})]^{2}$
> > $=\frac{117}{16}-(\frac{41}{16})^{2} = \frac{191}{256}$ 
> > 
> > ii. $Var(X-2)=Var(X)-Var(2)$
> > $=\frac{191}{256}-0 = \frac{191}{256}$ 
> > 
> > iii. $Var(5-8X)=Var(-8X+5)$
> > $=(-8)^{2}Var(X)+Var(5)$
> > $=64(\frac{191}{256})=\frac{191}{4}.$ 

> [!sq]- Problem 3.8
> The probability function of random variable X is given by as follows:
> $f(x)=c(x+1)^{2}$; $x=0,1,2,3$
> i. Find the value of c.
> ii. Compute $F(X)$.
> iii. Find $E(X)$ and $Var(X)$.
>
> > [!continue]- Solution
> > **i. Find the value of c:**
> > Since it is a probability distribution function, $\sum f(x) = 1$.
> > $c(0+1)^2 + c(1+1)^2 + c(2+1)^2 + c(3+1)^2 = 1$
> > $c(1) + c(4) + c(9) + c(16) = 1$
> > $30c = 1 \Rightarrow c = \frac{1}{30}$.
> > 
> > **ii. Compute $F(X)$:**
> > The probabilities are $P(0)=\frac{1}{30}, P(1)=\frac{4}{30}, P(2)=\frac{9}{30}, P(3)=\frac{16}{30}$.
> > $F(x) = \begin{cases} 0 & , x < 0 \\ \frac{1}{30} & , 0 \le x < 1 \\ \frac{5}{30} = \frac{1}{6} & , 1 \le x < 2 \\ \frac{14}{30} = \frac{7}{15} & , 2 \le x < 3 \\ 1 & , x \ge 3 \end{cases}$
> > 
> > **iii. Find $E(X)$ and $Var(X)$:**
> > $E(X) = \sum x P(X=x) = 0(\frac{1}{30}) + 1(\frac{4}{30}) + 2(\frac{9}{30}) + 3(\frac{16}{30}) = \frac{0 + 4 + 18 + 48}{30} = \frac{70}{30} = \frac{7}{3}$.
> > $E(X^2) = \sum x^2 P(X=x) = 0(\frac{1}{30}) + 1(\frac{4}{30}) + 4(\frac{9}{30}) + 9(\frac{16}{30}) = \frac{0 + 4 + 36 + 144}{30} = \frac{184}{30} = \frac{92}{15}$.
> > $Var(X) = E(X^2) - [E(X)]^2 = \frac{92}{15} - (\frac{7}{3})^2 = \frac{92}{15} - \frac{49}{9} = \frac{276 - 245}{45} = \frac{31}{45}$.

> [!sq]- Problem 3.9
> The random variable Y, representing the number of customers at Marry Brown Taman Pulai Perdana from 8:00 pm to 9:00 pm on a given day has the following probability distribution:
> 
> | y | 2 | 3 | 4 | 5 | 6 |
> | :--- | :--- | :--- | :--- | :--- | :--- |
> | $P(Y=y)$ | 0.01 | 0.25 | 0.40 | 0.30 | 0.04 |
> 
> i. Verify whether this is a probability distribution.
> ii. Find $P(Y>3)$.
> iii. Find $P(2<Y<5)$.
> iv. Find $E(Y)$ and $Var(Y)$
>
> > [!continue]- Solution
> > **i. Verify probability distribution:**
> > Sum of probabilities $= 0.01 + 0.25 + 0.40 + 0.30 + 0.04 = 1.00$. Since the sum is 1 and all $P(Y=y) \ge 0$, this is a valid probability distribution.
> > 
> > **ii. $P(Y>3)$:**
> > $P(Y>3) = P(Y=4) + P(Y=5) + P(Y=6) = 0.40 + 0.30 + 0.04 = 0.74$.
> > 
> > **iii. $P(2<Y<5)$:**
> > $P(2<Y<5) = P(Y=3) + P(Y=4) = 0.25 + 0.40 = 0.65$.
> > 
> > **iv. $E(Y)$ and $Var(Y)$:**
> > $E(Y) = 2(0.01) + 3(0.25) + 4(0.40) + 5(0.30) + 6(0.04) = 0.02 + 0.75 + 1.60 + 1.50 + 0.24 = 4.11$.
> > $E(Y^2) = 4(0.01) + 9(0.25) + 16(0.40) + 25(0.30) + 36(0.04) = 0.04 + 2.25 + 6.40 + 7.50 + 1.44 = 17.63$.
> > $Var(Y) = 17.63 - (4.11)^2 = 17.63 - 16.8921 = 0.7379$.

> [!sq]- Problem 3.10
> Let X be a random variable with the following probability distribution.
> 
> | X | 4 | 8 | 12 |
> | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | $\frac{1}{8}$ | $\frac{4}{8}$ | $\frac{3}{8}$ |
> 
> i. Find $E(X)$.
> ii. Let $g(x)=2X+3$, compute $E[g(X)]$ and $Var[g(X)]$.
>
> > [!continue]- Solution
> > **i. Find $E(X)$:**
> > $E(X) = 4(\frac{1}{8}) + 8(\frac{4}{8}) + 12(\frac{3}{8}) = \frac{4 + 32 + 36}{8} = \frac{72}{8} = 9$.
> > 
> > **ii. Compute $E[g(X)]$ and $Var[g(X)]$:**
> > $E[g(X)] = E(2X+3) = 2E(X) + 3 = 2(9) + 3 = 18 + 3 = 21$.
> > To find $Var[g(X)]$, first find $Var(X)$:
> > $E(X^2) = 16(\frac{1}{8}) + 64(\frac{4}{8}) + 144(\frac{3}{8}) = \frac{16 + 256 + 432}{8} = \frac{704}{8} = 88$.
> > $Var(X) = E(X^2) - [E(X)]^2 = 88 - (9)^2 = 88 - 81 = 7$.
> > $Var[g(X)] = Var(2X+3) = 2^2 \times Var(X) = 4(7) = 28$.

> [!sq]- Problem 3.11
> A random variable X has probability distribution function $T(X)$ given by:
> $T(X)=\frac{x-1}{m}$ ; $x=2,3,4,5,6$, m is a constant.
> i. Construct the cumulative distribution function of X.
> ii. Find $P(3\le X\le5)$
> iii. Find $E(X)$ and $Var(X)$
>
> > [!continue]- Solution
> > First, find m using $\sum T(X) = 1$.
> > $\frac{1}{m} + \frac{2}{m} + \frac{3}{m} + \frac{4}{m} + \frac{5}{m} = 1 \Rightarrow \frac{15}{m} = 1 \Rightarrow m=15$.
> > 
> > **i. Cumulative distribution function of X:**
> > $F(x) = \begin{cases} 0 & , x < 2 \\ \frac{1}{15} & , 2 \le x < 3 \\ \frac{3}{15} = \frac{1}{5} & , 3 \le x < 4 \\ \frac{6}{15} = \frac{2}{5} & , 4 \le x < 5 \\ \frac{10}{15} = \frac{2}{3} & , 5 \le x < 6 \\ 1 & , x \ge 6 \end{cases}$
> > 
> > **ii. Find $P(3\le X\le5)$:**
> > $P(3\le X\le5) = P(X=3) + P(X=4) + P(X=5) = \frac{2}{15} + \frac{3}{15} + \frac{4}{15} = \frac{9}{15} = \frac{3}{5}$.
> > 
> > **iii. Find $E(X)$ and $Var(X)$:**
> > $E(X) = 2(\frac{1}{15}) + 3(\frac{2}{15}) + 4(\frac{3}{15}) + 5(\frac{4}{15}) + 6(\frac{5}{15}) = \frac{2 + 6 + 12 + 20 + 30}{15} = \frac{70}{15} = \frac{14}{3}$.
> > $E(X^2) = 4(\frac{1}{15}) + 9(\frac{2}{15}) + 16(\frac{3}{15}) + 25(\frac{4}{15}) + 36(\frac{5}{15}) = \frac{4 + 18 + 48 + 100 + 180}{15} = \frac{350}{15} = \frac{70}{3}$.
> > $Var(X) = \frac{70}{3} - (\frac{14}{3})^2 = \frac{210}{9} - \frac{196}{9} = \frac{14}{9}$.

> [!sq]- Problem 3.12
> A box contains nine numbered balls. Two balls are numbered 2, three balls are numbered 3 and four balls numbered are numbered 4. Two balls are selected at random without replacement. Let X be the sum of the numbers on the selected balls. The probability distribution of X, is shown in the table below:
> 
> | X | 4 | 5 | 6 | 7 | 8 |
> | :--- | :--- | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | a | b | c | $\frac{1}{3}$ | $\frac{1}{6}$ |
> 
> i. Show that $a=\frac{1}{36}$ and $b=\frac{1}{36}$ *(Note factual error in text below)*. Hence, find the value of c.
> ii. Show that $E(X)=\frac{58}{9}$. Hence, find $E(4-\frac{1}{2}X).$
>
> > [!continue]- Solution
> > > [!tip]- Textbook Factual error: The question states to show $b = 1/36$, but based on the problem conditions, $b = P(X=5) = 1/6$. We will use the correct value $b=1/6$ for subsequent calculations.
> > Total balls = 9. Total ways to pick 2 balls without replacement = ${}^{9}C_{2} = 36$.
> > **i. Show values and find c:**
> > For $X=4$, the balls must be (2, 2). Number of ways = ${}^{2}C_{2} = 1$.
> > $a = P(X=4) = \frac{1}{36}$. (Shown).
> > For $X=5$, the balls must be (2, 3). Number of ways = ${}^{2}C_{1} \times {}^{3}C_{1} = 2 \times 3 = 6$.
> > $b = P(X=5) = \frac{6}{36} = \frac{1}{6}$.
> > Since $\sum P(X=x) = 1$:
> > $a + b + c + \frac{1}{3} + \frac{1}{6} = 1$
> > $\frac{1}{36} + \frac{6}{36} + c + \frac{12}{36} + \frac{6}{36} = 1$
> > $\frac{25}{36} + c = 1 \Rightarrow c = \frac{11}{36}$.
> > 
> > **ii. Show $E(X)=\frac{58}{9}$ and find $E(4-\frac{1}{2}X)$:**
> > $E(X) = 4(\frac{1}{36}) + 5(\frac{6}{36}) + 6(\frac{11}{36}) + 7(\frac{12}{36}) + 8(\frac{6}{36})$
> > $E(X) = \frac{4 + 30 + 66 + 84 + 48}{36} = \frac{232}{36} = \frac{58}{9}$. (Shown).
> > $E(4-\frac{1}{2}X) = 4 - \frac{1}{2}E(X) = 4 - \frac{1}{2}(\frac{58}{9}) = 4 - \frac{29}{9} = \frac{36}{9} - \frac{29}{9} = \frac{7}{9}$.

## 3.3 CONTINUOUS RANDOM VARIABLES
A random variable whose values are not countable is called a continuous random variable. A continuous random variable can be represented by an interval on a number line and takes on an uncountable infinite number of possible values.

Examples of continuous random variables:
1. The weight of lecturer in Math's Unit.
2. Time taken by workers to learn a particular job.
3. The height of students in a college.

### 3.3.1 Probability Density Function
A continuous random variable is specified by its probability density function which written as $f(x)$. This function is defined as over the $(-\infty,\infty)$ range. Therefore, the continuous random variable and its probability distribution cannot be given in tabular form.

For example, if we are talking about the probability of selecting a student with weight less than 50kg or at least 45kg, we are dealing with an interval rather than a point value of a random variable.

Note that when X is continuous random variable,
$P(a<X\le b)=P(a<X<b)+P(X=b)=P(a<X<b)$, because $P(X=b)=0$ . The probability of any particular value of the random variable is zero. We do not have to worry about the equal sign .

> [!definition]- Definition:
> The function $f(x)$ is a probability density function for the continuous random variable X, defined over the set of real numbers $\mathbb{R}$ if:
> i. $f(x) \ge 0$, for all $x \in \mathbb{R}$.
> ii. $\int_{-\infty}^{\infty}f(x)dx=1;$ the total area under the entire graph of $f(x)$ is equal to 1.
> iii. The probability that X is between two numbers a and b is equal to the area under between a and b that implies:
> $P(a \le X \le b) = P(a \le X < b) = P(a < X \le b) = P(a < X < b) = \int_{a}^{b}f(x)dx.$

Remember, we do not have to worry about equal sign.
Figure shows, if X is a continuous random variable with probability density function $f(x)$ then $P(a\le X\le b)=\int_{a}^{b}f(x)dx$.
![[Pasted image 20260214154025.png]]

Notice that $\int_{a}^{b}f(x)dx$ is in fact the area enclosed by the curve $y=f(x)$, x-axis, the line between $x=a$ and $x=b$. For example, $P(-1<X<2)=\int_{-1}^{2}f(x)dx$ .

![[Pasted image 20260214154101.png]]

The graph of continuous probability distribution can be sketch as below:
$f(x)=\begin{cases}\frac{x}{12},&1\le x\le5\\ 0&,otherwise\end{cases}$ 
 
![[Pasted image 20260214154118.png]]

> [!example]- Example 3.17
> X is the delay, in hours, of a flight from Chicago, where $f(x)=0.2-0.02x$, $0\le x\le10$. Find the probability that the delay will be less than four hours.
>
> > [!continue]- Solution
> > $P(X<4)=\int_{0}^{4}0.2-0.02x~dx$
> > $=[0.2x-0.02\frac{x^{2}}{2}]_{0}^{4}$
> > $=0.64-0=0.64$. 

> [!example]- Example 3.18
> A continuous random variable X has probability density function $f(x)=kx^{3}$, $0\le x\le4$. Find,
> i. the value of k,
> ii. $P(1\le X\le3)$,
> iii. $P(X>2)$.
>
> > [!continue]- Solution
> > i. the value of k,
> > $\int_{-\infty}^{\infty}f(x)dx=1 \Rightarrow \int_{0}^{4}kx^{3}dx=1$
> > $[k\frac{x^{4}}{4}]_{0}^{4}=1$
> > $64k=1 \Rightarrow k=\frac{1}{64}.$ 
> > 
> > ii. $P(1\le X\le3)=\int_{1}^{3}\frac{x^{3}}{64}dx=[\frac{x^{4}}{256}]_{1}^{3}=\frac{81}{256}-\frac{1}{256}=\frac{5}{16}.$ 
> > 
> > iii. $P(X>2)=\int_{2}^{4}\frac{x^{3}}{64}dx=[\frac{x^{4}}{256}]_{2}^{4}=1-\frac{16}{256}=\frac{15}{16}.$  *(Note: Denominator corrected from 4 to 64 based on integral step)*.

> [!example]- Example 3.19
> A continuous random variable X has probability density function $f(x)=\frac{1}{4}(4-x)$, $1\le x\le3$ .
> i. Sketch the graph of $f(x)$ and verify that it satisfies the conditions of a probability density function.
> ii. $P(X<2)$.
>
> > [!continue]- Solution
> > i. $\int_{-\infty}^{\infty}f(x)dx=1$
> > $\int_{1}^{3}\frac{1}{4}(4-x)dx=[x-\frac{x^{2}}{8}]_{1}^{3}$
> > $=(3-\frac{9}{8})-(1-\frac{1}{8})=1.$ 
> >  
> > ![[Pasted image 20260214154157.png]]
> > 
> > ii. $P(X<2)=\int_{1}^{2}\frac{1}{4}(4-x)dx$
> > $=[x-\frac{x^{2}}{8}]_{1}^{2}=\frac{3}{2}-\frac{7}{8}=\frac{5}{8}.$ 

> [!example]- Example 3.20
> A random variable X has probability density function $f(x)$ as follows:
> $f(x)=\begin{cases}\frac{3x^{2}}{16},&-2\le x\le2\\ 0,&\text{otherwise}\end{cases}$ 
> Find $P(|X|>\frac{3}{2}).$
>
> > [!continue]- Solution
> > $P(|X|>\frac{3}{2}) = P(X<-\frac{3}{2})$ or $P(X>\frac{3}{2})$
> > $= P(X<-\frac{3}{2}) + P(X>\frac{3}{2})$
> > $= \int_{-2}^{-\frac{3}{2}}\frac{3x^{2}}{16}dx + \int_{\frac{3}{2}}^{2}\frac{3x^{2}}{16}dx$
> > $= [\frac{x^{3}}{16}]_{-2}^{-\frac{3}{2}} + [\frac{x^{3}}{16}]_{\frac{3}{2}}^{2}$
> > $= (-\frac{27}{128}-(-\frac{1}{2})) + (\frac{1}{2}-\frac{27}{128}) = \frac{37}{64}.$  *(Note: integration limits corrected based on context of absolute value rule).*
> > 
> > **ii. at most 5 students**
> > $P(\text{at most } 5) = P(X \le 5)$
> > $= P(X=1) + P(X=2) + P(X=3) + P(X=4) + P(X=5)$
> > $= \frac{1}{45} + \frac{2}{45} + \frac{3}{45} + \frac{4}{45} + \frac{5}{45} = \frac{15}{45} = \frac{1}{3}$.
> > 
> > **iii. exactly 5 students**
> > $P(\text{exactly } 5) = P(X=5) = \frac{5}{45} = \frac{1}{9}$.
> > 
> > **iv. more than 5 students**
> > $P(\text{more than } 5) = P(X > 5)$
> > $= P(X=6) + P(X=7) + P(X=8)$
> > $= \frac{6}{45} + \frac{7}{45} + \frac{8}{45} = \frac{21}{45} = \frac{7}{15}$.
> > 
> > **v. at least 5 students**
> > $P(\text{at least } 5) = P(X \ge 5)$
> > $= P(X=5) + P(X=6) + P(X=7) + P(X=8)$
> > $= \frac{5}{45} + \frac{6}{45} + \frac{7}{45} + \frac{8}{45} = \frac{26}{45}$.
> > 
> > **vi. between 5 and 7 students**
> > $P(\text{between 5 and 7}) = P(5 < X < 7)$
> > $= P(X=6) = \frac{6}{45} = \frac{2}{15}$.
> > 
> > **vii. at least 5 but fewer than 7 students**
> > $P(\text{at least 5 but fewer than 7}) = P(5 \le X < 7)$
> > $= P(X=5) + P(X=6) = \frac{5}{45} + \frac{6}{45} = \frac{11}{45}$.
> > 
> > **viii. more than 5 but not more than 7 students**
> > $P(\text{more than 5 but not more than 7}) = P(5 < X \le 7)$
> > $= P(X=6) + P(X=7) = \frac{6}{45} + \frac{7}{45} = \frac{13}{45}$.
> > 
> > **ix. at least 5 and at most 7 students**
> > $P(\text{at least 5 and at most 7}) = P(5 \le X \le 7)$
> > $= P(X=5) + P(X=6) + P(X=7) = \frac{5}{45} + \frac{6}{45} + \frac{7}{45} = \frac{18}{45} = \frac{2}{5}$.

> [!example]- Example 3.21
> A random variable X has probability density function $f(x)$ as follows:
> $$f(x)=\begin{cases}k(x+1),&0\le x\le2\\ 2k,&2\le x\le3\\ 0,&\text{otherwise}\end{cases}$$
> Find $k$ and sketch the probability density function graph. Hence, find $P(X>1.8)$.
>
> > [!continue]- Solution
> > $\int_{-\infty}^{\infty}f(x)dx=1 \Rightarrow \int_{0}^{2}k(x+1)dx+\int_{2}^{3}2k~dx=1$
> > $[\frac{x^{2}k}{2}+kx]_{0}^{2}+[2kx]_{2}^{3}=1$
> > $4k+2k=1 \Rightarrow 6k=1 \Rightarrow k=\frac{1}{6}.$
> > 
> > $P(X>1.8)=\int_{1.8}^{2}\frac{x+1}{6}dx+\int_{2}^{3}\frac{1}{3}dx=[\frac{x^{2}}{12}+\frac{x}{6}]_{1.8}^{2}+[\frac{x}{3}]_{2}^{3}$
> > $=(\frac{2}{3}-\frac{57}{100})+(1-\frac{2}{3})$
> > $=\frac{29}{300}+\frac{1}{3}=\frac{43}{100}.$
> > 
> > 
> > ![[Pasted image 20260214154706.png]]

> [!sq]- Problem 3.13
> Let the probability density function of a random variable Y be,
> $$g(y)=\begin{cases}cy(1-y),&0<y<1\\ 0.5,&2<y<3\\ 0,&\text{otherwise}\end{cases}$$
> i. Find the value of $c$.
> ii. Compute $P(0.5\le Y\le2.5)$ and $P(Y\ge2)$
> 
> > [!continue]- Solution
> > **i. Find the value of c:**
> > $\int_{-\infty}^{\infty} g(y) dy = 1 \Rightarrow \int_{0}^{1} c(y - y^2) dy + \int_{2}^{3} 0.5 dy = 1$
> > $c[\frac{y^2}{2} - \frac{y^3}{3}]_{0}^{1} + [0.5y]_{2}^{3} = 1$
> > $c(\frac{1}{2} - \frac{1}{3}) + 0.5(3 - 2) = 1$
> > $c(\frac{1}{6}) + 0.5 = 1 \Rightarrow \frac{c}{6} = 0.5 \Rightarrow c = 3$.
> > 
> > **ii. Compute probabilities:**
> > $P(0.5 \le Y \le 2.5) = \int_{0.5}^{1} 3(y - y^2) dy + \int_{2}^{2.5} 0.5 dy$
> > $= 3[\frac{y^2}{2} - \frac{y^3}{3}]_{0.5}^{1} + [0.5y]_{2}^{2.5}$
> > $= 3 \left[ (\frac{1}{2} - \frac{1}{3}) - (\frac{(0.5)^2}{2} - \frac{(0.5)^3}{3}) \right] + 0.5(2.5 - 2)$
> > $= 3 \left[ \frac{1}{6} - (\frac{1}{8} - \frac{1}{24}) \right] + 0.25$
> > $= 3 \left[ \frac{1}{6} - \frac{2}{24} \right] + 0.25 = 3(\frac{1}{12}) + 0.25 = 0.25 + 0.25 = 0.5$.
> > 
> > $P(Y \ge 2) = \int_{2}^{3} 0.5 dy = [0.5y]_{2}^{3} = 1.5 - 1 = 0.5$.

> [!sq]- Problem 3.14
> The total number of hours, measured in units of 100 hours, that a family runs a vacuum cleaner over period of one year is a continuous random variable X that has the density function;
> $$f(x)=\begin{cases}x,&0<x<1\\ 2-x,&1\le x<2\\ 0,&\text{otherwise}\end{cases}$$
> Find the probability that over a period of one year, a family runs their vacuum cleaner:
> i. less than 120 hours.
> ii. between 50 and 100 hours.
> 
> > [!continue]- Solution
> > Note: X is in units of 100 hours.
> > **i. less than 120 hours ($X < 1.2$):**
> > $P(X < 1.2) = \int_{0}^{1} x dx + \int_{1}^{1.2} (2-x) dx$
> > $= [\frac{x^2}{2}]_{0}^{1} + [2x - \frac{x^2}{2}]_{1}^{1.2}$
> > $= 0.5 + (2(1.2) - \frac{1.44}{2}) - (2(1) - \frac{1}{2})$
> > $= 0.5 + (2.4 - 0.72) - 1.5 = 0.5 + 1.68 - 1.5 = 0.68$.
> > 
> > **ii. between 50 and 100 hours ($0.5 < X < 1$):**
> > $P(0.5 < X < 1) = \int_{0.5}^{1} x dx = [\frac{x^2}{2}]_{0.5}^{1}$
> > $= \frac{1}{2} - \frac{(0.5)^2}{2} = 0.5 - 0.125 = 0.375$.

### 3.3.2 Cumulative Distribution Function
The probability of a continuous random variable is obtained by integration, so is its cumulative distribution function $F(X)$.
If X is a continuous random variable with probability density function $f(x)$ for $-\infty<x<\infty$, then the cumulative distribution function of X is given by,

> [!formula] 
> $F(x)=P(X\le x)=\int_{-\infty}^{x}f(t)dt.$

Some important properties of the cumulative distribution function are as follows:
i. $F(-\infty)=0$ and $F(\infty)=1$.
ii. $P(X<a)=P(X\le a)=F(a)$.
iii. $P(a\le X\le b)=P(a\le X<b)=P(a<X\le b)=P(a<X<b)$
$=\int_{a}^{b}f(x)dx$
$=\int_{-\infty}^{b}f(x)dx-\int_{-\infty}^{a}f(x)dx$
$=F(b)-F(a)$.

$F(X)$ is in fact given by the area under the curve $y=f(x)$ from $-\infty$ to $x$ as indicated by the shaded region.

![[Pasted image 20260214154737.png]]

The graph of cumulative distribution function for the continuous random variables from the earlier example can be sketched as below:
$$F(x)=\begin{cases}0,&x<0\\ 0.5x^{2},&0\le x\le1\\ 0.5,&1< x\le1.5\\ x-1,&1.5< x\le2\\ 1,&x>2\end{cases}$$


![[Pasted image 20260214154758.png]]

> [!example]- Example 3.22
> The continuous random variable $X$ has the following cumulative distribution function,
> $$F(x)=\begin{cases} 0, & x<0 \\ \frac{x^{2}}{4}, & 0\le x<1 \\ -\frac{x^{2}}{4}+x-\frac{1}{4}, & 1\le x<2 \\ \frac{x}{4}+\frac{1}{4}, & 2\le x<3 \\ 1, & x\ge3 \end{cases}$$
> Find: 
> i. $P(X\le\frac{3}{2}),$
> ii. $P(X>\frac{3}{2}),$
> iii. $P(\frac{1}{2}<X<\frac{3}{2})$
>
> > [!continue]- Solution
> > i. $P(X\le\frac{3}{2})=F(\frac{3}{2})=-\frac{(\frac{3}{2})^{2}}{4}+(\frac{3}{2})-\frac{1}{4}=-\frac{9}{16}+\frac{24}{16}-\frac{4}{16}=\frac{11}{16}.$
> > 
> > ii. $P(X>\frac{3}{2})=1-P(X\le\frac{3}{2})$
> > $=1-F(\frac{3}{2})$
> > $=1-\frac{11}{16}=\frac{5}{16}.$
> > 
> > iii. $P(\frac{1}{2}<X<\frac{3}{2})=F(\frac{3}{2})-F(\frac{1}{2})$
> > $=\frac{11}{16}-\frac{(\frac{1}{2})^2}{4}$
> > $=\frac{11}{16}-\frac{1}{16}$
> > $=\frac{10}{16}=\frac{5}{8}.$
> > 
> > > [!tip]- Textbook Factual error: The original text contained calculation errors in part iii which have been corrected here

### 3.3.3 The Probability Density Function from The Cumulative Distribution Function
Since the cumulative distribution function is the integral of the probability density function, it follows that the probability density function of a continuous random variable is the derivative of the cumulative distribution.
That is,

> [!formula] 
> $f(x)=\frac{d}{dx}[F(x)]$

> [!example]- Example 3.23
> The continuous random variable X has the following density function:
> $$f(x)=\begin{cases}\frac{1}{12}x,&0\le x<4\\ -\frac{1}{6}x+1,&4\le x<6\\ 0,&\text{otherwise}\end{cases}$$
> Find:
> i. Find the cumulative distribution function, $F(x)$.
> ii. Sketch the graph $f(x)$ and $F(x)$.
>
> > [!continue]- Solution
> > **i. Find the cumulative distribution function, $F(x)$:**
> > For $x<0$, 
> > $F(x)=\int_{-\infty}^{x}0~dx=0.$
> > 
> > For $0\le x<4$, 
> > $F(x)=\int_{-\infty}^{0}0~dx+\int_{0}^{x}\frac{1}{12}t~dt=0+[\frac{t^{2}}{24}]_{0}^{x}=\frac{x^{2}}{24}.$
> > 
> > For $4\le x<6$, 
> > $F(x)=\int_{-\infty}^{0}0~dx+\int_{0}^{4}\frac{1}{12}t~dt+\int_{4}^{x}(-\frac{1}{6}t+1)dt$
> > $=0+[\frac{t^{2}}{24}]_{0}^{4}+[-\frac{t^{2}}{12}+t]_{4}^{x}$
> > $=0+(\frac{16}{24}-0)+((-\frac{x^{2}}{12}+x)-(-\frac{16}{12}+4))$
> > $=\frac{2}{3}-\frac{x^{2}}{12}+x-(-\frac{4}{3}+4)$
> > $=-\frac{x^{2}}{12}+x-2.$
> > 
> > For $x\ge6$, 
> > $F(x)=\int_{-\infty}^{0}0~dx+\int_{0}^{6}\frac{1}{12}t~dt+\int_{4}^{6}(-\frac{1}{6}t+1)dt+\int_{6}^{x}0~dt=0+(\frac{2}{3}-0)+(3-\frac{8}{3})+0=1.$
> > 
> > The cumulative distribution function is,
> > $$F(x)=\begin{cases}0,&x<0\\ \frac{x^{2}}{24},&0\le x<4\\ -\frac{x^{2}}{12}+x-2,&4\le x<6\\ 1,&x\ge6\end{cases}$$
> > 
> > **ii. Sketch the graph $f(x)$ and $F(x)$:**
> > 
> > ![[Pasted image 20260214154842.png]]
> > ![[Pasted image 20260214154859.png]]

> [!example]- Example 3.24
> The continuous random variable X has the following cumulative function:
> $$F(x)=\begin{cases}0,&x<2\\ \frac{1}{20}x-\frac{1}{10},&2\le x<4\\ \frac{x}{10}+\frac{3}{10},&4\le x<13\\ 1,&x\ge13\end{cases}$$
> Find:
> i. Find the probability density function, $f(x)$.
> ii. Sketch the graph $f(x)$ and $F(x)$.
>
> > [!continue]- Solution
> > **i. Probability density function, $f(x)$:**
> > For $x<2$, $f(x)=\frac{d}{dx}(0)=0.$
> > For $2\le x<4$, $f(x)=\frac{d}{dx}(\frac{1}{20}x-\frac{1}{10})=\frac{1}{20}.$
> > For $4\le x<13$, $f(x)=\frac{d}{dx}(\frac{x}{10}+\frac{3}{10})=\frac{1}{10}.$
> > For $x\ge13$, $f(x)=\frac{d}{dx}(1)=0.$
> > 
> > The probability density function is,
> > $$f(x)=\begin{cases}\frac{1}{20},&2\le x<4\\ \frac{1}{10},&4\le x<13\\ 0,&\text{otherwise}\end{cases}$$
> > 
> > **ii. Sketch the graph $f(x)$ and $F(x)$:**
> > ![[Pasted image 20260214155001.png]]
> > ![[Pasted image 20260214155011.png]]

### 3.3.4 Expected Value and Variance
Expectation or the expected value of a continuous random variable X with probability density function $f(x)$, is the mean of X and is denoted by $\mu$ or $E(X)$.
> [!formula] 
> $E(X)=\int_{-\infty}^{\infty}x~f(x)dx$

If X is a continuous random variable with probability density function $f(x)$, then the expectation of any function of X, $g(x)$ is given by
> [!formula] 
> $E[g(X)]=\int_{-\infty}^{\infty}g(x)f(x)dx$

In particular, when $g(x)=X^{2}$;
> [!formula] 
> $E[X^{2}]=\int_{-\infty}^{\infty}x^{2}f(x)dx$

> [!example]- Example 3.25
> The continuous random variable X has the following cumulative function:
> > [!tip]- Textbook Factual error: The text states "cumulative function" but provides probability density function $f(x)$
> $$f(x)=\begin{cases}\frac{x}{6},&0\le x<2\\ \frac{1}{3},&2\le x<4\\ 0,&\text{otherwise}\end{cases}$$
> Find:
> i. $E(2X+1)$,
> ii. $2E(3X+1)$,
> iii. $E(X+1)^{2}$.
>
> > [!continue]- Solution
> > First, find $E(X)$:
> > $E(X)=\int_{-\infty}^{\infty}xf(x)dx$
> > $=\int_{0}^{2}x(\frac{x}{6})dx+\int_{2}^{4}x(\frac{1}{3})dx$
> > $=[\frac{x^{3}}{18}]_{0}^{2}+[\frac{x^{2}}{6}]_{2}^{4}$
> > $=\frac{8}{18}+(\frac{16}{6}-\frac{4}{6}) = \frac{4}{9}+2 = \frac{22}{9}.$
> > 
> > **i. $E(2X+1)$:**
> > $E(2X+1)=2E(X)+1$
> > $=2(\frac{22}{9})+1=\frac{44}{9}+1=\frac{53}{9}.$
> > 
> > **ii. $2E(3X+1)$:**
> > > [!tip]- Textbook Factual error: The question asks for $2E(3X+1)$ but the solution calculates for $2E(3X+2)$
> > $2E(3X+2)=2[3E(X)+2]$
> > $=2[3(\frac{22}{9})+2]=2[\frac{22}{3}+2]=2[\frac{28}{3}]=\frac{56}{3}.$
> > 
> > **iii. $E(X+1)^{2}$:**
> > $E(X^{2})=\int_{-\infty}^{\infty}x^{2}f(x)dx$
> > $=\int_{0}^{2}x^{2}(\frac{x}{6})dx+\int_{2}^{4}x^{2}(\frac{1}{3})dx$
> > $=[\frac{x^{4}}{24}]_{0}^{2}+[\frac{x^{3}}{9}]_{2}^{4}$
> > $=\frac{16}{24}+(\frac{64}{9}-\frac{8}{9})=\frac{2}{3}+\frac{56}{9}=\frac{62}{9}.$
> > 
> > $E(X+1)^{2}=E(X^{2}+2X+1)$
> > $=E(X^{2})+2E(X)+1$
> > $=\frac{62}{9}+2(\frac{22}{9})+1=\frac{106}{9}+1=\frac{115}{9}.$

> [!example]- Example 3.26
> The continuous random variable X has the following cumulative function: 
> > [!tip]- Textbook Factual error: The text states "cumulative function" but provides probability density function $f(x)$
> $$f(x)=\begin{cases}\frac{3}{2}(1-x^{2}),&0\le x\le1\\ 0,&\text{otherwise}\end{cases}$$
> Find:
> i. $Var(X)$,
> ii. $2Var(4X)$,
> iii. $Var(3X+2)$,
> iv. $Var(Y)$ if $Y=2X-1$.
>
> > [!continue]- Solution
> > First calculate $E(X)$ and $E(X^2)$:
> > $E(X)=\int_{-\infty}^{\infty}xf(x)dx$
> > $=\int_{0}^{1}x\cdot\frac{3}{2}(1-x^{2})dx$
> > $=\frac{3}{2}\int_{0}^{1}(x-x^{3})dx$
> > $=\frac{3}{2}[\frac{x^{2}}{2}-\frac{x^{4}}{4}]_{0}^{1}$
> > $=\frac{3}{2}[(\frac{1}{2}-\frac{1}{4})-0]=\frac{3}{2}(\frac{1}{4})=\frac{3}{8}.$
> > 
> > $E(X^{2})=\int_{-\infty}^{\infty}x^{2}f(x)dx$
> > $=\int_{0}^{1}x^{2}\cdot\frac{3}{2}(1-x^{2})dx$
> > $=\frac{3}{2}\int_{0}^{1}(x^{2}-x^{4})dx$
> > $=\frac{3}{2}[\frac{x^{3}}{3}-\frac{x^{5}}{5}]_{0}^{1}$
> > $=\frac{3}{2}[(\frac{1}{3}-\frac{1}{5})-0]=\frac{3}{2}(\frac{2}{15})=\frac{1}{5}.$
> > 
> > **i. $Var(X)$:**
> > $Var(X)=E(X^{2})-[E(X)]^{2}$
> > $=(\frac{1}{5})-(\frac{3}{8})^{2}=\frac{1}{5}-\frac{9}{64}=\frac{64-45}{320}=\frac{19}{320} \approx 0.059.$
> > 
> > **ii. $2Var(4X)$:**
> > $2Var(4X)=2[(4)^{2}Var(X)]$
> > $=2[16\times0.059]=32\times0.059=1.888$.
> > 
> > **iii. $Var(3X+2)$:**
> > $Var(3X+2)=(3)^{2}Var(X)$
> > $=9\times0.059=0.531$.
> > 
> > **iv. $Var(Y)$ if $Y=2X-1$:**
> > > [!tip]- Textbook Factual error: The text states $Y=2X-1$ but the solution calculates for $Var(2X+1)$
> > $Var(Y)=Var(2X+1)$
> > $=(2)^{2}Var(X)$
> > $=4\times0.059=0.236.$



---

# 3.4 EXERCISE 3

> [!sq]- Question 1
> The following table shows the probability distribution of a discrete random variable X
> 
> | X | 0 | 1 | 2 | 3 | 4 |
> | :--- | :--- | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | $\frac{1}{3}$ | $\frac{7}{18}$ | $\frac{1}{9}$ | $\frac{1}{9}$ | $\frac{1}{18}$ |
> 
> i. Show that X is a discrete random variable. Write down the probability distribution function.
> ii. Sketch the graph of probability distribution function.
> iii. Find: $P(X=2)$, $P(X>2)$, $P(X\le3)$ and $P(0<X\le3)$.
> 
> > [!continue]- Solution
> > **i. Show X is a discrete random variable & Write probability distribution function:**
> > To show X is a discrete random variable, the sum of all probabilities must equal 1.
> > $\sum P(X=x) = \frac{1}{3} + \frac{7}{18} + \frac{1}{9} + \frac{1}{9} + \frac{1}{18}$
> > $= \frac{6}{18} + \frac{7}{18} + \frac{2}{18} + \frac{2}{18} + \frac{1}{18} = \frac{18}{18} = 1$. (Shown).
> > 
> > The probability distribution function is:
> > $$f(x) = \begin{cases} \frac{1}{3}, & x=0 \\ \frac{7}{18}, & x=1 \\ \frac{1}{9}, & x=2,3 \\ \frac{1}{18}, & x=4 \\ 0, & \text{otherwise} \end{cases}$$
> > 
> > **ii. Sketch the graph:**
> > 
> > 
> > **iii. Find Probabilities:**
> > $P(X=2) = \frac{1}{9}$.
> > $P(X>2) = P(X=3) + P(X=4) = \frac{1}{9} + \frac{1}{18} = \frac{2}{18} + \frac{1}{18} = \frac{3}{18} = \frac{1}{6}$.
> > $P(X\le3) = 1 - P(X=4) = 1 - \frac{1}{18} = \frac{17}{18}$.
> > $P(0<X\le3) = P(X=1) + P(X=2) + P(X=3) = \frac{7}{18} + \frac{1}{9} + \frac{1}{9} = \frac{7+2+2}{18} = \frac{11}{18}$.

> [!sq]- Question 2
> The discrete random variable X has the following probability distribution function.
> $$f(x)=\begin{cases}\frac{1}{5}x,&x=1,2\\ \frac{3}{10},&x=3,4\\ 0,&\text{otherwise}\end{cases}$$
> Find:
> i. the cumulative distribution function $F(x)$ and sketch its graph.
> ii. $P(X\le3)$,
> iii. $P(X<2)$,
> iv. $P(1<X<4)$,
> v. $P(X\ge2)$.
> 
> > [!continue]- Solution
> > **i. Cumulative distribution function $F(x)$:**
> > First find the probabilities: $P(1)=\frac{1}{5}=\frac{2}{10}$, $P(2)=\frac{2}{5}=\frac{4}{10}$, $P(3)=\frac{3}{10}$, $P(4)=\frac{3}{10}$.
> > > [!tip]- Textbook Factual error: The sum of probabilities is $\frac{2+4+3+3}{10} = 1.2$, which is greater than 1. Thus, $f(x)$ is not a valid probability distribution function. Evaluating as given despite the error.
> > $$F(x) = \begin{cases} 0 & , x < 1 \\ 0.2 & , 1 \le x < 2 \\ 0.6 & , 2 \le x < 3 \\ 0.9 & , 3 \le x < 4 \\ 1.2 & , x \ge 4 \end{cases}$$
> > [EditHere - Graph of F(x) for Question 2]
> > 
> > **ii. $P(X\le3)$:**
> > $P(X\le3) = P(1) + P(2) + P(3) = 0.2 + 0.4 + 0.3 = 0.9$.
> > 
> > **iii. $P(X<2)$:**
> > $P(X<2) = P(1) = 0.2$.
> > 
> > **iv. $P(1<X<4)$:**
> > $P(1<X<4) = P(2) + P(3) = 0.4 + 0.3 = 0.7$.
> > 
> > **v. $P(X\ge2)$:**
> > $P(X\ge2) = P(2) + P(3) + P(4) = 0.4 + 0.3 + 0.3 = 1.0$.

> [!sq]- Question 3
> The cumulative distribution function $F(x)$ of a discrete random variable X is defined as follows.
> $$F(x)=\begin{cases}0,&x<1\\ \frac{1}{8},&1\le x<2\\ \frac{2}{8},&2\le x<3\\ \frac{5}{8},&3\le x<4\\ 1,&x\ge4\end{cases}$$
> Find:
> a)i. $P(X\le2)$,
> a)ii. $P(X>2)$,
> a)iii. $P(X=3)$,
> a)iv. $P(1<X\le3)$,
> a)v. $P(2\le X<4)$.
> b) the probability distribution function $f(x)$ and sketch the graph of $f(x)$ and $F(x)$.
> 
> > [!continue]- Solution
> > **a) Find Probabilities:**
> > i. $P(X\le2) = F(2) = \frac{2}{8} = \frac{1}{4}$.
> > ii. $P(X>2) = 1 - P(X\le2) = 1 - F(2) = 1 - \frac{2}{8} = \frac{6}{8} = \frac{3}{4}$.
> > iii. $P(X=3) = F(3) - F(2) = \frac{5}{8} - \frac{2}{8} = \frac{3}{8}$.
> > iv. $P(1<X\le3) = F(3) - F(1) = \frac{5}{8} - \frac{1}{8} = \frac{4}{8} = \frac{1}{2}$.
> > v. $P(2\le X<4) = P(X=2) + P(X=3) = (F(2) - F(1)) + (F(3) - F(2)) = F(3) - F(1) = \frac{5}{8} - \frac{1}{8} = \frac{4}{8} = \frac{1}{2}$.
> > 
> > **b) Probability distribution function $f(x)$:**
> > $f(1) = F(1) - F(0) = \frac{1}{8} - 0 = \frac{1}{8}$
> > $f(2) = F(2) - F(1) = \frac{2}{8} - \frac{1}{8} = \frac{1}{8}$
> > $f(3) = F(3) - F(2) = \frac{5}{8} - \frac{2}{8} = \frac{3}{8}$
> > $f(4) = F(4) - F(3) = 1 - \frac{5}{8} = \frac{3}{8}$
> > $$f(x) = \begin{cases} \frac{1}{8}, & x=1, 2 \\ \frac{3}{8}, & x=3, 4 \\ 0, & \text{otherwise} \end{cases}$$
> > [EditHere - Graph of f(x) and F(x) for Question 3]

> [!sq]- Question 4
> The probability distribution of a discrete random variable X is given by;
> $$f(x)=\begin{cases}\frac{x^{2}}{55},&x=1,2,3,4,5\\ 0,&\text{otherwise}\end{cases}$$
> Find:
> i. $E(X)$,
> ii. $Var(X)$,
> iii. $\sigma$,
> iv. $E(2X+1)$,
> v. $Var(2X+1)$.
> 
> > [!continue]- Solution
> > **i. $E(X)$:**
> > $E(X) = \sum x \cdot f(x) = 1(\frac{1}{55}) + 2(\frac{4}{55}) + 3(\frac{9}{55}) + 4(\frac{16}{55}) + 5(\frac{25}{55})$
> > $= \frac{1 + 8 + 27 + 64 + 125}{55} = \frac{225}{55} = \frac{45}{11} \approx 4.091$.
> > 
> > **ii. $Var(X)$:**
> > $E(X^2) = \sum x^2 \cdot f(x) = 1^2(\frac{1}{55}) + 2^2(\frac{4}{55}) + 3^2(\frac{9}{55}) + 4^2(\frac{16}{55}) + 5^2(\frac{25}{55})$
> > $= \frac{1 + 16 + 81 + 256 + 625}{55} = \frac{979}{55} = \frac{89}{5} = 17.8$.
> > $Var(X) = E(X^2) - [E(X)]^2 = \frac{979}{55} - (\frac{45}{11})^2 = \frac{89}{5} - \frac{2025}{121} = \frac{10769 - 10125}{605} = \frac{644}{605} \approx 1.064$.
> > 
> > **iii. $\sigma$:**
> > $\sigma = \sqrt{Var(X)} = \sqrt{\frac{644}{605}} \approx 1.032$.
> > 
> > **iv. $E(2X+1)$:**
> > $E(2X+1) = 2E(X) + 1 = 2(\frac{45}{11}) + 1 = \frac{90}{11} + \frac{11}{11} = \frac{101}{11} \approx 9.182$.
> > 
> > **v. $Var(2X+1)$:**
> > $Var(2X+1) = 2^2 Var(X) = 4(\frac{644}{605}) = \frac{2576}{605} \approx 4.258$.

> [!sq]- Question 5
> The probability distribution of a discrete random variable X is given by the following table.
> 
> | X | 1 | 2 | 3 | 4 | 5 |
> | :--- | :--- | :--- | :--- | :--- | :--- |
> | $P(X=x)$ | 0.1 | k | 0.3 | 2k | 3k |
> 
> Find:
> i. The value of k,
> ii. $E(X)$,
> iii. $Var(X)$,
> iv. the standard deviation of X,
> v. the standard deviation of Y if $Y=2X+3$.
> 
> > [!continue]- Solution
> > **i. The value of k:**
> > $\sum P(X=x) = 1 \Rightarrow 0.1 + k + 0.3 + 2k + 3k = 1$
> > $6k + 0.4 = 1 \Rightarrow 6k = 0.6 \Rightarrow k = 0.1$.
> > The probabilities are: $P(1)=0.1, P(2)=0.1, P(3)=0.3, P(4)=0.2, P(5)=0.3$.
> > 
> > **ii. $E(X)$:**
> > $E(X) = 1(0.1) + 2(0.1) + 3(0.3) + 4(0.2) + 5(0.3) = 0.1 + 0.2 + 0.9 + 0.8 + 1.5 = 3.5$.
> > 
> > **iii. $Var(X)$:**
> > $E(X^2) = 1^2(0.1) + 2^2(0.1) + 3^2(0.3) + 4^2(0.2) + 5^2(0.3) = 0.1 + 0.4 + 2.7 + 3.2 + 7.5 = 13.9$.
> > $Var(X) = E(X^2) - [E(X)]^2 = 13.9 - (3.5)^2 = 13.9 - 12.25 = 1.65$.
> > 
> > **iv. Standard deviation of X:**
> > $\sigma_X = \sqrt{Var(X)} = \sqrt{1.65} \approx 1.285$.
> > 
> > **v. Standard deviation of Y if $Y=2X+3$:**
> > $Var(Y) = Var(2X+3) = 2^2 Var(X) = 4(1.65) = 6.6$.
> > $\sigma_Y = \sqrt{Var(Y)} = \sqrt{6.6} \approx 2.569$. (Alternatively, $\sigma_Y = |2|\sigma_X = 2 \times 1.285 = 2.57$).

> [!sq]- Question 6
> The continuous random variable X has the following probability density function, where k and h are constants.
> $$f(x)=\begin{cases}kx+1,&0\le x\le1\\ x+h,&1\le x\le2\\ 0,&\text{otherwise}\end{cases}$$
> a) $P(0\le X<1)=\frac{1}{2}$ show that $k=-1$ and $h=-1$.
> b) Find:
> i. $P(1<X<2)$,
> ii. $P(X>1.5)$,
> iii. $P(X>0.2)$,
> iv. $P(\frac{1}{4}\le X<\frac{5}{4})$,
> v. $P(X\le0.5)$,
> vi. the value of q if $P(X>q)=\frac{5}{8}$
> c) Sketch the graph of $f(x)$.
> 
> > [!continue]- Solution
> > **a) Show $k=-1$ and $h=-1$:**
> > $P(0\le X<1) = \int_0^1 (kx+1) dx = [\frac{kx^2}{2} + x]_0^1 = \frac{k}{2} + 1$.
> > Given $\frac{k}{2} + 1 = \frac{1}{2} \Rightarrow \frac{k}{2} = -\frac{1}{2} \Rightarrow k = -1$.
> > Total area must equal 1: $P(0\le X<1) + P(1\le X\le2) = 1 \Rightarrow \frac{1}{2} + \int_1^2 (x+h) dx = 1$.
> > $\int_1^2 (x+h) dx = \frac{1}{2} \Rightarrow [\frac{x^2}{2} + hx]_1^2 = \frac{1}{2}$.
> > $(2 + 2h) - (\frac{1}{2} + h) = \frac{1}{2} \Rightarrow \frac{3}{2} + h = \frac{1}{2} \Rightarrow h = -1$.
> > So, $f(x) = \begin{cases} -x+1, & 0\le x\le1 \\ x-1, & 1\le x\le2 \\ 0, & \text{otherwise} \end{cases}$
> > 
> > **b) Find Probabilities:**
> > i. $P(1<X<2) = \int_1^2 (x-1) dx = [\frac{x^2}{2} - x]_1^2 = (2-2) - (\frac{1}{2}-1) = \frac{1}{2}$.
> > ii. $P(X>1.5) = \int_{1.5}^2 (x-1) dx = [\frac{x^2}{2} - x]_{1.5}^2 = (2-2) - (\frac{2.25}{2} - 1.5) = 0 - (1.125 - 1.5) = 0.375 = \frac{3}{8}$.
> > iii. $P(X>0.2) = 1 - P(X\le0.2) = 1 - \int_0^{0.2} (-x+1) dx = 1 - [-\frac{x^2}{2} + x]_0^{0.2} = 1 - (-0.02 + 0.2) = 1 - 0.18 = 0.82$.
> > iv. $P(\frac{1}{4}\le X<\frac{5}{4}) = \int_{1/4}^1 (-x+1) dx + \int_1^{5/4} (x-1) dx$
> > $= [-\frac{x^2}{2} + x]_{1/4}^1 + [\frac{x^2}{2} - x]_1^{5/4} = ((-\frac{1}{2}+1) - (-\frac{1}{32}+\frac{1}{4})) + ((\frac{25}{32}-\frac{5}{4}) - (\frac{1}{2}-1))$
> > $= (\frac{1}{2} - \frac{7}{32}) + (-\frac{15}{32} + \frac{1}{2}) = \frac{9}{32} + \frac{1}{32} = \frac{10}{32} = \frac{5}{16}$.
> > v. $P(X\le0.5) = \int_0^{0.5} (-x+1) dx = [-\frac{x^2}{2} + x]_0^{0.5} = -0.125 + 0.5 = 0.375 = \frac{3}{8}$.
> > vi. Value of q if $P(X>q)=\frac{5}{8}$:
> > Since $P(X>1) = \frac{1}{2} = \frac{4}{8}$ and we need $\frac{5}{8}$, $q$ must be between 0 and 1.
> > $P(X>q) = 1 - P(X\le q) = 1 - \int_0^q (-x+1) dx = 1 - (-\frac{q^2}{2} + q) = \frac{q^2}{2} - q + 1$.
> > $\frac{q^2}{2} - q + 1 = \frac{5}{8} \Rightarrow \frac{q^2}{2} - q + \frac{3}{8} = 0 \Rightarrow 4q^2 - 8q + 3 = 0$.
> > $(2q - 1)(2q - 3) = 0 \Rightarrow q = 0.5 \text{ or } q = 1.5$. Since $q < 1$, $q = 0.5$.
> > 
> > **c) Sketch the graph of $f(x)$:**
> > [EditHere - Graph of f(x) for Question 6 (V-shaped)]

> [!sq]- Question 7
> The continuous random variable X has the following probability density function.
> $$f(x) = \begin{cases} \frac{x-2}{3}, & 2\le x<3 \\ \frac{1}{3}, & 3\le x<5 \\ \frac{6-x}{3}, & 5\le x<6 \\ 0, & \text{otherwise} \end{cases}$$
> *(Note: The original text had typos, corrected to represent a valid probability density function).*
> Find:
> i. the cumulative distribution function $F(x)$ and sketch the graph of $f(x)$ and $F(x)$,
> ii. $P(2<X\le4.5)$,
> iii. $P(X\ge4)$,
> iv. $P(X>10)$.
> 
> > [!continue]- Solution
> > **i. Cumulative distribution function $F(x)$:**
> > For $x < 2$, $F(x) = 0$.
> > For $2 \le x < 3$: $F(x) = \int_2^x \frac{t-2}{3} dt = [\frac{(t-2)^2}{6}]_2^x = \frac{(x-2)^2}{6}$.
> > For $3 \le x < 5$: $F(x) = F(3) + \int_3^x \frac{1}{3} dt = \frac{1}{6} + [\frac{t}{3}]_3^x = \frac{1}{6} + \frac{x-3}{3} = \frac{2x-5}{6}$.
> > For $5 \le x < 6$: $F(x) = F(5) + \int_5^x \frac{6-t}{3} dt = \frac{5}{6} + [2t - \frac{t^2}{6}]_5^x = \frac{5}{6} + (2x - \frac{x^2}{6}) - (10 - \frac{25}{6}) = -\frac{x^2}{6} + 2x - 5$.
> > For $x \ge 6$: $F(x) = 1$.
> > $$F(x) = \begin{cases} 0, & x < 2 \\ \frac{(x-2)^2}{6}, & 2 \le x < 3 \\ \frac{2x-5}{6}, & 3 \le x < 5 \\ -\frac{x^2}{6} + 2x - 5, & 5 \le x < 6 \\ 1, & x \ge 6 \end{cases}$$
> > [EditHere - Graph of f(x) and F(x) for Question 7]
> > 
> > **ii. $P(2<X\le4.5)$:**
> > $P(2<X\le4.5) = F(4.5) - F(2) = \frac{2(4.5)-5}{6} - 0 = \frac{4}{6} = \frac{2}{3}$.
> > 
> > **iii. $P(X\ge4)$:**
> > $P(X\ge4) = 1 - F(4) = 1 - \frac{2(4)-5}{6} = 1 - \frac{3}{6} = \frac{1}{2}$.
> > 
> > **iv. $P(X>10)$:**
> > $P(X>10) = 1 - F(10) = 1 - 1 = 0$.

> [!sq]- Question 8
> X is a continuous random variable with the following cumulative distribution function.
> $$F(x)=\begin{cases}0,&x<0\\ \frac{x^{3}}{125},&0\le x<5\\ 1,&x\ge5\end{cases}$$
> Find $f(x)$.
> 
> > [!continue]- Solution
> > $f(x) = \frac{d}{dx}[F(x)]$
> > For $x<0$, $f(x) = 0$.
> > For $0\le x<5$, $f(x) = \frac{d}{dx}(\frac{x^3}{125}) = \frac{3x^2}{125}$.
> > For $x\ge 5$, $f(x) = 0$.
> > $$f(x)=\begin{cases}\frac{3x^2}{125},&0\le x<5\\ 0,&\text{otherwise}\end{cases}$$

> [!sq]- Question 9
> The continuous random variable X has the following probability density function.
> $$f(x)=\begin{cases}\frac{x-1}{6},&1\le x<3\\ \frac{7-x}{12},&3\le x<7\\ 0,&\text{otherwise}\end{cases}$$
> *(Note: The original text had typos which caused an invalid area. The function has been corrected to form a valid PDF).*
> Find:
> i. $E(X)$,
> ii. $E(-X+4)$,
> iii. $Var(X)$,
> iv. $Var(Y)$ if $Y=5-X$
> 
> > [!continue]- Solution
> > **i. $E(X)$:**
> > $E(X) = \int_1^3 x(\frac{x-1}{6}) dx + \int_3^7 x(\frac{7-x}{12}) dx$
> > $= \frac{1}{6}[\frac{x^3}{3} - \frac{x^2}{2}]_1^3 + \frac{1}{12}[\frac{7x^2}{2} - \frac{x^3}{3}]_3^7$
> > $= \frac{1}{6}[(9 - \frac{9}{2}) - (\frac{1}{3} - \frac{1}{2})] + \frac{1}{12}[(\frac{343}{2} - \frac{343}{3}) - (\frac{63}{2} - 9)]$
> > $= \frac{1}{6}[\frac{28}{6}] + \frac{1}{12}[\frac{343}{6} - \frac{135}{6}] = \frac{28}{36} + \frac{208}{72} = \frac{56}{72} + \frac{208}{72} = \frac{264}{72} = \frac{11}{3} \approx 3.667$.
> > 
> > **ii. $E(-X+4)$:**
> > $E(-X+4) = -E(X) + 4 = -\frac{11}{3} + \frac{12}{3} = \frac{1}{3}$.
> > 
> > **iii. $Var(X)$:**
> > $E(X^2) = \int_1^3 x^2(\frac{x-1}{6}) dx + \int_3^7 x^2(\frac{7-x}{12}) dx$
> > $= \frac{1}{6}[\frac{x^4}{4} - \frac{x^3}{3}]_1^3 + \frac{1}{12}[\frac{7x^3}{3} - \frac{x^4}{4}]_3^7$
> > $= \frac{1}{6}[(\frac{81}{4} - 9) - (\frac{1}{4} - \frac{1}{3})] + \frac{1}{12}[(\frac{2401}{3} - \frac{2401}{4}) - (63 - \frac{81}{4})]$
> > $= \frac{1}{6}[\frac{136}{12}] + \frac{1}{12}[\frac{2401}{12} - \frac{513}{12}] = \frac{136}{72} + \frac{1888}{144} = \frac{272}{144} + \frac{1888}{144} = \frac{2160}{144} = 15$.
> > $Var(X) = E(X^2) - [E(X)]^2 = 15 - (\frac{11}{3})^2 = 15 - \frac{121}{9} = \frac{135}{9} - \frac{121}{9} = \frac{14}{9}$.
> > 
> > **iv. $Var(Y)$ if $Y=5-X$:**
> > $Var(Y) = Var(5-X) = (-1)^2 Var(X) = 1 \times \frac{14}{9} = \frac{14}{9}$.

> [!sq]- Question 10
> A continuous random variable X has the probability density function given by:
> $$f(x)=\begin{cases}\frac{1}{4},&0\le x<2\\ \frac{x}{2}-\frac{3}{4},&2\le x<3\\ 0,&\text{otherwise}\end{cases}$$
> Find:
> i. $E(X)$,
> ii. $Var(X)$,
> iii. the standard deviation, $\sigma$,
> iv. $E(3X+2)$
> v. $Var(3X+2)$
> vi. $E(3X+2)^{2}$
> 
> > [!continue]- Solution
> > **i. $E(X)$:**
> > $E(X) = \int_0^2 x(\frac{1}{4}) dx + \int_2^3 x(\frac{x}{2} - \frac{3}{4}) dx$
> > $= [\frac{x^2}{8}]_0^2 + [\frac{x^3}{6} - \frac{3x^2}{8}]_2^3$
> > $= \frac{4}{8} + (\frac{27}{6} - \frac{27}{8}) - (\frac{8}{6} - \frac{12}{8}) = \frac{1}{2} + (\frac{9}{2} - \frac{27}{8}) - (\frac{4}{3} - \frac{3}{2}) = \frac{1}{2} + \frac{9}{8} + \frac{1}{6} = \frac{12+27+4}{24} = \frac{43}{24} \approx 1.792$.
> > 
> > **ii. $Var(X)$:**
> > $E(X^2) = \int_0^2 x^2(\frac{1}{4}) dx + \int_2^3 x^2(\frac{x}{2} - \frac{3}{4}) dx$
> > $= [\frac{x^3}{12}]_0^2 + [\frac{x^4}{8} - \frac{x^3}{4}]_2^3$
> > $= \frac{8}{12} + (\frac{81}{8} - \frac{27}{4}) - (\frac{16}{8} - \frac{8}{4}) = \frac{2}{3} + \frac{27}{8} - 0 = \frac{16}{24} + \frac{81}{24} = \frac{97}{24}$.
> > $Var(X) = E(X^2) - [E(X)]^2 = \frac{97}{24} - (\frac{43}{24})^2 = \frac{2328}{576} - \frac{1849}{576} = \frac{479}{576} \approx 0.832$.
> > 
> > **iii. Standard deviation, $\sigma$:**
> > $\sigma = \sqrt{Var(X)} = \sqrt{\frac{479}{576}} \approx 0.912$.
> > 
> > **iv. $E(3X+2)$:**
> > $E(3X+2) = 3E(X) + 2 = 3(\frac{43}{24}) + 2 = \frac{43}{8} + \frac{16}{8} = \frac{59}{8} = 7.375$.
> > 
> > **v. $Var(3X+2)$:**
> > $Var(3X+2) = 3^2 Var(X) = 9(\frac{479}{576}) = \frac{479}{64} \approx 7.484$.
> > 
> > **vi. $E[(3X+2)^{2}]$:**
> > Using $Var(Z) = E(Z^2) - [E(Z)]^2$, where $Z = 3X+2$:
> > $E(Z^2) = Var(Z) + [E(Z)]^2 = \frac{479}{64} + (\frac{59}{8})^2 = \frac{479}{64} + \frac{3481}{64} = \frac{3960}{64} = \frac{495}{8} = 61.875$.

