# CIS320

Code Instructions
> data1 <-read.csv(file.choose(), header=T)
If you want to see the data enter the following code:
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
