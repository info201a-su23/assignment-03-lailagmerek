# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?

1,000,000

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

250,000

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

California has the highest, South Dakota the lowest.
## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

I was suprised because my guess was 10x less than the actual number of COVID cases in the US.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

King county has the highest number of cases. I am not suprised by this because King county is the largest county in Washington.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

The number of counties in the variable lowest_deaths_in_each_state is greater than 50 because the dataset includes multiple observations for the same state on different dates.

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

I think the number is not as high as I was expecting. I think that even though there are inconsitiencies, people should still use this data they just need to be cautious and realize that there are some errors.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

I was intrigued by this question because I believe that analyzing the most recent data is crucial for predicting future COVID-19 case trends. Through the code analysis, I discovered that over the last 30 days, an average of approximately 54,000 new cases per day were reported in the United States. This information provides valuable insights into the current state of the pandemic and can aid in making informed decisions to manage and respond to the ongoing situation.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? 
Answer in at least 1-3 sentences

The sheer magnitude of COVID cases in the US was truly shocking. For my future data wrangling projects, I have learned the importance of meticulously managing data formats to prevent potential issues and ensure accurate analysis. Proper data handling is crucial for gaining meaningful insights and making informed decisions.