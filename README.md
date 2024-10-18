java cMATH36031 Problem solving by computer.
Project 1 - deadline 25th October 2024, time 1100hrs. Submission of the
project is via Blackboard.
Recurring decimals Consider the rational number x = p/q where p, q are positive
integers, p < q and the integer q ends with the digit 9. It is known that the decimal
expansion of x takes the form of a recurring decimal with
x = 0.a1a2 . . . a↵ . . .
where the ai are non-negative integers and ↵ is the smallest integer such that the sequence
a1a2 . . . a↵ repeats. We deﬁne ↵ to be the period of the recurring fraction. The bar over
the digits denotes the recurring sequence.
For example with p = 1, q = 19
x = 1
19 = 0.052631578947368421
and
a1 = 0, a2 = 5, . . . a18 = 1, with ↵ = 18.
Task 1: Write a function RecFrac1 such that [k,a] = RecFrac1(p,q) returns the
period k of the recurring fraction p/q and the variable a which contains the recurring digits
a1, a2, . . . , ak, in the decimal expansion of p/q. Here the integers p, q are positive and the last
digit of q is 9. In performing this task you need to use Algorithm 1 (mentioned below).
The ﬁrst few lines of your code should look like:
function [k , a ] = RecFrac1 ( p,q )
%% RecFrac1 uses Algorithm 1 and returns the recurring digits in the
% decimal expansion of p /q , among all pairs of
% positive integers (p , q ) such that p< q and the last digit of q is a 9.
Task 2: Write a function RecFrac2 such that [k,a] = RecFrac2(p,q) returns the
period k of the recurring fraction p/q and the variable a which contains the recurring digits
a1, a2, . . . , ak, in the decimal expansion of p/q. Here the integers p, q are positive and the last
digit of q is 9. In performing this task you need to use Algorithm 2 (mentioned below).
The ﬁrst few lines of your code should look like:
function [k , a ] = RecFrac2 ( p,q )
%% RecFrac2 uses Algorithm 2 and returns the recurring digits in the
% decimal expansion of p /q , among all pairs of
% positive integers (p , q ) such that p< q and the last digit of q is a 9.
Task 3: Using the RecFrac functions deﬁned in Task 1 or Task 2 ﬁnd positive integers
r, s with r < s <= 649, and with the last digit of s ending in a 9, such that that period of the
recurring fraction r/s is largest. Display all the recurring digits. If there is more than one
pair with the largest recurring digits, show the pair with the largest s value. If additionally
1
 
Etnssettfnnftftttnttnttttssostssetottatttgsnngtstannesssentatgngaasattangttftngtnsztsgtnaettssesototttotseoseattthere are multiple (r, s) values with the largest period and largest s, choose the pair with the
largest r to display your answer and as part of the required output list all the (r, s) values
in your report suitably formatted.
Notes: (a) you can assume that p, q are positive integers. You will need to build in a
check of the validity of the input, ie that the number q ends in a 9 and that p < q.
(b) In computing the recurring digits you need to use both Algorithms 1 and 2 and
you will need to give details of how the algorithms compute the recurring digits
in your report. Detailed proofs are not expected.
Note that a naive application of simple division will not work as the period of the recurring
digits will in most cases be larger than the typical values computed via simple application
of division in MATLAB.
(c) One algorithm is described in the video clip labelled Algorithm 1 in the Projects
folder in Blackboard for this module. Another algorithm using the ancient Vedic system of
mathematics developed in India is explained in the video clip labelled Algorithm 2 in the
Projects folder in Blackboard. Please study both algorithms and try them yourself on several
example代 写MATH36031、MATLAB
代做程序编程语言s by hand to see how they work. You will then need to formulate the algorithms to
use for the project. You will of course have to explain the details in your report.
Additional Information
All coding must be done in MATLAB and you are required to submit your MATLAB
functions and m (or mlx)-ﬁles via the Blackboard submission box. Project reports
in pdf form only should be submitted via the Turnitin submission box. Remember
the Turnitin software will automatically scan reports for plagiarism.
Please ask if you need help on any commands, or whether there are built-in commands/functions
 to accomplish certain tasks (especially important if you think you have a
good approach to the questions, but do not know the related commands).
The default datatype is double (decimal number), and be aware of possible side e↵ects
when using the numbers as integers. Remember that the same question can be solved
by di↵erent approaches, and the same approach can be implemented in di↵erent ways.
All relevant commands should be covered during the lectures or tutorial exercises,
but you are free to explore your own. Make critical judgement to choose the best
approach/implementation.
Aim for emust be reproducible from your codes. Remember
that markers will be able to run the codes in case of any doubts and any inconsistencies
between reported results and actual results from running codes will lead to reports
being marked down. You will be marked down if no codes are submitted.
Guidelines for the report.
1. Have a look at the generic rubric and frequently asked questions, which is given on
Blackboard in the Projects folder and about how your report will be marked. The
rubric also describes the intended learning outcomes about what you are expected to
achieve at the end.
2. Avoid copying (too many) sentences directly from the project description, and try to
restate the problem with your own words or examples if possible.
3. You may use your report in the future as evidences of written work, so take it seriously.
4. Your target audience is a fellow student on your course: explain the questions so that
the report can be understood without this project description and your approach can
be implemented in another computer. The report should indicate to the reader how
well you understand the problem and the approach you have taken, the validation and
other checks that you made to ensure your results are credible. Reports submitted
containing codes only and with no explanations of how the problem was solved, will
result in a failing mark, even though the codes may work perfectly well and give the
correct answers.
5. Balance the explanation of the approach and the comments in the code. Avoid undercommenting
 and over-commenting.
6. Aim for precision and clarity of writing (discussed in Week 5).
7. Keep your page length not exceeding eight A4 pages, with a font size no smaller
than 11, and page margins no smaller than 2cm. There is no need for a title page for
a relative short report like this. If more than 8 pages are submitted only the
ﬁrst 8 pages will be marked and the rest of the submission will be ignored.
8. Since there is no ﬁnal exam, you are advised to spend at least 15 hours on each project.
9. The submission box (via Blackboard and Turnitin) for each project will be open
two weeks before the deadline, and you are encouraged to submit an early draft to
see how Turnitin works on Blackboard. Only your last submission will be marked.
Anything submitted after the deadline (except for those with approved extensions)
will be subject to late penalties. Any late penalty will be applied by the Teaching and
Learning Support O

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
