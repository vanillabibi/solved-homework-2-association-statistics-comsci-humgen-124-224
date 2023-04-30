Download Link: https://assignmentchef.com/product/solved-homework-2-association-statistics-comsci-humgen-124-224
<br>
<h1>Problem 1 – Association Study at a Single SNP</h1>

<h2>Part A – Calculating the Non-Centrality Parameter</h2>

Use the formulas described in Lectures 2 &amp; 3 to compute the non-centrality parameters. Compute the noncentrality parameters for minor allele frequencies 0.05, 0.2 and 0.4, for relative risks of 1.5, 2.0 and 3.0, for total individual numbers in the cases and controls of 500 and 1000. Assume that disease prevalence (<em>F</em>) is very low. You must compute the non-centrality parameter using R and show a transcript of your code and results.

You can enter the results into these tables and include them in the homework submission,

<h2>Part B – Calculating the Power</h2>

Now compute the power of these studies assuming a p-value threshold of 0.05. You must compute the power using R and show a transcript of your code and results. You should re-use the R code you wrote for computing non-centrality parameter in Part A.

You can enter the results into these tables and include them in the homework submission,

<h2>Part C – Calculating the number of individuals</h2>

Using the same relative risks and minor allele frequencies as in Part A and B, compute the number of individuals needed to achieve 80% power for each pair of relative risk and minor allele frequency. You should use the R code you wrote for Part B, and try different values of the number of individuals to achieve 80% power roughly (79% ∼ 81%).

You can enter the results into these tables and include them in the homework submission,

<h1>Problem 2 – Unbalanced Cases and Controls</h1>

<h2>Part A</h2>

Assume that you have a <em>N </em>total individuals in a balanced case and control study (i.e.√ <em>N/</em>2 case individuals

and <em>N/</em>2 control individuals). The non-centrality parameter for this study is <em>λ<sub>A </sub>N</em>.

On the other hand, if the number of cases and controls are not equal, the non-centrality paramter is different. If there are <em>N</em><sup>+</sup><em>/</em>2 cases and <em>N</em><sup>−</sup><em>/</em>2 controls, the non centrality parameter is.

Now assume you are designing a study with three times the number of cases as controls. How large does your study have to be (as a factor of <em>N</em>) so that you achieve the same power as a balanced study with <em>N </em>individuals?

<h2>Part B</h2>

Assume that you have <em>N</em><sup>+</sup><em>/</em>2 cases and an unlimited number of controls. What is the size of a balanced study (i.e. equal numbers of cases and controls) that would have equivalent power? Show your derivation. (Hint: First solve for the noncentrality parameter if you have a very large number of controls. Try using

1,000,000.)

<h2>Part C (Grad Students Only)</h2>

Derive the non-centrality parameter for unbalanced cases and controls above. Describe the precise approximation assumption you need to make.