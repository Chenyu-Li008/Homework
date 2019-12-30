# R语言复刻
## 图一
### 原图
![](https://github.com/Chenyu-Li008/Homework/blob/master/week9/1.1.jpg)
### R复刻版
![](https://github.com/Chenyu-Li008/Homework/blob/master/week9/1.png)
![](https://github.com/Chenyu-Li008/Homework/blob/master/week9/2.png)
### 代码

> library(ggplot2)

x <- c(1.0,19.2)

label <- c("female","male")  

> pie(x, labels = percent,main="不同性别未成年人犯罪率-中国",radius =0.8,col =c("gold","blue4"),clockwise = TRUE)  #制图

> percent<-round(100*x/sum(x),2)  #计算百分比    

> percent <-paste(percent, "%", sep = "")  #将不同数据类型放在一起 

> legend("topright",label, cex=0.8, fill=c("gold","blue4"))  #加图例

（这里是第二张图，代码是一样的）  
> x <- c(366.6,819.9)  
> label <- c("female","male")  
> pie(x, labels = percent,main="不同性别未成年人犯罪率-美国",radius =0.8,col =c("gold","blue4"),clockwise = TRUE)  
> percent<-round(100*x/sum(x),2)   
> percent <-paste(percent, "%", sep = "")   
> legend("topright",label, cex=0.8, fill=c("gold","blue4")  


## 图二
### 原图：

### R复刻版

### 代码
>View(crime)
>options(scipen=200)
>ggplot(crime,aes(year,number,fill=type))+
geom_bar(stat="identity",position="stack")+
theme_economist(base_size=14)+
scale_fill_economist()+
guides(fill=guide_legend(title=NULL))+
ggtitle("我国未成年犯罪数量及占比变化")+
theme(axis.title = element_blank())
