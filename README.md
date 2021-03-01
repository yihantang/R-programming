# module 7 assignment

#decide the datasets

mydata <-nottem

#check mydata

mode(mydata)

typeof(mydata)

class(mydata)

isS4(mydata) #check the mydata is S4 or not

otype(mydata)

#create a new data

j <- list(year=1918, month="Jan", temp= 40.3)

class(j)<- "average temp"

attributes(j)

j

#try S4
setClass ("averagetemp",
         slots = c(year= "numeric",month="character",temp="numeric") )

newinfo<- new("averagetemp", year=1918, month="Jan", temp=40.3)

newinfo
