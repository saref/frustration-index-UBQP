# frustration-index-UBQP
This algorithm is designed in Python 3.7 based on the UBQP model (Aref et al. 2018) for computing the exact value of frustration index (also called line index of balance).

Unconstrained binary quadratic programming (UBQP) model for computing the frustration index of a signed graph - Jupyter code written by Samin Aref in 2015

Creative common license: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

Using this code for non-commercial purposes is permitted to all given that the two following publications are cited:

Aref, S., Mason, A. J., and Wilson, M. C. A modelling and computational study of the frustration index in signed networks. arXiv:1611.09030 (2017). url: http://arxiv.org/pdf/1611.09030.

Aref, S., Mason, A. J., and Wilson, M. C. Computing the line index of balance using integer programming optimisation. In Optimization Problems in Graph Theory, B. Goldengorin, Ed. Springer, 2018, pp. 65-84. url: https://www.springer.com/gp/book/9783319948294. doi: 10.1007/978-3-319-94830-0_3

Suggested publications:

Aref, S., and Wilson, M. C. Measuring partial balance in signed networks. Journal of Complex Networks 6, 4 (2018), 566-595. doi: 10.1093/comnet/cnx044.

Aref, S., and Wilson, M. C. Balance and frustration in signed networks. Journal of Complex Networks (in press) (2019). doi: 10.1093/comnet/cny015.

Aref, S., and Neal, Z. Legislative effectiveness hangs in the balance: Studying balance and polarization through partitioning signed networks. arXiv:1906.01696 (2019). url: http://arxiv.org/pdf/1906.01696.
 
Related dataset:

Aref, S. Signed networks from sociology and political science, systems biology, international relations, finance, and computational chemistry. Figshare research data repository (2017). doi: 10.6084/m9.figshare.5700832.v2.

The following steps outline the process for installing the required software on your computer to be able to run the code:

1-Download and install Anaconda (Python 3.7 version) which allows you to run a Jupyter code. It can be downloaded from https://www.anaconda.com/distribution/. Note that you must select your operating system first and download the corresponding installer.

2-Register for an account on https://www.gurobi.com/registration-general-reg/ to get a free academic license for using Gurobi (world's most powerful mathematical solver!).
Note that Gurobi is a commercial software, but it can be registered with a free academic license if the user is affiliated with a recognized degree-granting academic institution. This involves creating an account on Gurobi website to be able to request a free academic license in step 5.

3-Download and install Gurobi Optimizer (versions 8.0 and above are recommended) which can be downloaded from https://www.gurobi.com/downloads/gurobi-optimizer-eula/ after reading and agreeing to Gurobi's End User License Agreement.

4-Install Gurobi into Anaconda. You do this by first adding the Gurobi channel to your Anaconda channels and then installing the Gurobi package from this channel.

From a terminal window issue the following command to add the Gurobi channel to your default search list

conda config --add channels http://conda.anaconda.org/gurobi

Now issue the following command to install the Gurobi package

conda install gurobi

5-Request an academic license from https://www.gurobi.com/downloads/end-user-license-agreement-academic/ and install the license on your computer following the instructions given on Gurobi license page.

Completing these steps is explained in the following links (for version 8.1): 

for windows
https://www.gurobi.com/documentation/8.1/quickstart_windows/installing_the_anaconda_py.html

for Linux
https://www.gurobi.com/documentation/8.1/quickstart_linux/installing_the_anaconda_py.html

for mac
https://www.gurobi.com/documentation/8.1/quickstart_mac/installing_the_anaconda_py.html

After following the instructions above, open Jupyter Notebook which takes you to an environment (a new tab on your browser pops up on your screen) where you can open the main code (which is a file with .ipynb extension).
