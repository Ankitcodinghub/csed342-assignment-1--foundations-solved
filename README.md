# csed342-assignment-1--foundations-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/csed342-assignment-1-foundations-solved-2/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128352&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED342  Assignment 1- Foundations Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
CSED342 – Artificial Intelligence

General Instructions

Assignment 1 has three problems – problem 0, 1, 2. You only need to submit problem 1 and 2. Problem 0 is not graded, but must be solved by yourself before participating in this course.

This assignment has been developed in Python 3.9, so please use Python 3.9 to implement your code. we recommend using Conda environment.

You should modify the code in submission.py between

# BEGIN_YOUR_ANSWER and

# END_YOUR_ANSWERYou can add other helper functions outside the answer block if you want, but do not import other libraries and do not make changes to files other than submission.py.

Your code will be evaluated on two types of test cases, basic and hidden, which you can see in grader.py. Basic tests, which are fully provided to you, do not stress your code with large inputs or tricky corner cases. Hidden tests are more complex and do stress your code. The inputs of hidden tests are provided in grader.py, but the correct outputs are not. To run all the tests, type

python grader.py

This will tell you only whether you passed the basic tests. On the hidden tests, the script will alert you if your code takes too long or crashes, but does not say whether you got the correct output. You can also run a single test (e.g., 2a-0-basic) by typing

python grader.py 2a-0-basic

We strongly encourage you to read and understand the test cases, create your own test cases, and not just blindly run grader.py.

Problems

Problem 0. Optimization and probability

In this class, we will cast AI problems as optimization problems, that is, finding the best solution in a rigorous mathematical sense. At the same time, we must be adroit at coping with uncertainty in the world, and for that, we appeal to tools from probability. The three problems below will not be scored, but please solve them because they are basic concepts.

Problem 0a [0 points]

Suppose you repeatedly roll a fair six-sided dice until you roll a 1 or a 2 (and then you stop). Every time you roll a 3, you lose 1 points, and every time you roll a 4, you win 2 points. You do not win or lose any points if you roll a 5 or a 6. What is the expected number of points you will have when you stop?

Problem 0b [0 points]

Suppose the probability of a coin turning up heads is 0 &lt; p &lt; 1, and that we flip it 5 times and get {H,T,H,T,T}. We know the probability (likelihood) of obtaining this sequence is L(p) = p(1 − p)p(1 − p)(1 − p) = p2(1 − p)3. Now let’s go backwards and ask the question: what is the value of p that maximizes L(p)?

Hint: Consider taking the derivative of logL(p). Taking the derivative of L(p) works too, but it is cleaner and more natural to differentiate logL(p). You can verify for yourself that the value of p which minimizes logL(p) must also minimize L(p).

Problem 0c [0 points]

Let’s practice taking gradients, which is a key operation for being able to optimize continuous functions. For w ∈Rd and constants ai,bj ∈Rd and λ ∈R, define the scalar-valued function

m n

f(w) = XX(a⊤i w − b⊤j w)2 + λ∥w∥22,

i=1 j=1

where w, ai and bj are column vectors (e.g. w = (w1,…,wd)⊤) and is known as the L2 norm. Compute the gradient ∇wf(w).

Recall: the gradient is a d-dimensional vector of the partial derivatives with respect to each wi:

.

If you’re not comfortable with vector calculus, first warm up by working out this problem using scalars in place of vectors and derivatives in place of gradients. Not everything for scalars goes through for vectors, but the two should at least be consistent with each other (when d = 1). Do not write out summation over dimensions, because that gets tedious.

Problem 1. Programming 1

In this problem, you will implement a bunch of short functions related vector representations. The main purpose of this exercise is to familiarize yourself with Python, and to understand vector representations in programming.

If you’re new to Python, the following provide pointers to various tutorials and examples for the language: • Python for Programmers:

https://wiki.python.org/moin/BeginnersGuide/Programmers • Example programs of increasing complexity:

https://wiki.python.org/moin/SimplePrograms

Problem 1a [2 points]

Implement denseVectorDotProduct in submission.py.

Problem 1b [2 points]

Implement incrementDenseVector in submission.py.

Problem 1c [2 points]

Implement dense2sparseVector in submission.py.

Problem 1d [2 points]

Implement sparseVectorDotProduct in submission.py.

Problem 1e [2 points]

Implement incrementSparseVector in submission.py.

Problem 2. Programming 2

In this problem, you will implement short functions more, and the main purpose of this exercise is also to familiarize yourself with Python.

Problem 2a [2 points]

Implement minkowskiDistance in submission.py.

Problem 2b [2 points]

Implement getLongestWord in submission.py.

Problem 2c [2 points]

Implement getFrequentWords in submission.py.
