# Baseball
A look into a the Lahman Baseball database.

# THE DATA
The Lahman Baseball database is a comprehensive database that contains pitching, hitting, and fielding statistics for Major League Baseball from 1871 through 2016.

> Source: Sean Lahman's Baseball Database - http://www.seanlahman.com/baseball-archive/statistics/ and http://www.seanlahman.com/files/database/readme2016.txt

# THE ASK
Using the Lahman Baseball database, answer various questions and show the code you used to answer those questions in postreSQL.

# THE PROCESS
In order for me to get a grasp on the information in the database, I relied heavily on the database's dictionary to understand the acronyms and statistics presented. I used JOINs, Window Functions and Common Table Expessions (CTEs) to extrapolate historical facts for comparison.

**Questions:**

1.  Find the name and height of the shortest player in the database. How many games did he play in? What is the name of the team for which he played? 


         . Eddie Gaedel
			. 43"
            . He played 1 game.
            . He played for the St. Louis Browns.

    ![image](https://user-images.githubusercontent.com/59903096/78852964-56dbbd80-79e3-11ea-9880-b648ecc4d762.png)

2.  Which Vanderbilt player earned the most money in the majors? 


         . David Price
			. $81,851,296

     ![image](https://user-images.githubusercontent.com/59903096/78852535-2fd0bc00-79e2-11ea-923a-b48611bf0e15.png)


3. From 1970 – 2016, what is the largest number of wins for a team that did not win the world series? What is the smallest number of wins for a team that did win the world series? Doing this will probably result in an unusually small number of wins for a world series champion – determine why this is the case. 

    ![image](https://user-images.githubusercontent.com/59903096/78852816-fe0c2500-79e2-11ea-852c-f14ec51dbb54.png)


4. Which managers have won the TSN Manager of the Year award in both the National League (NL) and the American League (AL)? Give their full name and the teams that they were managing when they won the award.

        . David Allen Johnson
			. 1997 - Baltimore Orioles
			. 2012 - Washington Nationals
		. James Richard Leyland
			. 1988 - Pittsburgh Pirates
			. 1990 -Pittsburgh Pirates
			. 1992 - Pittsburgh Pirates
			. 2006 - Detroit Tigers

   ![image](https://user-images.githubusercontent.com/59903096/78852122-23982f00-79e1-11ea-8eef-a160994551d0.png)


# TAKEAWAYS

*Challenges:*

(Prior Knowledge) I don't know a whole lot about baseball, but I do know how to find what I'm looking for. The questions posed for this project required you to know about the sport and use subqueries or Common Table Expressions (CTEs) in order to find what you wanted. I gravitated towards CTEs since subqueries are still a bit of a challenge for me.


*Rewards:*

I learned the functionality of using CTEs, more information about baseball and how to code using postgreSQL by working my way from the inside-out to avoid errors. 
