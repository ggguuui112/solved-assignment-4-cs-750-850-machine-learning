Download Link: https://assignmentchef.com/product/solved-assignment-4-cs-750-850-machine-learning
<br>
<span style="font-size: 2.61792em; letter-spacing: -1px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Problem 1 [25%]</span>

In this exercise, we will predict the number of applications received using the other variables in the College (ISLR::College) data set.

<ol>

 <li>Fit a linear model using least squares on the training set, and report the <strong>test </strong>error obtained.</li>

 <li>Use best subset selection with cross-validation. Report the test error obtained.</li>

 <li>Fit a ridge regression model on the training set, with <em>λ </em>chosen by cross-validation.</li>

 <li>Fit a lasso model on the training set, with <em>λ </em>chosen by cross-validation. Report the test error obtained, along with the number of non-zero coefficient estimates.</li>

 <li>Briefly comment on the results obtained. How accurately can we predict the number of college applications received? Is there much difference among the test errors resulting from these approaches?</li>

</ol>

<h1>Problem 2 [25%]</h1>

We will try to predict per capita crime rate in the Boston dataset.

<ol>

 <li>Try out best subset selection, the lasso, ridge regression, and PCR on this problem. Present and discuss results for the approaches that you consider.</li>

 <li>Propose a model (or set of models) that seem to perform well on this data set, and justify your answer. Make sure that you are evaluating model performance using validation set error, cross-validation, or some other reasonable alternative, as opposed to using training error.</li>

</ol>

<h1>Problem 3 [25%]</h1>

Suppose we have a linear regression problem with <em>P </em>features. We estimate the coefficients in the linear regression model by minimizing the RSS for the first <em>p </em>features:

<em>n </em>                           <em>p                </em>2

<h2>                                                            X                                X</h2>

<em>y</em><em>i − β</em>0 <em>−                β</em><em>jx</em><em>ij</em>

<em>i</em>=1                              <em>j</em>=1

where <em>p ≤ P</em>. For parts (1) through (5), indicate which of i. through v. is correct. Briefly <strong>justify </strong>your answer.

<ol>

 <li>As we increase <em>p </em>from 1 to <em>P</em>, the training RSS will <em>typically</em>:</li>

 <li>Remain constant. ii. Steadily increase. iii. Steadily decrease. iv. Increase initially, and then eventually start decreasing in an inverted U shape.</li>

 <li>Decrease initially, and then eventually start increasing in a U shape.</li>

</ol>

1

<ol start="2">

 <li>Repeat (1) for test MSE.</li>

 <li>Repeat (1) for squared bias.</li>

 <li>Repeat (1) for variance.</li>

 <li>Repeat (1) for the irreducible error (Bayes error).</li>

</ol>

<h1>Problem 4 [25%]</h1>

Suppose we estimate the regression coefficients in a linear regression model by minimizing

<em>n </em>                           <em>p                </em>2                               <em>p</em>

<h2>                                           X                               X                                                  X</h2>

<sub> <em>i </em></sub><em>− β</em><sub>0 </sub><em>−    β<sub>j</sub>x<sub>ij</sub></em><sub> </sub>subject to     <em>|β<sub>j</sub>| ≤ s y</em>

<em>i</em>=1                              <em>j</em>=1                                                 <em>j</em>=1

for a particular value of <em>s</em>. For parts (1) through (5), indicate which of i. through v. is correct. <strong>Justify </strong>your answer.

<ol>

 <li>As we increase <em>s </em>from 0, the training RSS will <em>typically</em>:</li>

 <li>Remain constant. ii. Steadily increase. iii. Steadily decrease. iv. Increase initially, and then eventually start decreasing in an inverted U shape.</li>

 <li>Decrease initially, and then eventually start increasing in a U shape.</li>

 <li>Repeat (1) for test RSS.</li>

 <li>Repeat (1) for (squared) bias.</li>

 <li>Repeat (1) for variance.</li>

 <li>Repeat (1) for the irreducible error (Bayes error).</li>

</ol>

<h1>Problem O4 [30%]</h1>

This problem can be substituted for Problem 4 above, for up to 5 points extra credit. The better score from problems 4 and O4 will be considered.

Solve Exercise <em>3.6 </em>in [Bishop, C. M. (2006). Pattern Recognition and Machine Learning].


