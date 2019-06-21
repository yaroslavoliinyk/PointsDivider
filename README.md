# PointsDivider using Genetic Algorithm
*Created by Yaroslav Oliinyk*

* The purpose of the following program is 
***to create a polinomium which will separate 2 sets of dots***(RED dots from BLUE dots)

* We have such polinomium: ***y = a + bx + cx<sup>2</sup>***

* Our genetic algorithm will find the best coefficients: ***a,b,c***

## POINTS DIVIDER ALGORITHM
 
### Launching the program
 
1. Download the repository
2. Extract the program in "Downloads" folder
3. Use the following command: "cd ~/Downloads/PointsDivider/PointsDivider/src"
4. Then this: "javac -cp jcommon-1.0.23.jar:jfreechart-1.0.19.jar: Main.java"
5. Then: "java -cp jcommon-1.0.23.jar:jfreechart-1.0.19.jar: Main"
6. Well done! The program is running.

### Interface and controlling

* The program will propose you to insert **RED** and **BLUE** dots by yourself or generate them.
>![Choice](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/1.png)
* In case of choosing insert **by yourself** you will need to write the coordinates of firstly **RED** points(which are also called **POSITIVE**)
* For example you've entered 5 points and you want to stop, then write in the coordinate something **that's not a number** and you'll be switched to writing coordinates of **BLUE** points
>![Insert RED dots](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/5.png)
* After writing coordinates of **BLUE**(NEGATIVE) points simply as it was with RED points write smth, **that's not a number** to finish entering points.
>![Insert BLUE dots](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/6.png)
* In case you chose to ***generate points***, they will be geneated right away without effort.
>![Generation](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/4.png)
* Then after all the points are entered, the ***algorithm starts to work*** and eventually you should receive a **graph** with polinomials, starting from the first generation to the last.
### Example 1:
>![Graph 1](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/2.png)
### Example 2:
>![Graph 2](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/3.png)
* The last polinomial will be ***the best divider***.
	* In **Example 1** is a **red polinomium**
	* In **Example 2** is a **pink polinomium**
* Meanwhile in console you can observe the evolution of the population.
##### Staring population
>![Staring population](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/7.png)
##### Evaluation
>![Evaluation population](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/8.png)
##### Parents
>![Parents population](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/9.png)
##### Crossover
>![Crossover population](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/10.png)
##### Mutation
>![Mutation population](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/11.png)
##### Evaluation of NEW population
>![Evaluation population](https://raw.githubusercontent.com/yaroslavoliinyk/PointsDivider_GeneticAlgorithm/master/pics/11.png)
### Have fun! :+1: 

	All rights are reserved
		2019


