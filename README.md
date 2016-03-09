# CIS320

Code Instructions
To upload the data to R enter the following: 
> data1 <-read.csv(file.choose(), header=T)
Then select the .csv where you saved it
To see the data enter the following code:
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
