# mast90105-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [MAST90105 Lab 4 Solved](https://www.ankitcodinghub.com/product/mast90105-lab-and-workshop-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112931&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAST90105 Lab 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this lab, we will examine the shape of distributions for different values of their parameters.

1. Download and open the file lab4.R in R or RStudio

a. The function m34binomial(n,p) returns a skewness (first column) and kurtosis (second column) of a binomial distribution with parameters n and p (these can be vectors of the same length). Here, n is the number of trials and p is the probability of success in each trial. Use this function to compute the skewness and kurtosis and record these values in the following table for the binomial distribution:

p=0.1 p=0.3 p=0.5 p=0.7 p=0.9

n=1

n=10

n=50

n=100

n=250

n=500

b. Comment on the trends you find in your table, in particular across the rows and down the columns

c. The function m34negbinomial(r,p) returns a skewness (first column) and kurtosis (second column) of a negative binomial distribution with parameters r and p (these can be vectors of the same length). Here, experiment continues until r successes and p is the probability of success in each trial. Use this function to compute the skewness and kurtosis and record these values in the following table for the negative binomial distribution:

p=0.1 p=0.3 p=0.5 p=0.7 p=0.9

r=1

r=10

r=50

r=100

r=250

r=500

d. Comment on the trends you find in the table, in particular across the rows and down the columns

2. The function distBinomHyper(n,p,t) computes the distance between the binomial distribution Binom(n,p) and the hypergeometric distribution Hyper(b,t − b,n) with b = p · t. This function also plots these two pmf-s for all values from the interval

. Here, n is the sample size, p is the probability of success and

the proportion of items of type 1 for the binomial and hypergeometric distributions, respectively, and b, t − b are the numbers of items of type 1 and 2, respectively, in the population of size t. The distance between the two distributions is defined as

D = max|Pr(X ∈ A) − Pr(Y ∈ A)| = 0.5X|Pr(X = i) − Pr(Y = i)|. (1)

A i

a. Take the sample size n to be 500, 1000 and 3000. Record the three distances between the binomial and hypergeometric distributions for each of the combinations in the table:

p=0.1 p=0.3 p=0.5 p=0.7 p=0.9

t=n+100

t=n+500

t=n+1,500

t=n+2,000

t=n+10,000

t=16,000,000

b. Comment on the trends in the table, in particular across the rows and columns

c. Looking at the R code, what is the purpose of defining the variable i.plot?

d. (Challenging!) Prove the equality (1) for any discrete random variables X and Y . (Hint: use the fact that probabilities add to one, and think about the set of numbers for which the hypergeomtric probability is greater than the binomial probability and vice-versa.)

3. The objective of this question is to use R to look at the actual distance between binomial and Poisson distributions.

a. We learned that the maximum difference between any binomial and the corresponding Poisson probability, denoted D in the plots, was bounded by p, the probability of success in the binomial distribution (check module 2, Section 7.1).

Modify the function distBinomHyper(n,p,t) to compute the distance between the Binomial distribution Binom(n,p) and the Poisson distribution Poisson(λ), with λ = np, and to plot their pmf-s. Choosing a variety of values for p between 0 and 1, compute and record the values of D, for different values of n. Comment, particularly on whether the relationship with n is monotone.

b. Find the maximum difference p − D and write it down. What do the plots in (b) show about the guidance that is given in many textbooks that “the Poisson approximation to Binomial can be used when n is large, p is small and np is moderate”?

c. Try to find n and p that minimize the ratio between p/D. Report on your findings.

2 Workshop

1. A warranty is written on a product worth $10,000 so that the buyer is given $8000 if it fails in the first year, $6000 if it fails in the second, $4000 if it fails in the third, $2000 if it fails in the fourth, and zero after that. Its probability of failing in a year is 0.1; failures are independent of those of other years. What is the expected value of the warranty?

2. Define the pmf and give the values of µ and σ2 when the moment-generating function (mgf) of X is defined by

a.

a. What probability distribution does X have? Namely, what is the pmf of X?

b. Give the mean and variance of X.

c. Find P(X &gt; 400) and P(X &lt; 300).

4. Let X equal the number of flips of a fair coin that are required to observe the same face on consecutive flips. Find the pmf of X.

5. Suppose that a basketball player can make a free throw 60% of the time. Let X equal the minimum number of free throws that this player must attempt to make a total of

10 shots,

a. What probability distribution does X have? Namely, what is the pmf of X?

b. Give the mean and variance of X.

c. Find P(X = 16).

6. Let X have a Poisson distribution with a variance of 3. Find P(X = 2).

7. Flaws in a certain type of drapery material appear on the average of one in 150 square feet. If we assume the Poisson distribution, find the probability of at most one flaw in 225 square feet.

8. Suppose that the probability of suffering a side effect from a certain flu vaccine is 0.005. Also suppose 1000 persons are inoculated.

a. Find the exact probability that at most 1 person suffers using a binomial distribution.

b. Find approximately the probability that at most 1 person suffers using a Poisson distribution.

9. A hospital obtains 40% of its flu vaccine from Company A, 50% from Company B, and 10% from Company C. From past experience it is known that 3% of the vials from A are ineffective, 2% from B are ineffective, and 5% from C are ineffective. The hospital test 5 vials from each shipment. If at least one of the five is ineffective, find the conditional probability of that shipment coming from C.

10. If X has a Poisson distribution so that 3P(X = 1) = P(X = 2), find P(X = 4).

11. One of four different prizes was randomly put into each box of a cereal. If a family decided to buy this cereal until it obtained at least one of each of the four different prizes, what is the expected number of boxes of cereal that must be purchased?
