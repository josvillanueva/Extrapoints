Ximena Correa A01734499

José Alfredo Peralta Soriano A01733723

José Antonio Villanueva A01737550

Bernardo Quintana López A01658064

Collaborative activity: Mini case 1 - Linear programming

Consider the WhiskasModel1.py
What are the two parameters that the LpProblem function implements? 
The first parameter is the name “The Whiskas Problem” and it represents the name of the linear program. The second parameter is “LPMinimize” and it indicates the type of the objective of the problem that is to minimize the objective function. 

Is it mandatory to name the prob variable as prob?
 No, it is not mandatory, we can choose any valid variable that describes and makes sense. 
 
What are LpContinous and LpInteger used for?
LpInteger is used for discrete data, in this case the number of cans produced, while LpContinous is used for a numerical data which is between two points and it is unspecified.

Explain and copy the section of code that defines the objective function.
min 0.013 * x1 + 0.008 * x2, this would give us the minimum price of each can by multiplying the price of chicken and beef with the minimum required  percentage of chicken and beef in each can.

Explain and copy the section of code that defines the constraints.
![# The five constraints are entered](https://github.com/josvillanueva/Extrapoints/assets/133794349/7bad8e24-95b7-4ea6-b2f3-319a0091f07b)


The first one ensures that the sum of x1 and x2 is equal to 100. It enforces a constraint on the total percentage allocation. The second one, represents a protein requirement. It specifies that the protein content, calculated by multiplying the percentage of x1 with 0.100 and the percentage of x2 with 0.200, should be greater than or equal to 8.0. The third one defines a fat requirement. It states that the fat content, obtained by multiplying the percentage of x1 with 0.080 and the percentage of x2 with 0.100, should be greater than or equal to 6.0. The fourth one, sets a maximum limit on the fiber content. It specifies that the fiber content, calculated by multiplying the percentage of x1 with 0.001 and the percentage of x2 with 0.005, should be less than or equal to 2.0. And the last one represents a salt requirement. It limits the salt content, obtained by multiplying the percentage of x1 with 0.002 and the percentage of x2 with 0.005, to be less than or equal to 0.4.

 
Is this a minimization or maximization problem?
Since the objective is to minimize the cost, this is a minimization problem. The problem aims to find the minimum cost solution 

 that satisfies the nutritional requirements specified on the cans. By adjusting the quantities of each ingredient used, Uncle Ben's wants to minimize the cost while still meeting the desired nutritional standards for their cat food products.

Run the WhiskasModel1.py code. (no need to make changes, just run it as is) What is the value of the following variables. 
Status: 
Beef Percent =66.0
 Chicken Percent =34.0
Total Cost of Ingredients per can =0.97
