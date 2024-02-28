# Provide_insights_to_the_marketing_team
![image](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/f6b3abef-a714-4702-b7f0-904051ceb031)

### The task here is to provide insights to the marketing team. In other words, to provide the following recommendations:
1.) What immediate improvements can we bring to the product?

2.) What should be the ideal price of our product?

3.) What kind of marketing campaigns, offers, and discounts we can run?

4.) Who should be our target audience, and why?
#
Before diving into the task, let us know about the company.

## CodeX
Codex is a German beverage company that is aiming to make its mark in the Indian market. 

A few months ago, they launched their energy drink at 10 cities in India

![Screenshot 2024-02-25 221247](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/39dc5d9c-f53f-4ca7-b7c3-9dc8981e2ee6)

Their Marketing team is responsible for increasing brand awareness, market share, and product development.

They conducted a survey in those 10 cities and received results from 10k respondents.

### I have shared the survey questions here: 
https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/blob/main/Survey_Questions_and_Response_Options.pdf

### I have uploded the response data here: 

https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/blob/main/dim_repondents.csv

https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/blob/main/fact_survey_responses.csv

If you are unable to go throught the data, alternative link is provided: 
https://www.kaggle.com/datasets/suhanias/marketing-dataset
#
## Analysis
Before analysing the data, we will have to make sure that the data is adequate and the cleaning (i.e., data cleaning) is to be done(if required).
I have done the above analysis part in __Python (Jupyter Notebook)__.

https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/blob/main/Survey.ipynb

Thus, data cleaning is not required as the data has no empty cells.

Now let us analyse the data provided and answer the following questions. The questions are mentioned in the below pdf.

https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/blob/main/Primary_Secondary_Insights.pdf
#
### 1.) Demographic Insights
#### a. Who prefers energy drink more? (male/female/non-binary?)
![Screenshot 2024-02-28 204142](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/e8b481f6-6a91-42f6-9f86-640ddba747d8)
##### From the above graph, it is clear that male prefer more energy drink than female and non-binary.
##### It is also to be noted that, in population male is dominated over the rest.
![Screenshot 2024-02-28 204435](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/90fc66a0-cd7c-4089-90b8-6d90798e2007)

#### b. Which age group prefers energy drinks more?
![Screenshot 2024-02-28 204759](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/6b6c79da-4dd7-46d2-8192-316b53a2fe22)
##### 19-30 age group people prefer more energy drinks.

#### c. Which type of marketing reaches the most Youth (15-30)?
![Screenshot 2024-02-28 205335](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/77dec74a-0144-4d91-b223-45ca22095f29)
##### You can see that, Online adds reaches the most youth.
#
### 2.) Consumer Preferences:
#### a. What are the preferred ingredients of energy drinks among respondents?
![Screenshot 2024-02-28 205829](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/da676988-dbd8-474d-a2f2-3bed669b6aeb)
##### Caffeine is the prefered ingredient of energy drinks among the respondents.

#### b. What packaging preferences do respondents have for energy drinks?
![Screenshot 2024-02-28 210510](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/05f12982-ff04-4165-95c7-55f9d4073352)
##### Here, I have considered the complete population. And out of it, most of the people prefer 'Compact and portable cans' and 'Innovative bottle design' over the rest.
##### Just to know, what would be the result when gender is considered, I have inclided gender and the resulting graph is as shown below.
![Screenshot 2024-02-28 211034](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/77691594-0097-4d04-9e17-f437ed9ca5a7)
#
### 3.) Competition Analysis:
#### a. Who are the current market leaders? 
#### b. What are the primary reasons consumers prefer those brands over ours?
![Screenshot 2024-02-28 211323](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/0f05e8a3-8cdd-43bb-b832-5a9130c542b8)

![Screenshot 2024-02-28 211757](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/16ae983e-f878-4864-83d8-497cd90e4ee4)

##### Cola-Coka is the market leader as it ranks 1st with all the reasons mentioned. Specifically, people prefer Cola-Coka over the rest due to its taste, availability, effectiveness and brand reputation. And some prefer this for other reasons. We can also notice that, our brand is placed at 6th rank when coming to taste and effectiveness. Availability also needs to be increased inorder to increase the reputation. 
#
### 4.)  Marketing Channels and Brand Awareness:
#### a. Which marketing channel can be used to reach more customers?
#### b. How effective are different marketing strategies and channels in reaching our customers?
![Screenshot 2024-02-28 213022](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/5b9aaf9b-1f25-45c5-82b6-312154f1d957)
##### We know that, in this generation people will be involved in their cell phones. If not, they would prefer TV. Very few people prefer print media. This is the knowledge that I have in general. 
##### From 1.c we got to know that online adds can be used to reach most of the consumers. When the complete population is considered with respect to age, online adds and TV commercials can be used to reach more customers.
#
### 5.) Brand Penetration:
#### a. What do people think about our brand? (overall rating)?
![Screenshot 2024-02-28 214929](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/587ece45-a4e8-40eb-94fb-b1c84396237b)
##### We can see that, most of the people have rated 3. The reason would be either taste and flavor or the availability. So would be very important for us to introduce new flavors and improve in taste as well. And make sure that our product is available everywhere. 

#### b. Which cities do we need to focus more on?
![Screenshot 2024-02-28 220859](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/0bf2193b-1de0-471e-8113-9c1946a69f58)
##### It would be CT113 (i.e, Bangalore), as they are concerned about their health and the product is not available locally. This clearly means that they are not aware of the product. So we will have to do marketing in Bengaluru and make sure that the product is available locally and are aware of the product in a better way. 
#
### 6.) Purchase Behavior:
#### a. Where do respondents prefer to purchase energy drinks?
![Screenshot 2024-02-28 222127](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/2a812b78-64fd-4cbe-884f-1998ac879472)
##### Most of the people would prefer to purchase our product at super market.

#### b. What are the typical consumption situations for energy drinks among respondents?
![Screenshot 2024-02-28 222441](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/fd494e33-b6a8-474b-b3b0-736193e51290)
##### Most of the people would prefer energy drink in order to increase energy and focus, and to combat fatigue.

#### c. What factors influence respondents' purchase decisions, such as price range and limited edition packaging?
##### We have discussed earlier about the availability of the product and packages customer prefer. Now, let us know about the price range people prefer in percentage.
![Screenshot 2024-02-28 225234](https://github.com/SuhaniAS/Provide_insights_to_the_marketing_team/assets/137792301/7b707ff2-aa5a-407d-bab2-48f5b303a692)
##### 42.88% of the people prefer 50-99 Rs, whereas 31.42% of the people would prefer 100-150 Rs. So it would be better to fix the price range from between 75-125.
#
### 7.) Product Development
#### Which area of business should we focus more on our product development? (Branding/taste/availability)
##### From the above analysis, we got to know that, to increase the brand reputation, it would be very important to make sure that there is an imrovement in taste and the product is available locally. In addition, marketing is done well.
#
#
## Recommendation
##### Since, youngsters prefer the energy drink, I would ask to consider them as the target audience. When coming to discount, during the starting days at some place, its better to provide some offer inspight of discount. When coming to price, Rs 99 would be better with offer. Some more recommendations I have provided along the process of analysis.
#
## Thank you for going through my project.
