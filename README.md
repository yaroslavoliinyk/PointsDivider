# PointsDivider using GeneticAlgorithm
*Created by Yaroslav Oliinyk*

### The purpose of the following program is *to create a polinomium which will separate 2 sets of dost*(RED dots from BLUE dots)

#### We have such polinomium: *y = a + b*x + c*x<sup>2</sup>*

Our genetic algorithm will find the best coefficients: a,b,c

		POINTS DIVIDER ALGORITHM
 
	Launching the program

1. Download the repository
2. Extract the program in "Downloads" folder
3. Use the following command: "cd ~/Downloads/PointsDivider/PointsDivider/src"
4. Then this: "javac -cp jcommon-1.0.23.jar:jfreechart-1.0.19.jar: Main.java"
5. Then: "java -cp jcommon-1.0.23.jar:jfreechart-1.0.19.jar: Main"
6. Well done! The program is running.

	Interface and controlling
1. The program will propose you to insert RED and BLUE dots by yourself or generate them.
2. In case of choosing insert by yourself you will need to wite the coordinates of firstly RED points(which are also called POSITIVE)
3. For example you've entered 10 points and you want to stop, then write in the coordinate somthing that's not a number and you'll be switched to writing coordinates of BLUE points
4. After writing coordinates of BLUE(NEGATIVE) points simply as it was with RED points write smth, that's not a number to finish entering points.
5. In case you chose to generate points, they will be geneated right away without effort.
6. Then after all the points are entered, the algoriths starts to work and eventually you should receive a graph with polinomials, starting from the 1 generation to the last.
7. The last polinomial will be the best divider.
8. Meanwhile in console you cn observe the evolution of the population.
9. Have fun!

	All rights are reserved
		2019


