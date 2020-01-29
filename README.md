# Merger
Merging LDM or XY coordinates for WETFEET

setwd()
DF1<-read.csv("")
DF2<-read.csv("")
str(DF1);str(DF2)
DF3<-merge(DF1, DF2,by=c("Sampling","Code"),all=TRUE)
levels(DF1$Code);levels(DF2$Code)
write.csv(DF3,"complete.csv")
levels(as.factor(DF1$Sampling))

levels(DF1$Sampling)
str(DF1)

