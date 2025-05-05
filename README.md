# cmsc320-project-2-exploring-moneyball-solved
**TO GET THIS SOLUTION VISIT:** [CMSC320 Project 2-Exploring Moneyball Solved](https://www.ankitcodinghub.com/product/cmsc320-project-2-exploring-moneyball-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98630&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC320 Project 2-Exploring Moneyball Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
# Project 2

In this project you will apply your data wrangling and exploratory data analysis skills to baseball data. In particular, we want to know how well did [Moneyball](https://en.wikipedia.org/wiki/Moneyball_(film)) work for the [Oakland A’s](https://en.wikipedia.org/wiki/Oakland_Athletics). Was it worthy of a movie? (I’m sad to say that watching the movie is unlikely to help with completing the project).

For this project, the _writeup_ is a crucial part of your marks. As we’ve discussed in class, the Notebooks themselves aren’t just about the code, they’re for communicating ideas to the reader. Make sure you spend non-trivial time _explaining_ your methods, otherwise you will lose a significant amount of points. This includes things like correct labelling of plots and other aspects of communicating results.

## A bit of background

We’ll be looking at data about teams in [Major League Baseball](https://en.wikipedia.org/wiki/Major_League_Baseball). A couple of important points:

Major League Baseball is a professional baseball league, where teams pay players to play baseball. The goal of each team is to win as many games out of a 162 game season as possible. Teams win games by scoring more runs (“getting more points”) than their adversary. In principle, better players are costlier, so teams that want good players need to spend more money. Teams that spend the most, frequently win the most. So, the question is, how can a team that can’t spend so much win? The basic idea that Oakland (and other teams) used is to redefine what makes a player good, i.e., figure out what player characteristics translated into wins. Once they realized that teams were not really pricing players using these characteristics, they could exploit this to pay for undervalued players, players that were good according to their metrics, but were not recognized as such by other teams, and therefore not as expensive.

You can get more information about this period in baseball history from:

[Wikipedia](http://en.wikipedia.org/wiki/Moneyball)

[The Moneyball book](http://www.amazon.com/Moneyball-The-Winning-Unfair-Game/dp/0393324818)

[The Moneyball movie](http://www.imdb.com/title/tt1210166/)

## The Data

You will be using data from a very useful database on baseball teams, players and seasons curated by Sean Lahman available at [http://www.seanlahman.com/baseball-archive/statistics/](http://www.seanlahman.com/baseball-archive/statistics/). The database has been made available as a `sqlite` database [https://github.com/jknecht/baseball-archive-sqlite](https://github.com/jknecht/baseball-archive-sqlite). `sqlite` is a light-weight, file-based database management system that is well suited for small projects and prototypes.

You can read more about the dataset here: [http://seanlahman.com/files/database/readme2014.txt](http://seanlahman.com/files/database/readme2014.txt). (Mirror: [readme2014.txt](mirror/readme2014.txt))

You can download the `sqlite` file directly from github at [https://github.com/jknecht/baseball-archive-sqlite/raw/master/lahman2014.sqlite](https://github.com/jknecht/baseball-archive-sqlite/raw/master/lahman2014.sqlite).

You will be accessing the `sqlite` database in python using the [sqlite package](https://docs.python.org/3/library/sqlite3.html). This package provides a straightforward interface to extract data from `sqlite` databases using standard SQL commands.

Once you establish a connection with the `sqlite` database, you can store query results directly in a pandas dataframe using the [read_sql](http://pandas.pydata.org/pandas-docs/version/0.15.0/generated/pandas.read_sql.html) function.

For example, here’s how you would tabulate total league payrolls for each year:

“`

import sqlite3

import pandas

sqlite_file = ‘lahman2014.sqlite’

conn = sqlite3.connect(sqlite_file)

salary_query = “SELECT yearID, sum(salary) as total_payroll FROM Salaries WHERE lgID == ‘AL’ GROUP BY yearID”

team_salaries = pandas.read_sql(salary_query, conn)

team_salaries.head()

“`

The result would look something like:

| | yearID | total_payroll |

| — | — | — |

| 0 | 1985 | 134401120.0 |

| 1 | 1986 | 157716444.0 |

| 2 | 1987 | 136088747.0 |

| 3 | 1988 | 157049812.0 |

| 4 | 1989 | 188771688.0 |

## The Question

We want to understand how efficient teams have been historically at spending money and getting wins in return. In the case of Moneyball, one would expect that Oakland was not much more efficient than other teams in their spending before 2000, were much more efficient (they made a movie about it after all) between 2000 and 2005, and by then other teams may have caught up. Your job in this project is to see how this is reflected in the data we have.

## Organization of the Project

Each part of the project is split into two aspects: The _problems_ and the _questions_. The _problems_ are to be solved with code. This code should be documented and formatted in a manner that makes understanding the code feasible. The _questions_ are meant to be answered with prose. Notice that each question is worth more than each problem: A hastily written sentence is unlikely to earn full marks.

## Part 1: Wrangling

The data you need to answer these questions is in the Salaries and Teams tables of the database.

#### Problem 1 (8 pts)

Using SQL compute a relation containing the total payroll and winning percentage (number of wins / number of games * 100) for each team (that is, for each teamID and yearID combination). You should include other columns that will help when performing EDA later on (e.g., franchise ids, number of wins, number of games).

Include the SQL code you used to create this relation in your writeup. Describe how you dealt with any missing data in these two relations. Specifically, indicate if there is missing data in either table, and how the type of join you used determines how you dealt with this missing data. One note, for SQL you have to be mindful of integer vs. float division.

I mentioned in the lectures that some folks find Pandas simpler to use than SQL, and that’s true. However, there are cases where SQL is unavoidable. If the data is already stored in a database, you’d need to know at least enough SQL to get the data out.

## Part 2: Exploratory Data Analysis

### Payroll Distribution

#### Problem 2 (8 pts)

Write code to produce plots that illustrate the distribution of payrolls across teams conditioned on time (from 1990-2014).

#### Question 1 (9 pts)

What statements can you make about the distribution of payrolls conditioned on time based on these plots? Remember you can make statements in terms of central tendency, spread, etc.

#### Problem 3 (8 pts)

Write code to produce plots that specifically show at least one of the statements you made in Question 1. For example, if you make a statement that there is a trend for payrolls to decrease over time, make a plot of a statistic for central tendency (e.g., mean payroll) vs. time to show that specficially.

### Correlation between payroll and winning percentage

#### Problem 4 (8 pts)

Write code to discretize year into five time periods (you can use [pandas.cut](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.cut.html) to accomplish this) and then make a scatterplot showing mean winning percentage (y-axis) vs. mean payroll (x-axis) for each of the five time periods. You could add a regression line (using, e.g., NumPy’s [polyfit](https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html)) in each scatter plot to ease interpretation.

#### Question 2 (9 pts)

What can you say about team payrolls across these periods? Are there any teams that standout as being particularly good at paying for wins across these time periods? What can you say about the Oakland A’s spending efficiency across these time periods (labeling points in the scatterplot can help interpretation).

## Part 3: Data transformations

### Standardizing across years

It looks like comparing payrolls across years is problematic so let’s do a transformation that will help with these comparisons.

#### Problem 5 (8 pts)

Create a new variable in your dataset that standardizes payroll conditioned on year. So, this column for team `i` in year `j` should equal:

&lt;!–

“`

$ standardized\_payroll_{ij} = \frac{{payroll}_{ij} – \overline{payroll}_{j} }{{s}_{j}} $

“`

–&gt;

![](figs/prob5_alternate.png)

for team `i` in year `j`.

where &lt;!–&lt;em&gt;&lt;span style=”text-decoration: overline”&gt;payroll&lt;/span&gt;&lt;sub&gt;j&lt;/sub&gt;&lt;/em&gt;–&gt; &lt;em&gt;avg\_payroll&lt;sub&gt;j&lt;/sub&gt;&lt;/em&gt; is the average payroll for year `j`, and &lt;em&gt;s&lt;sub&gt;j&lt;/sub&gt;&lt;/em&gt; is the standard deviation of payroll for year `j`.

#### Problem 6 (8 pts)

Repeat the same plots as Problem 4, but use this new standardized payroll variable.

#### Question 3 (9 pts)

Discuss how the plots from Problem 4 and Problem 6 reflect the transformation you did on the payroll variable.

### Expected wins

It’s hard to see global trends across time periods using these multiple plots, but now that we have standardized payrolls across time, we can look at a single plot showing correlation between winning percentage and payroll across time.

#### Problem 7 (8 pts)

Make a single scatter plot of winning percentage (y-axis) vs. standardized payroll (x-axis). Add a regression line to highlight the relationship.

The regression line gives you expected winning percentage as a function of standardized payroll. Looking at the regression line, it looks like teams that spend roughly the average payroll in a given year will win 50% of their games (i.e. win\_pct is 50 when standardized\_payroll is 0), and teams increase 5% wins for every 2 standard units of payroll (i.e., win\_pct is 55 when standardized\_payroll is 2). We will see how this is done in general using linear regression later in the course.

From these observations we can calculate the expected win percentage for team `i` in year `j` as

&lt;!–

“`

${expected\_win\_pct_{ij} = 50+2.5×standardized\_payroll_{ij}}$

“`

–&gt;

![](figs/prob7.png)

### Spending efficiency

Using this result, we can now create a single plot that makes it easier to compare teams efficiency. The idea is to create a new measurement unit for each team based on their winning percentage and their expected winning percentage that we can plot across time summarizing how efficient each team is in their spending.

#### Problem 8 (8 pts)

Create a new field to compute each team’s spending effiency, given by

&lt;!–

“`

$efficiency_{ij} = win\_pct_{ij} − expected\_win\_pct_{ij}$

“`

–&gt;

![](figs/prob8.png)

for team `i` in year `j`, where `expected_win_pct` is given above.

Make a line plot with year on the x-axis and efficiency on the y-axis. A good set of teams to plot are Oakland, the New York Yankees, Boston, Atlanta and Tampa Bay (teamIDs OAK, BOS, NYA, ATL, TBA).

#### Question 4 (9 pts)

What can you learn from this plot compared to the set of plots you looked at in Question 2 and 3? How good was Oakland’s efficiency during the Moneyball period?

## Extra Credit (15 pts)

The data used in this project is starting to get a bit old. The extra credit is ambitious: Can you create a new sqlite database that has the newest available data (up to 2020)? Explain your method with code and prose, if your explanation is reproducible, you will get the points. In order for a method to be reproducible you must provide code that can access the data online, mangle the data as necessary and the SQL necessary for creating the new sqlite database. Use the prose to describe where you found the data and what steps might be necessary to access that data (account creation/authentication/etc.). Any steps that require human intervention should be clearly described in prose.
