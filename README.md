## Statistical Inference Course Project

### Part 1

Assignment Description

Investigate the exponential distribution in R and compare it with the Central Limit Theorem.The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of exponential distribution is 1/lambda and the standard deviation is also 1/lambda. Set lambda = 0.2 for all of the simulations. You will investigate the distribution of averages of 40 exponentials. Note that you will need to do a thousand simulations.

Illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponentials. You should:

    Show the sample mean and compare it to the theoretical mean of the distribution.
    Show how variable the sample is (via variance) and compare it to the theoretical variance of the distribution.
    Show that the distribution is approximately normal.

### Part 2

Analyze the ToothGrowth data in the R datasets package.

This study assesses the effect of Vitamin C on tooth growth of Guinea pigs. It contains measurement of the length of odontoblasts (teeth) in each of 10 guinea pigs at each of three dose levels of Vitamin C (0.5, 1, and 2 mg) with each of two delivery methods (orange juice or ascorbic acid).

A data frame with 60 observations on 3 variables.

[,1] len numeric Tooth length
[,2] supp factor Supplement type (VC or OJ).
[,3] dose numeric Dose in milligrams.

Source

C. I. Bliss (1952) The Statistics of Bioassay. Academic Press.

References
McNeil, D. R. (1977) Interactive Data Analysis. New York: Wiley.
