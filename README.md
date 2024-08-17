# Restaurant-Rating-Dashboard

## Case Study

Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant and their cuisines, and each consumer and their preferences.

## Problem Statement

1. What can you learn from the highest rated restaurants? Do consumer preferences have an effect on
ratings?

2. What are the consumer demographics? Does this indicate a bias in the data sample?

3. Are there any demand & supply gaps that you can exploit in the market?

4. If you were to invest in a restaurant, which characteristics would you be looking for?

## Dataset Description

Our data set consists of the following observations which include:

Consumers

- Consumer_ID - Unique identifier for each consumer
- City - City where the consumer lives
- State - State where the consumer lives
- Country - Country where the consumer lives
- Latitude - Latitude where the consumer lives
- Longitude - Longitude where the consumer lives
- Smoker - Whether the consumer smokes or not
- Drink_Level - Whether the consumer is an abstemious, casual, or social drinker
- Transportation_Method - Whether the consumer transports on foot, by public transport, or by car
- Marital_Status - The consumer's marital status (single or married)
- Children - Whether the consumer has dependent/independent children or kids
- Age - The consumer's age
- Occupation - The consumer's occupation (student, employed, or unemployed)
- Budget - The consumer's budget (low, medium, high)

Consumer_Preferences

- Consumer_ID - Unique identifier for each consumer
- Preferred_Cuisine - Types of food the consumer prefers

Ratings

- Consumer_ID - Unique identifier for each consumer
- Restaurant_ID - Unique identifier for each restaurant
- Overall_Rating - The overall rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)
- Food_Rating - The food's rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)
- Service_Rating - The service rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)

Restaurants

- Restaurant_ID - Unique identifier for each restaurant
- Name - The restaurant's name
- City - The restaurant's city
- State - The restaurant's state
- Country - The restaurant's country
- Zip_Code - The restaurant's zip code
- Latitude - The restaurant's latitude
- Longitude - The restaurant's longitude
- Alcohol_Service - Whether the restaurant serves no alcohol, wine & beer, or a full bar
- Smoking_Allowed - Whether any smoking is allowed, including in the bar or in smoking sections
- Price - The restaurant's price (low, medium, high)
- Franchise - Whether the restaurant is a franchise
- Area - Whether the restaurant is in an open or closed area
- Parking - Whether the restaurant offers any sort of parking (none, yes, public, valet)

Restaurant_Cuisines

- Restaurant_ID - Unique identifier for each restaurant
- Cuisine - Types of food the restaurant serves

## Data Modeling

Power BI automatically connected related tables resulting in a star schema model.
![]()

## Data Transformation

Data was cleaned and transformed with the Power Query Editor of Power BI 
- Removed all duplicates.
- Created the Age group, service rating, Food rating and overall rating category using conditional columns.
- Created two dashboards for this dataset, one for consumers behavior insights and the other for restaurant insights.

## DASHBOARD
![]()

## Consumer Insights

- Most of the population is from San Luis Potosí, while the second largest group is from Morelos, then Tamaulipas.
- In all three states, young adults under 30 years of age form the majority of the population. In two states, San Luis Potosí and Morelos, the second largest demographic consists of elderly, aged over 60 years.
- The vast majority of consumers from all four cities are non-smokers, with Jiutepec having a 100% non-smoking population. In Cuernavaca city, smokers make up 25% of the population.
- The majority of restaurants across all cities lack parking facilities, while some have parking available. In San Luis Potosí and Cuernavaca, two restaurants and one restaurant offer valet parking respectively.
- A relatively large percentage of the population consists of students, with the remaining portion comprising both employed and unemployed individuals.
- Mostly singles are casual drinkers, abstemious and social drinkers, while only 7 married consumers are social drinkers and 2 are abstemious.
- 61% of consumers use public transportation, 27% use cars, and 11% walk.
- San Luis Potosi, Cuernavaca, Ciudad Victoria and Jiutepec have high majority of non-smokers.
- Among the students, 67 have a medium budget, 33 have a low budget, and 4 have a high budget. Additionally, 15 employed individuals and 1 unemployed individual have a medium budget.

## Restaurant Insights

- Out of the 16 high-priced restaurants, 16 have parking available, with 3 offering valet parking, 1 providing public parking, and 5 lacking any parking options. Medium and low-priced restaurants do not offer valet parking; however, some provide public parking or have parking available, while others do not have parking available at all.
- Mexican cuisine is the most preferred by consumers, followed by American cuisine.
- Tortas Locas Hipocampo had the most orders, followed by Puesto de Tacos.

## Review Insights

- What are the top 5 restaurants by food rating?

The top 5 restaurants with high customer satisfaction are Tortas Locas Hipocampo and Puesto de Tacos. Cafeteria Y Restaurant El Pacífico has 9 consumers rating it highly satisfactory, while Gorditas Doa Gloria received 10. La Cantina Restaurante is rated highly satisfactory by 11 consumers, with the remaining votes split between satisfactory and unsatisfactory.

- What are the top 5 restaurants by service rating?

The top 5 restaurants with high customer satisfaction for service ratings are Tortas Locas Hipocampo. Puesto de Tacos has received 12 satisfied consumer ratings. Cafeteria Y Restaurant El Pacífico also has 12 consumers rating it as satisfactory, while Gorditas Doña Gloria has received the same number. La Cantina Restaurante is rated satisfactory by 7 consumers, with the remaining votes split between highly satisfactory and unsatisfactory.

- What are the top 5 restaurants by overall rating?

The top five restaurants with high customer satisfaction ratings are Tortas Locas Hipocampo, and Puesto de Tacos, which has received 15 highly satisfied consumer ratings. Cafeteria Y Restaurante El Pacífico follows closely with 12 consumers rating it as highly satisfactory, while La Cantina Restaurante boasts 14 highly satisfied ratings. Rounding out the list.
