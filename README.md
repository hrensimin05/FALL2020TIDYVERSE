# FALL2020TIDYVERSE
CUNY DATA 607 TIDYVERSE Collaborative project
```{r}
#Dominika Markowska-Desvallons
library(tidyverse)

#read csv file 
file<- read.csv("https://raw.githubusercontent.com/hrensimin05/Data_607/master/2019.csv")
#view(file)

list<-as.data.frame(file)%>% 
  arrange(desc(Healthy.life.expectancy))

head(list)
