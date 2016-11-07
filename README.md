# Global-Income-Analysis
Portfolio building 
fileURL <- "https://d396qusza40orc.cloudfront.net/getdata%2Fdata%2Fss06hid.csv"
destFile <- tempfile()
download.file(fileURL, destFile, method = "curl")

data <- read.csv(destFile, header = T)
