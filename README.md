# emap-homework-4--movie-ratings-over-time-p0-solved
**TO GET THIS SOLUTION VISIT:** [EMAP Homework 4- Movie Ratings over Time¶ P0 Solved](https://www.ankitcodinghub.com/product/emap-movie-ratings-over-time%c2%b6-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124604&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EMAP Homework 4- Movie Ratings over Time¶ P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Here are the tables and their respective columns:

• rating

• rid: reviewer id, int

• mid: movie id, int

• stars: stars given to a movie, 0 to 5, int

• movie

• mid: movie id, int

• title: title of the movie, text

• year: year of the movie was released, integer

• director: director of the movie, text

• reviewer

• rid: reviwer id, int

• name: name of reviewer, text

Task 1¶ Write the SELECT query that finds all the movies that have a rating range (max stars-min stars) less than or equal to 1 stars but with at least 2 reviews. Your query should return the title of Assignment Project Exam Help

each movie and the rating range for the corresponding movie. Your SQL query should be

written as a string variable called query in Python.

import sqlite3

In [9]:

In [2]:

### TEST FUNCTION: test_tight_range

# DO NOT REMOVE THE LINE ABOVE

query = “””

“”” Task 2¶

Write the SELECT query, as a string variable called query, that returns the summary of the movies, i.e. for each movie you should report, in the following order:

• the movie title

• the director of the movie. If a movie’s director is NULL, assign ‘Unknown Director’ to those observations. Hint: COALESCE

• the year that movie was filmed

• the number of ratings that movie receives

• the average stars of that movie across all ratings In [3]:

### TEST FUNCTION: test_summary

# DO NOT REMOVE THE LINE ABOVE

query = “””

“””

In [14]:

Task 3 – creating variables¶

To answer the question whether movies before 1980 were better, please calculate the average rating for each movie, then calculate the average of these averages before vs after 1980. Your SELECT statement should return 2 averages, one for before and one for after 1980. Please assign the difference between the two averages to the variable old_vs_new.

In [4]:

### TEST FUNCTION: test_old_vs_new

# DO NOT REMOVE THE LINE ABOVE query = “””

“””

Task 4 – identifying bad data and multiple joins¶

In [5]:

### TEST FUNCTION: test_null

# DO NOT REMOVE THE LINE ABOVE

query = “””Assignment Project Exam Help

“””
