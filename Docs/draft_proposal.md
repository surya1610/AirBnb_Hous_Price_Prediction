# Draft PROPOSAL

## What is your issue of interest (provide sufficient background information)?

- Airbnb began in 2008 when two designers who had space to share hosted three travelers looking for a place to stay. 
- Now, millions of hosts and travelers choose to create a free Airbnb account so they can list their space and book unique accommodations anywhere in the world. AirBnB provides a predictive pricing tool to hosts, but the tool has received complaints for not being accurate enough. 
- Some hosts even believe AirBnB may be artificially decreasing prices to keep new customers coming into the platform. Hence i decided to develop a predictive model for AirBNB prices.

## Why is this issue important to you and/or to others?

- Being such a gaint in its domain, Airbnb should maintain its customers with atmost satisfaction.
- Airbnb pricing is important to get right, particularly in big cities like London where there is lots of competition and even small differences in prices can make a big difference.
- It is also a difficult thing to do correctly — price too high and no one will book. Price too low and you’ll be missing out on a lot of potential income.

## What questions do you have in mind and would like to answer?

- What is the types of verification of the identity of the host ?
- Who is Top 25 most reviewed neighbourhoods ?
- Is host identity verified effect on price ?
- What is the most available set of dates of the year ?
- Which neighbourhood do you give the highest ratings to?

## Where do you get the data to analyze and help answer your questions?

- Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in New York City
- Listings, including full descriptions and average review score Reviews, including unique id for each reviewer and detailed comments Calendar, including listing id and the price and availability for that day

The data source is mentioned below:
- http://insideairbnb.com/explore/
- Size    : 35.91 MB
- Rows    : 1.02 M
- Columns : 26


## What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?

- The main motive of the project is to predict the listing prices. Hence "Price" is the unit for my analysis. There are about 20 to 24 units that i expect to analyze which might differ based on future findings.

## What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?

The variables that I plan to analyze are mentioned below:

Cloumn name                  Data Type

- id              :                    int64
- NAME      :                         object
- host id    :                         int64
- host_identity_verified    :         object
- host name              :            object
- neighbourhood group     :           object
- neighbourhood      :                object
- lat            :                   float64
- long          :                    float64
- country    :                        object
- country code      :                 object
- instant_bookable  :                 object
- cancellation_policy     :           object
- room type       :                   object
- Construction year       :          float64
- price          :                    object
- service fee          :              object
- minimum nights    :                float64
- number of reviews    :             float64
- last review      :                  object
- reviews per month       :          float64
- review rate number    :            float64
- calculated host listings count   : float64
- availability 365        :          float64
- house_rules       :                 object
- license           :                 object

## What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?
Some of the techniques that I plan to use are as follows:
- Data Preprocessing
- Handling missing values.
- Encoding the data

For Modeling purpose, based on the data using these models might be beneficial. which are :
- Linear Regression
- Decision tree
- Random forest

## How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?

- By splitting the data into train and test sets with the best suitable ratio, the above mentioned macine learning models can be developed and some metrics such as Accuracy, confusion matrix, ROC curve and means squared error (MSE) and Classification report will help in analysing and comparing the results of the trained models.

## What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?

- With the help of this project I intend to gain in depth knowledge about the AirBNB market analysis through which proper data analysis can be done. The best model with the highest performance will be choosen and might be used to predict the Listing's prices more accurately.







