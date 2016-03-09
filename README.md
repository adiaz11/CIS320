# CIS320
Alan Diaz 
CIS 320 
February 28, 2016 
Final Project Paper 

For this project, I had to learn about the coding language R which is primarily used for statistical analysis. Before this class, I had never heard of R and became curious at the beginning. Learning R was difficult because I had no previous knowledge with it. While I was in High School I learned a bit of C++ which made it somewhat easy for me to understand Java in my time here at Cal State LA. This project required us to acquire a set of statistics, load them into the R program, and graph the data. At first it did not sound too complicated, but I soon learned that I was wrong. 
The type of data that I chose to analyze with R is NFL Quarterback Statistics. There were many categories of data such as Passing Yards, Touchdowns, and Interceptions which gave me a lot of choices in terms of what statistics I could manipulate and show in a graph.
For the presentation, I will do a few simple examples of different data comparisons using a smaller data set. Right now, the graphs are plotting data for 50 NFL Quarterbacks who played in a Regular Season game. I will condense it to about 15 or so just to make the data look less cluttered and easier to see. In the first example, I plotted a simple scatter plot that shows the amount of yards and touchdowns a Quarterback has thrown. For the second example, I will do the same but I will display touchdowns and interceptions. 

Code Instructions

To upload the data to R enter the following:

> data1 <-read.csv(file.choose(), header=T)

Then if you want to see the data enter the following code:

> data1

To Calculate the Mean enter the following:

>sapply(data,mean)

To enter the data that will be used for the scatter plot enter the following:

>Touchdowns=data$TD

>Yards=data$Yds

>Interceptions=data$Int

To display the graph the data enter the following:

>plot(Touchdowns,Yards)

>plot(Touchdowns,Interceptions)
