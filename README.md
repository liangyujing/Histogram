##直方图
##问题：make A graph of the data


par(mfrow = c(2,1))  # historiographer的排列方式，2是2排，1是1列
hist(liedetection, 
    breaks=10,   #每隔十个，#Define a sequence b of breakpoints 
    breaks=b, b <- c(3.5,5.5,7.5,9.5,11.5,13.5,15.5,17.5),
    col="red",border="orange")
