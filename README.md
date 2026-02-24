# A-Mathematical-and-Simulation-Based-Study-of-Hiring-Strategies
Recruitment involves decisions under uncertainty: candidates are interviewed one by one, without knowing the quality of future applicants. This project models hiring using the Secretary problem to mathematically analyze and simulate strategies that maximize the probability of selecting the best candidate.
Overview
This project models recruitment as an instance of the Secretary problem, a classical probability problem involving sequential decisions under uncertainty.
The objective is to analyze and simulate strategies that maximize the probability of selecting the best candidate when interviews occur one by one and decisions cannot be changed.
________________________________________
Objectives
•	Formulate the hiring problem mathematically
•	Derive and explain the 37% optimal stopping rule
•	Validate results using Monte Carlo simulations
•	Compare theoretical and empirical success rates
________________________________________
Method
The project combines:
•	Probability and combinatorics
•	Calculus-based optimization
•	Statistical simulation in Python
Simulations confirm that rejecting approximately the first 37% of candidates and then selecting the next best observed candidate maximizes the probability of choosing the overall best applicant.
________________________________________
Technologies
•	Python
•	NumPy
•	Matplotlib
•	Jupyter Notebook
________________________________________
How to Run
git clone <repository-url>
pip install -r requirements.txt
jupyter lab
Open hiring_strategy.ipynb and run all cells.
________________________________________
Author
Ina Dimitrova
Math Concepts for Developers – Final Project
