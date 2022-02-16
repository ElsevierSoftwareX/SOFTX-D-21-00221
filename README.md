# SOFTX-D-21-00221
onlineBcp: An R Package for Online Change Point Detection using a Bayesian Approach. To cite this Original Software Publication: https://www.sciencedirect.com/science/article/pii/S2352711022000140
Change point analysis has been useful for practical data analytics. In this paper, we
provide a new R package, onlineBcp , based on an online Bayesian change point
detection algorithm. This R package conveniently outputs the maximum posterior
probabilities of multiple change points, loci of change points, basic statistics for
segments separated by identified change points, confidence interval for unknown
segment mean and a plot displaying the segmented data. Practically, missing value
pre-treatment of the data, before the change point detection algorithm is implemented,
is built in this package. In addition, the Kolmogorov-Smirnov test for checking the
normality assumption on each segment, post-change point detection, is included as an
option in the package for the ease of data analytic and assumption checking flow.
When additional data come in, the package provides a function to combine changes
identified based on prior data and changes identified based on additional data and thus
provides a fast detection of change points in the data stream when new batches of
data are collected
