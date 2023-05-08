Download Link: https://assignmentchef.com/product/solved-stats506-problem-set-1
<br>
<h1>Question 1</h1>

In this question you will use command line tools to answer question about the 2015 Residential Energy

Consumption Survey (RECS 2015) <a href="https://www.eia.gov/consumption/residential/data/2015/index.php?view=microdata">data set</a><a href="https://www.eia.gov/consumption/residential/data/2015/index.php?view=microdata">.</a>

In addition to your Rmd file, please submit a shell script ps1_q1.sh written in <em>Bash</em> using the “shebang” #!/ bin/bash. Your script should assume the file recs2015_public_v3.csv is in the same directory and be executable as bash ps1_q1.sh.

<h2>Part A</h2>

In part A, your solution to each question should be a Linux “one-liner”, i.e. a series of one or more commands connected by pipes “|”. Please provide both your solution and the result. Your solution must be written in text so that it can be copied and pasted if needed.

<ul>

 <li>How many rows are there for region 3 in the RECS 2015 data set?</li>

 <li>Write a one-liner to create a compressed data set containing only the variables: DOEID, NWEIGHT, and BRRWT1-BRRWT96.</li>

</ul>

<h2>Part B</h2>

<ul>

 <li>Write a Bash for loop to count and print the number of observations within each region.</li>

 <li>Produce a file txt providing a sorted list showing unique combinations of values from REGIONC and DIVISION. Include the contents of that file in your solution. <em>Hint:</em> See man uniq.</li>

</ul>

<h1>Question 2</h1>

In this question, you will use <strong>R</strong> to answer questions about flights originating in New York City, NY (NYC) in

2013 and 2014. Data for 2013 can be found in the nycflights2013 <strong>R</strong> package. Data through October 2014 is available <a href="https://raw.githubusercontent.com/wiki/arunsrinivasan/flights/NYCflights14/flights14.csv">here</a><a href="https://raw.githubusercontent.com/wiki/arunsrinivasan/flights/NYCflights14/flights14.csv">.</a> Your answers should be submitted as nicely formatted tables produced using Rmarkdown.

<ul>

 <li>Which airlines were responsible for at least 1% of the flights departing any of the three NYC airports between January 1 and October 31, 2013?</li>

 <li>Among the airlines from part “a”, compare the number and percent of annual flights in the first 10 months of 2013 and the first 10 months of 2014. Your table should include: the airline name (not carrier code), a nicely formatted number (see format()), percents for each year with 95% CI, and change in percent with 95% CI. Which airlines showed the largest increase and decrease? Why do some airlines show an increase in the percent of flights but a decrease in the number of flights?</li>

 <li>Among of the three NYC airports, produce a table showing the percent of flights each airline is responsible for. Limit the table to the airlines identified in part a and include confidence intervals for your estimates. Which airline is the largest carrier at each airport?</li>

</ul>

<h1>Question 3</h1>

In this question, you will use <strong>R</strong> to answer questions about the RECS 2015 data. You should read the section on computing standard errors available <a href="https://www.eia.gov/consumption/residential/data/2015/pdf/microdata.pdf">here</a><a href="https://www.eia.gov/consumption/residential/data/2015/pdf/microdata.pdf">.</a> For each question, produce a nicely formatted table and graph to support you answer. In your tables and graphs please provide standard errors for all point estimates.

<ul>

 <li>What percent of homes have stucco construction as the <em>major outside wall material</em> within each division? Which division has the highest proportion? Which the lowest?</li>

 <li>What is average total electricity usage in kilowatt hours in each division? Answer the same question stratified by urban and rural status.</li>

 <li>Which division has the largest disparity between urban and rural areas in terms of the proportion of homes with internet access?</li>

</ul>