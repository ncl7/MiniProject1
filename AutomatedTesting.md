# AUTOMATED TESTING

**Automated testing** increases efficiency since there is regular feedback from the 
system after a problem is found and tested. The development process becomes more 
streamlined since bugs are found early and fixed before the user has time to notice or complain. Automated testing is a part of the DevOps process flow and keeps a company on good terms with its customers, keeping a company competitive. It is part of [continuous integration](https://github.com/Shannon-NJIT/MiniProject1/blob/master/CI.md) since the updated code from the developers is tested automatically. This allows developers to see if their software breaks sooner rather than later, giving them more time to fix it. As long as the company’s automated testing environment is reliable, then the company can continue being productive and competitive. 

Martin Fowler mentions a test pyramid on his website that helps visualize the 
tests required and the different layers. The pyramid was created by Mike Cohn and is a 
concept that can be used for automated testing. (See Figure 1 below.)
Basically, for faster testing results it is better to write a bunch of small tests for 
units, some service tests, and very few high-level tests since these are slower and 
require more integration. Otherwise, it would be difficult to maintain the fast 
turnaround of automated testing.


![](https://martinfowler.com/articles/practical-test-pyramid/testPyramid.png)
**Figure 1. Practical Test Pyramid**
