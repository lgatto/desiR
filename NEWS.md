# desiR 1.1

* updated des.line() function so that arguments passed to the desirability function must be given in the des.args=c() argument. The ellipses (...) is now used to pass arguments to the plot function (e.g. xlim, lwd, lty, col). Note that scripts from previous versions will fail and will need to be updated from:

des.line(x1, "d.high", cut1=10 cut2=11)

to

des.line(x1, "d.high", des.args=c(cut1=10, cut2=11))


* Provided GitHub url and location for bug reports.


# desiR 1.0

* First version
