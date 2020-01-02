# datasciencecoursera
mean(iris$Sepal.Length[iris$Species=="virginica"], na.rm = TRUE) or round(mean(iris$Sepal.Length[iris$Species=="virginica"], na.rm = TRUE))
apply(iris[,1:4],2,mean)
tapply(mtcars$mpg, mtcars$cyl, mean) and sapply( split(mtcars$mpg, mtcars$cyl) , mean)
cyl_4 <- round(mean(mtcars$hp[mtcars$cyl==4], na.rm = TRUE))
cyl_8 <- round(mean(mtcars$hp[mtcars$cyl==8], na.rm = TRUE))
abs(cyl_8-cyl_4)
 
