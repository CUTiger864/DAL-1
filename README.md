# DAL-1
# Title: #### #John Covington: #January 14, 2021
# Let's Try Some Basic Arithmetic
1+11+1
13
365/12365/12
12*10
28 + 3828+38
R1+1*(365/12)
6*6= 36
9/3.142
# Lesson 2 ####
# Learning to assign variables 
myFirstVar<- "Hello world!"
mySecondVar<-16 
home <-"Clemson"
h_mascot <-"Tigers"
away <-"Ohio State"
away_mascot <-"Buckeyes"
homeScore <- 31
awayScore <- 0
homeWin<-TRUE
awayWin<-FALSE
class(Tigers)
class(31)
class(TRUE)
str(Tigers)
str(31)
str(TRUE)
homeScore <- as.integer(31)
homeScore
awayScore <- as.integer(0)
awayScore

vector_numeric <-c(12, 8, 16, 4, 15)
str(vector_numeric)
MyNumericVector <-c(10, 2, 14, 6, 9)
str(MyNumericVector)
vector_logical <-c(TRUE, TRUE, FALSE, T, F)
str(vector_logical)
myLogicalVector <-c(FALSE, TRUE, TRUE, FALSE, FALSE)
str(myLogicalVector)
vector_character <-c("Montana", "Aikman", "Manning", "Favre", "Mahomes")
str(vector_character)
myCharVector <-c("Rivers", "Newton", "Marino", "Kelley", "Elway")
str(myCharVector)
drAllardList <-list(vector_numeric, vector_logical, vector_character)
str(drAllardList)
myList <-list(MyNumericVector, myLogicalVector, myCharVector)
str(myList)
QB_df <-data.frame(vector_character, vector_numeric, vector_logical)
QB_df
str(QB_df)
QB_df$vector_numeric
names(QB_df)[names(QB_df)=="vector_character"] <- "qbName"
str(QB_df)
QB_df[1,]
QB_df[,1]
QB_df[,"qbName"]
QB_df[1]
QB_df["qbName"]
QB_df[3,2]
QB_df <-data.frame(myCharVector, MyNumericVector, myLogicalVector)
QB_df
str(QB_df)
QB_df$MyNumericVector
QB$columnName
names(QB_df)[names(QB_df)=="myCharVector"] <- "qbName"
str(QB_df)
QB_df[1,]
QB_df[,3]
QB_df[1,2]
names(QB_df)
names(QB_df)[names(QB_df)=="vector_numeric"]
names(QB_df)[names(QB_df)=="vector_numeric"] <- "jerseyNum"

