# Canonical Correlation Analysis: an overview

Originally defined by Hotelling in 1936 (Hotelling, 1936),
canonical correlation analysis (CCA)
is a statistical method whose goal is to extract the
information common to two data tables that measure quantitative
variables on a same set of observations.
To do so, CCA computes two sets of linear combinations --called latent variables--
(one for each data table) that have maximum correlation.
To visualize this common information 
extracted by the analysis, 
a convenient way
is 
1. to plot the latent variables of one set against the other set
(this creates plots akin to plots of factor scores in principal component analysis);
2. to plot the coefficients of the linear combinations 
(this creates plots akin to  plotting the loadings in principal component analysis); and
3. to plot the correlations between the original variables and the latent variables (this creates "correlation circle" plots like in principal component analysis).

CCA generalizes many standard statistical techniques 
(e.g., multiple regression, analysis of variance, discriminant analysis)
and can also be declined in several related methods
that address
slightly different types of problems 
(e.g., different normalization conditions, different types data).

If the two data matrices are called \\( X \\) and \(Y\), CCA looks for loading \(p\) and \(q\) such that they solve the following maximization problem:

\[
\max cor(p^\top X^\top Y q)
\]

Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]


