# Los Angeles Sports Teams Percent Wins

**__Look at Assignment4.ipynb to look at code on how the data was generated.__**

---
### Question:
From time to time, Dr. Chris Brooks may want to share your work
anonymously (via social media channels such as Twitter), to highlight some of
the accomplishments of learners in this course.
If you agree that you are comfortable with instructor sharing your
Assignment #4 as an example of great work, please type YES in the text box.
The submitter's response goes here.

### Answer:

Yes

---

### Question:
State the region and the domain category that your data sets are about (e.g.,
Chaohu, China and sports or athletics).

### Answer:
Los Angeles, California, United States of America
Sports and Athletics

---

### Question:
Create a research question about the domain category and region that you
identified.


### Answer:
How have the win percentages for four professional sports teams (The Los Angeles Lakers , The Los Angeles Kings,
Los Angeles Dodgers, and The Los Angeles Rams) of different sports categories (basketball, hockey, baseball, and football)
change over the last thirty years?

---

### Question:
Provide at least two links to publicly accessible datasets. These could be links
to files such as CSV or Excel files, or links to websites which might have data
in tabular form, such as Wikipedia pages.

### Answer:
Basketball (Los Angeles Lakers) https://en.wikipedia.org/wiki/List_of_Los_Angeles_Lakers_seasons
Hockey (Los Angeles Kings) https://en.wikipedia.org/wiki/List_of_Los_Angeles_Kings_seasons
Baseball (Los Angeles Dodgers) https://en.wikipedia.org/wiki/List_of_Los_Angeles_Dodgers_seasons
Football (Los Angeles Rams) https://en.wikipedia.org/wiki/List_of_Los_Angeles_Rams_seasons 

I also provide a .zip file that contains the my web scraping code
that retrieve the data from the web pages on December 5, 2017. Since
the web page may change or may not be available in the future, I also
included the raw data scraped and saved into a .csv file. I provide
as well the data cleaned as a .csv file. The clean data .csv files
are what I used to generate the graphs. You can use those to 
reproduce the graph. 

---

### Question:
Provide a short (1-2 paragraphs) justification of how your visual addresses
your research question.

### Answer:
This visual was concerned with answering the question of how the win percentages for four professional sports teams 
(The Los Angeles Lakers , The Los Angeles Kings, Los Angeles Dodgers, and The Los Angeles Rams) of different sport 
categories (basketball, hockey, baseball, and football) change over the last thirty years? Wikipedia was scraped
for data concerning wins and lossses by season for each team. The data is actually drawn back from 1970 but
the clean data starts at 1980. The reason being that not all the teams had data prior to 1970 and to have 
a rolling mean of 10 years, the first 10 years will be NaN (not a number.) NHL had a lockout in 2004-05 so the
season was cancelled. A fill-forward was used in order to still calculate the rolling mean. Los Angeles is 
a big city and it has multiple professional teams in the same league such as NBA basketball (Lakers and Clippers,)
and NFL football (Rams, and Chargers.) It is intereting to see how well these teams due overall in a city
with many teams. A decade rolling mean was plotted to help the viewer identify trends in the team's win
percentages.

The line plot indicates that overall the Los Angeles Kings and Dodgers hover around the same value levels for the
last 30 years. The is not as much volatility when compared to the Lakers or the Rams. The Lakers, however showed
a high win % near 30 years ago and remained pretty high, with some volatility until are 2010. After that, there
is a sharp decline. Up until recently, Lakers were consistently higher in win percentage when compared against 
Dodgers and Kings but now they are below them. The Rams, on the other hand have the most dynamic range. 30 years
ago, the team had a high win percentage but have been on a steady decline for approximately 18 years. Their 
success in win percentage rose to about the same level as Dodgers and Kings between 2000 to 2010. Rams had 
a sharp decline since and still on the decline. Based on the line plot alone, overall Lakers seem to be the 
exciting team with high hopes of success until recently; Kings and Dodgers have been consistently average
hovering around 0.5 win percentage; Rams have been consistantly getting worse over the last 30 years, with
signs of approvement for a decade (2000 to 2010 period) but have resumed to deliver disappointing win percentages
around 2008 afterwards declining at a much more rapid rate and dropping at values lower than before.

---

### Question:
As this assignment is for the whole course, you must incorporate and defend
the principles discussed in the first week, specifically, Cairo’s principles of
truth, beauty, function, and insight.

### Answer:
Addressing Cairo's principles.

**Truthfulness:**
This plot is as truthful as possible, but as Cairo's mention, truthfulness is subjective. 
In the case of this assignment, the data was taken from wikipedia. We assume that the data 
provided is 100% accurate but we cannot tell 100%. So the truth is based on the 
assumption that what we were given is telling the truth in the first place. The graph
avoids misleading representation by having a note expain Win % = games won/(games won + games lost).
Also, by labeling the x and y axis to Season and 10 Year Moving Average Win % respectively, makes
it clear and not misleading what is being represented on the graph. The title, Los Angeles 
Sports Teams Win % (10 Year Moving Average,) is descriptive leaving no room for ambiguity.
So, truthfulness is related to the x-axis, y-axis, title, plot, and legend note elements
of the graph.

**Beauty:**
Beauty is subjective and contextual. I believe the graph is beautiful due to selective information
provided to allow the user to get relevant information quickly and not spend too much time being
bogged down trying to decipher the graph. The graph sparse and provides enough information to
get the general idea with colors that differ from each other. Using clear pring font (i.e. not cursive),
colors that are not obnoxious and that pop from the background yet differ from each other (the plot line colors)
makes it pleasing to the eye. Also, people familiar with the teams will appreciate that the team colors
were used for their respected plot. So beauty is related to the choice of not chosing obnoxious colors but
rather the team color, the clear print font, and different background color elements of the graph.

**Functionality:**
The plot gives a quick overview of the win percentage (via rolling mean,) over the last 3
decades. Chosing a line plot as a charting type seemed the more appropriate because we can see
the continous progress of the teams over the last 3 decades. So the functionality relates to,
charting type being a line plot for continuous information of 3 decades.


**Insightful:**
Viewers do not have the large enough time to do full reviews. Having the information jump out
quickly gives them insight on the situation easily. This is facilitated with colors chosen 
that resemble the team color, it should make it quickly identifiable to those familiar with the
team. The value makings for x is every 10 years, easy to see time periods. The value markings 
for 7 or 0, 0.25, 0.5, 0.75. All easy numbers to associate as landmarks in your head without 
the use of a calculator. So the insightfulness to producing a "eureka" or "aha" response 
in the viewer relates to the element of the colors of the line plot associated with the team. 
The other elements that relate to insightfulness are the value markings for the x and y axis.

---