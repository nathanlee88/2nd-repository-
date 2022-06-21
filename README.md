# 2nd-repository-
repository 2

test test 

print("Hello World!")

hi 
🐼

#installing packages
# install.packages("tidymodels")
# install.packages("readxl")
# install.packages("repr")
# install.packages("tidyverse")
# install.packages("psych")
# install.packages("digest")
# install.packages("kknn")

#libraries
library(psych)
library(tidyverse)
library(repr)
library(tidymodels)
library(readxl)
library(digest)
library(kknn)

url <- "https://github.com/nathanlee88/2nd-repository-/blob/main/data/uk_data.xls?raw=true"
file <- download.file(url, "data/uk_data.xls")
uk_train <- read_excel("data/uk_data.xls", sheet = 2) %>%
  select(STG:UNS)
head(uk_train)  
 
