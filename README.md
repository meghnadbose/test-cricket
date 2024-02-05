<h1>More Results, Closer Matches in Tests Now: But Will That Be Enough to Save Cricket’s 5-Day Format?</h1>

About the project: Test cricket seems to be replete with such tight finishes nowadays, and it led me to wonder, has men’s Test cricket become more exciting in recent years?

Findings: Even as Test cricket grapples with an existential crisis, an analysis of match results data reveals that the sport's longest format is a tighter contest now than it has been in a century.

Data collection process: I used BeautifulSoup to scrape pages from <a href="https://meghnadbose.github.io/data-stories/test_cricket.html](https://www.espncricinfo.com/records/list-of-match-results-by-year-307847" target="_blank">ESPNCricinfo's</a> list of Test match results. There was one page for each year from 1877 to 2023, and so I scraped more than 140 pages. I then analysed the match results data.

Overview of the data analysis process: The first question facing me was - how do we determine or compare how exciting Test matches are over a period? I did this using two factors.

<ul><li>Firstly, are more Test matches ending with decisive results instead of draws? Granted that some close draws can be thrilling to watch, but we wouldn’t want every other five-day encounter ending with no winner, right? Our first factor was, therefore, the percentage of draws in Test matches played over a given time period.</li>

<li>Secondly, how close were the matches? Did the team batting last win by one wicket or nine? Or did the team that bowled last win by 10 runs or 200? Typically, the smaller the margin of victory, the more exciting a match has been. Therefore, our second factor was be the margin of victory.</li></ul>

I also conducted interviews with three eminent cricket writers - Ayaz Memon, Venkatraman Ramnarayan, and Amit Sinha - to get their reactions to my data analysis and their insights on the topic.

What's new: This data project was one in which I did everything from the computation and analysis, to the reporting and front-end HTML coding myself. It was a great experience to be responsible for the full 360-degree production of a computation-aided data story. 

If I have more time to spend on this, I would add another two layers of complexity to the data - 

1. I would scrape the scorecards of each of the drawn Test matches from 1877 to 2023, and then categorise the closeness of the draws.

Not all draws are boring matches. Close draws, where the team batting last almost reached the target or were close to getting bowled out, definitely make for exciting cricket. A limitation of the metric in the story is that it relegates all draws to one point. A more advanced version of the rubric could give a close draw some additional points, depending on how close the match was to a result.

2. I would also use the scraped scorecards to map the run rates of each Test match from 1877 to 2023. I would then analyse the average run rate by year and by decade in men's Tests. This could be an additonal factor in our measurement of the excitement of Test matches.

<a href="https://meghnadbose.github.io/test_cricket" target="_blank">Read the full story here.</a>
