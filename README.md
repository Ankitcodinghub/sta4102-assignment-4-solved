# sta4102-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [STA4102 Assignment 4 Solved](https://www.ankitcodinghub.com/product/sta410-instructions-solutions-to-problems-1-and-2-are-to-be-submitted-on-quercus-pdf-files-only-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117150&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STA4102  Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
– Instructions: Solutions to problems 1 and 2 are to be submitted on Quercus (PDF files only).

1. Consider the model

Yi = θi + εi (i = 1,···,n)

where {εi} is a sequence of random variables with mean 0 and finite variance representing noise. We will assume that θ1,···,θn are dependent or “smooth” in the sense that the absolute differences {|θi−θi−1|} are small for most values of i. Rather than penalizing a lack of smoothness by Pi(θi − 2θi−1 + θi−2)2 (as in Assignment #2), we will consider estimating {θi} given data {yi} by minimizing

(1)

n

where λ &gt; 0 is a tuning parameter and X|θi − θi−1| represents the total variation of {θi}.

i=2

The resulting estimates θb1,···,θbn, are sometimes called fusion estimates and are useful if {θi} contain “jumps”, that is, θi = g(i/n) where g is a smooth function with a small number of discontinuities (i.e. jumps).

The non-differentiable part of the objective function in (1) can be made separable by defining φi = θi − θi−1 for i = 2,···,n and then minimizing

(2)

where now each θi (for i = 2,···,n) will be a function of θ1,φ2,···,φi. The representation of the objective function in (2) can be used to compute the parameter estimates using coordinate descent although there is must faster algorithm. However, (2) is useful for deriving properties of the estimates.

(a) Show that

(b) Show that if minimize (1) (or (2)) then

n

X

(yi − θbi) = 0.

i=1

(Hint: Use the representation (2) and compute its partial derivative with respect to θ1.)

(c) Show that for all i. (Hint: Show that

for any θ1,···,θn.)

(d) For λ sufficiently large, we will have or equivalently

How large must λ be in order to have ? (Hint: Look at the sub-gradient of (2) with respect to (θ1,φ2,···,φn); when is (0,0,···,0) an element of this sub-gradient at (¯y,0,···,0)?)

2. Suppose that X1,···,Xn are sampled from the following truncated Poisson distribution:

for x = r + 1,r + 2,···

for some integer r ≥ 0 where

.

Such a sample might arise if we were sampling from a Poisson population but were unable to observe data less than or equal to r.

The EM algorithm can be employed to estimate λ from the observed X1,···,Xn. The key is to think of the observed data as a subset of some larger (“complete”) data set

X1,···,Xn,Xn+1,···,Xn+M where M ≥ 0 is a random variable and Xn+1,···,Xn+M ≤ r; given M = m, this complete data set is now assumed to be m+n independent observations from a Poisson distribution with mean λ. The log-likelihood for the complete data is

n+m

lnL(λ) = ln(λ) X xi − (n + m)λ,

i=1

which depends on two unknowns and m. To use the EM algorithm, we need to

estimate these two unknowns.

(a) The probability distribution of M is

for m = 0,1,2,···

Show that Eλ(M) = n(1 − κλ(r))/κλ(r).

(b) Show that

.

(Hint: Note that (a) Xn+1,···,Xn+M are independent of X1,···,Xn and (b) Xn+1,···,Xn+M ≤ r.)

(c) Consider the data given in the table below. They represent the accident claims submittedto La Royale Belge Insurance Company during a single year. A crude model for the number of claims submitted for a given policy is Poisson. However, the data below does not provide the number of policies for which no claims were submitted. We want to estimate λ as well as to impute (estimate) the number M of policies with no claims.

Number of claims 1 2 3 4 5 6 7

Number of policies 1317 239 42 14 4 4 1

Assume a truncated Poisson model for these data taking r = 0 and estimate λ as well as M using the EM algorithm (which in this case has a particularly simple form). Do you think the truncated Poisson model is useful for these data? (For example, do you think your estimate of M is reasonable?)
