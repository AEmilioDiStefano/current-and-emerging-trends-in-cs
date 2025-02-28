## Briefly explain the work that you did on this project: 
### What code were you given?
The Python code which I was given included a GameExperience class meant to store learned information and a TreasureMaze class meant to define the actual maze that the intelligent agent is meant to navigate.  The provided code also included a Jupyter Notebook file including a ‘qtrain()’ function with pseudocode for training the intelligent agent.
 
### What code did you create yourself?
I first wrote code to reflect what was being portrayed in the pseudocode, which was meant to use the aforementioned classes and the other functions provided in the IPYNB file to train the intelligent agent to solve the maze in as few epochs and in as little time as possible.  Upon implementing the code written to bring to life what was in the provided pseudocode, the system took hundreds of epochs ofer tens of minutes to finally solve the maze.  In order to make the agent’s learning process more efficient, I added some functions to control different aspects of the learning process.  This included a function for decreasing the data size across epochs to increase efficiency, an early stopping method to avoid overfitting, and three different functions for the decay of epsilon: one for linear decay, another for exponential decay, and another for discrete interval (step) decay.  I then broke the 'qtrain()' function into five different functions in order to increase modularity and reusability.  With the addition and proper use of these functions and modifications, I was able to drastically improve the system’s performance to the point where the agent was able to solve the maze 100 out of 100 times (100% success rate) after only 32 epochs and in under 5 minutes within the environment of the Apporto environment (virtual machine) provided to me though SNHU for this course.   


## Connect your learning from throughout this course to the larger field of computer science:
### What do computer scientists do and why does it matter?
Computer science encompasses a wide range of diverse programmatic disciplines meant to communicate commands to a machine in hopes that it will execute them in a way which solves a given problem.  The computer science covered in this course is meant to solve problems through the use of artificially intelligent agents which approximate human thought in their solving of problems, including the solving of the simple maze included in Project Two.  The role of computer scientists is incredibly important to society, especially in our current age where humanity has become so accustomed and even largely dependent on the computer systems which make our modern world possible.  


### How do I approach a problem as a computer scientist?
As a computer scientist, I approach problems as opportunities to prove and to further develop my abilities and skills as a professional.  I relish these challenges, as my education in this field has fomented within me a need to refine these skills and to use them for the betterment of humankind.  I find the materials included in this course especially promising for the advancement of humanity, and I believe that the collaborative masterpiece which is modern artificial intelligence will increasingly be used in every aspect of human life.   


### What are my ethical responsibilities to the end user and the organization?
My ethical responsibilities to the end user include the protection of user data, the respecting of user privacy, and the facilitation of user interaction with the systems which I engineer and develop.  My ethical responsibilities to public and private client organizations include the development and engineering of problem-solving systems and the general advancement of the organization itself. 
