# Investigate-a-Dataset

### Introduction

In this project, TMDb movie data set was analysed. The data set consists of information about 10,000 movies from 1966 to 2015 which includes budget, vote_count, revenue earned, runtime etc.

### Methodology

This project was conducted in Python 3 in Jupyter Notebook. Libraries installed for carrying out the project were
numpy, pandas, matplotlib

#### Questions which had been answered from this data set were:
1. Which movies earned the highest and lowest profit?
2. Which movies had the highest and lowest budget?
3. Which movies had earned the maximum and minimum revenue?
4. Which movie had the highest and lowest runtime?
5. What is the average runtime of all the movies from 1966 to 2015?
6. What properties are associated with the revenue earned and popularity of a movie?
7. Which genres had the highest release?
8. Who were the most frequent actors?

#### Key Findings
It was found that the popularity of a movie has a strong correlation with revenue earned and profit has moderate correlation with budget. The Revenue earned has a strong correlation with popularity, budget and profit. It was also depicted from the analysis that amongst the genres, Drama had been released the maximum number of times and Robert De Niro was the mostly casted actor.
Although some important informations were retrieved from the data set, it has some limitations.

### Limitations
1. The budget and revenue supplied in the data set have no information about the currency. It was assumed that they are in US Dollar. However, the data might change if the currencies are different. 
2. The 0 values and NaN values were discarded from the data set. It had reduced the number of data present in the data set significantly, which might had effected the statistical analysis.
