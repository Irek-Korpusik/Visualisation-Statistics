#Inferential Statistics 
Applying your skills in R produce an analysis of a problem that will engage the reader on both the emotional and rational level. Analysis need to apply statistical inference and in particular one of the following methods: linear multiple regression, logistic regression, t-test, ANOVA

# Download 2 or 4 files from https://data.smartdublin.ie/dataset/dublinbikes-api
or from here:
https://data.smartdublin.ie/dataset/dublinbikes-api/resource/aab12e7d-547f-463a-86b1-e22002884587
https://data.smartdublin.ie/dataset/dublinbikes-api/resource/8ddaeac6-4caf-4289-9835-cf588d0b69e5

You can download 4 files (from January 2020 to January 2021), but don't forget to add into 3rd chunk of code : 
df_2 <- read.csv("dublinbikes_20200701_20201001.csv")
df_3 <- read.csv("dublinbikes_20201001_20210101.csv")
dublinbikes = rbind(df_3, rbind(df_2, rbind(df,df_1)))

##2 extra .csv files
https://data.smartdublin.ie/dataset/dublinbikes-api/resource/99a35442-6878-4c2d-8dff-ec43e91d21d7
https://data.smartdublin.ie/dataset/dublinbikes-api/resource/5328239f-bcc6-483d-9c17-87166efc3a1a

