
# Welcome to the BYU Biophysics Group !
The BYU Biophysics research group studies fundamental processes of life. We model these processes on the computer and compare with cryo-EM images. Prokaryotic cells are our current focus because of the large database of tomograms that are available. 

We use the julia programmming language, which provides a solution to the "two-language problem". By understanding basic life processes, our ultimate goal is to contribute to the general knowledge of human function and thus impact medical and preventitive treatment to improve human health.

 Below you will find all the information you need to get started! 

# Getting Started with Biology
Here are some interesting papers and useful textbooks which will provide foundation to the sorts of questions and problebms we are working on.
* [Escherichia coli Peptidoglycan Structure and Mechanics as Predicted by Atomic-Scale Simulations](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003475)
* [Coarse-Grained Molecular Dynamics Simulations of the Bacterial Cell Wall](https://www.researchgate.net/publication/304020343_Coarse-Grained_Molecular_Dynamics_Simulations_of_the_Bacterial_Cell_Wall)
* [Coarse-grained simulations of bacterial cell wall growth reveal that local coordination alone can be sufficient to maintain rod shape](https://www.pnas.org/content/112/28/E3689.long)
* [Simulations of Proposed Mechanisms of FtsZ-Driven Cell Constriction](https://journals.asm.org/doi/10.1128/JB.00576-20)
* [Random walks in Biology by Howard c. Berg](https://press.princeton.edu/books/paperback/9780691000640/random-walks-in-biology)
* [Microcosm: E.Coli and the new science of life by Carl Zimmer](https://www.amazon.com/Microcosm-Coli-Science-Life/dp/0307276864/ref=asc_df_0307276864/?tag=hyprod-20&linkCode=df0&hvadid=266033622375&hvpos=&hvnetw=g&hvrand=7949759552210628870&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9029858&hvtargid=pla-529339927612&psc=1)
* [Physical Biology of the Cell by Rob Phillips](https://www.amazon.com/Physical-Biology-Cell-Rob-Phillips/dp/0815344503/ref=sr_1_1?gclid=CjwKCAjwloCSBhAeEiwA3hVo_Z_QGpY5HKXNcUuloiPCHinDh-dNL-LtrzsACZaicseqIxA1a1vuKhoC6QEQAvD_BwE&hvadid=241627101117&hvdev=c&hvlocphy=9029858&hvnetw=g&hvqmt=e&hvrand=626376698173270681&hvtargid=kwd-10715236319&hydadcr=3208_10392132&keywords=physical+biology+of+the+cell&qid=1648415021&s=books&sr=1-1)  
* [Physical Models of Living Systems by Philip Nelson](https://www.physics.upenn.edu/biophys/PMLS2e/index.html)
* [Biological Physics by Philip Nelson](https://www.physics.upenn.edu/biophys/BPse/)

Here are some wonderful lectures and prestantions about various topics in biophisycal modeling
* [James C Gumbart](https://www.youtube.com/watch?v=tp-FPanCaWM)
* [Grant J Jensen](https://www.youtube.com/watch?v=FSOrXcWOMJU)
* [Sven Van Teffelen](https://www.youtube.com/watch?v=oYY03X2mZgw)
* [Cecile Morlot](https://www.youtube.com/watch?v=71c3rET3qAI&feature=youtu.be)
* [Bart Hoogenboom](https://www.youtube.com/watch?v=y-I0thStOv0)
* [Seamus Holden](https://www.youtube.com/watch?v=7GP5zZyTRPY)

# Getting Started with GitHub
If you are unfamiliar with GitHub or how it works, in this section you will find helpful tips and terminal commands to be able to perform the basic git commands that will be necessary for us to share code and findings. 
* Check out this [GitHub Tutorial Video](https://www.youtube.com/watch?v=DVRQoVRzMIY&list=WL&index=20&t=513s) for help understanding the basics. (One thing to note: the branch people used to call "master" is now typically called "main". In the video, replace "master"->"main".)
* Branches: Around 27 mins in the tutorial video, there's a nice illustration of using different branches (and even later a nice illustration of resolving conflicting changes). After you're used to the basics of git, revisiting the latter part of the tutorial might be helpful.

# Getting Started with learning Julia
As mentioned above we have chosen to work in the Julia programing language! In this section you will find helpful tips and tricks to get you started in working with this powerful language! 
* Check out this [Julia tutorial](https://syl1.gitbook.io/julia-language-a-concise-tutorial/) for on help setting up Julia and VS code on your computer
* Check out this [Julia tutorial](https://www.youtube.com/watch?v=sE67bP2PnOo) for a great introduction to the basic syntax 
* Check out this [Julia tutorial](https://docs.juliaplots.org/latest/tutorial/) to learn how plots work in Julia
* Check out this helpful conversation [thread](https://stackoverflow.com/questions/58087096/a-plot-describing-the-density-of-data-points-in-2d-space-in-julia) on Kernel Density plotting in Julia
* Check out this helpful conversation [thread](https://discourse.julialang.org/t/plotting-single-density-plot-for-table/51962) about plotting single density plots for tables
* [Random walk Julia tutorial](https://sje30.github.io/catam-julia/casestudies/randomwalks/randomwalksnotebook.html)

# BYU Supercomputing
In order to run the simulation software we make use of the BYU supercomputing lab. You can find more information about that as well as apply for a supercomputing account [here](https://rc.byu.edu/).

To learn how to setup a remote environment in VS Code, click [here](/supercomputer/VScode_setup.md).

# Getting Started with random walks 
A random walk is a simple model of fundamental biological processes and is a great place to start doing biophysics simulations.

## What is a random walk ?
* Check out this amazing [video](https://www.youtube.com/watch?v=stgYW6M5o4k) which helps explains the context around and the importance of random walks 
* Check out this amazing [video](https://www.youtube.com/watch?v=a3V0BJLIo_c) for an introduction to the diffusion equation
## Problem # 1
* Build a program using Julia which can simulate a random walk for *t* number of walkers each taking *n* number of steps. Plot the trajectory of the walkers in 1, 2 and 3 dimensions. Also see if you can plot the density distribution for each dimension! Feel free to compare your solution with Jack and Cayson's solutions.

## Problem # 2

* [2D Random walk](resources/SethnaStatMech_2Dwalk.pdf) problem from Jim Sethna's statistical mechanics book. This problem is insightful.


## Problem # 3

* [Bicycle Motion (2.1)](resources/Chapter_2_Giordano.pdf) problem from Giordano's textbook, chapter 2 on realistic projectile motion. Helpful in beginning to understand the coding behind projectile motion. 

## Problem # 4

* [Cannonball Trajectory (2.2)](resources/Chapter_2_Giordano.pdf) problem 2.2 from Giordano's textbook. Helpful in learning the dynamics of projectile motion in multiple dimensions. 

## Problem # 5

* [Natural Pendulum (3.3)](resources/Giordano_chap_3.pdf) problem from Giordano's textbook. Helpful in beginning to learn about chaotic motion as well as realistic harmonic motion. Take a look at problem 3.1 and 3.2 before as well for an introduction into simple harmonic motion.

## Problem # 6

* [Molecular Dynamics (9.1)](resources/Giordano_Chap_9.pdf) problem from Giordano's textbook is the culmination of the coding exercises we have worked on up until this point. You will be coding a realistic simulation of gas molecules acting according to the Lennart-Jones Potential relationship. Do your best to work through it, and for an easier starting exercise you can try and work through the simulation with elastic boundaries instead of periodic boundary conditions as it is there most bugs develop. 