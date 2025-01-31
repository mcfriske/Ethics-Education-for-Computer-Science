# If/Else Advertisement Assignment

## Note for Instructors
Within there assignment there are various examples or specific locations used. **Example text and locations** may be changed to create assignments that are more closely related to the space in which the assignment is being assigned.

## Overview
For this homework, you will be creating functions that will output personalized ads **using if/elif/else.** Each problem will present a short scenario and task describing what type of personalized ad should be served. There will be a few guidelines for the type of ad you want to print to the screen, but **you have freedom on the actual text of the advertisment.** Please read the instructions carefully and come to office hours if you have any questions. 

*You will be graded for effort as well as correctness (i.e. one-word ad text will not receive full credit).* Additionally, for problems 1, 2, and 3 you are given some specific decisions to make&mdash;you may include additional decisions underneath those using information given if you would like. In Problem 4, you make all the decisions.

## Problems
### Problem 1, suggested points: 24 (30 without reflection)
*Scenario*: You work at an advertising company and your client paid for ads at the lowest tier of personalization; therefore, they only have a small amount of data access—whether a user self-reported that they atleast own a dog.

*Task*: Given a boolean `owns_dog` that contains whether the user owns a dog, write a function that:
- if they own a dog, print text advertising dog food. Your text must start with `"Dog Food Ad: "`.
- if they **do not** own a dog, print text advertising anything else. Your text must start with `"Ad: "`.

For example, given `owns_dog = True`, your function might print:
```
Dog Food Ad: Meat’s the need of dogs like yours! The ALL-MEAT dinner for dogs, WOOF.
```
And if `owns_dog = False`, your function might print:
```
Ad: Dirty mouth? Clean it up with new Orbit Raspberry Mint. For a good clean feeling, no matter what!
```

### Problem 2, suggested points: 24 (30 without reflection)
*Scenario*: By combining data from a marketing platform with the results from personality tests that users have completed, we know that people with at least 500 Facebook friends are likely to be extroverts, and people with less than 500 friends are likely to be introverts. Based on analysis of user-uploaded photos using computer-vision algorithms, we also know that people who are extroverts are more likely to have many photos of dogs, and introverts are more likely to have many photos of cats. Market research has shown that dog people are highly likely to be positively influenced by advertisements for any product that includes dogs, and similar for cat people and cats.
 
*Task*: Given an integer `number_of_friends`, which represents how many Facebook friends a user has, write a function that does the following:
- if the user has 500 or more friends, print advertisement text that includes a dog. Your text must start with `"Ad with Dog:  "`.
- if the user has less than 500 friends, print advertisement text that includes a cat. Your text must start with `"Ad with Cat:  "`.
 
For example, given `number_of_friends = 358`, your function might print:
```
Ad with Cat:  *cat using a smartphone on Catdr, Tindr for cats* Tired of swiping? Join eHarmony today and find your purrrfect companion.
```

### Problem 3, suggested points: 16 (20 without reflection)
*Scenario*: Based on ad clicks and third-party data shared through purchases on a “marketplace” platform, we have data about likely income averages for every zipcode in the country. We also know based on self-reported age how incomes vary based on life stage (e.g., college students have less disposable income no matter where they live). Your clients prefer to strategically advertise to people who are more likely to be able to afford their product.
 
*Task*: Given a user’s `zipcode` and `age` as integers, write a function that:
- if the zipcode is in Boulder (i.e. between and including 80301 and 80310) and age is at least 25, print text advertising an expensive product. Your text must start with `"Expensive Product Ad:  "`.
- if the zipcode is in Boulder and age is less than 25, print text advertising an inexpensive product. Your text must start with `"Cheap Product Ad:  "`.
- Otherwise, print advertisement text encouraging the user to visit Boulder. Your text must start with `"Tourism Ad:  "`.

For example, given `zipcode = 53566` and `age = 25`, your function might print:
```
Tourism Ad:  Come visit Boulder, where everything is bolder.
```

### Product 4, suggested points: 16 (20 without reflection)
*Scenario*: Not only do you work for an advertising agency, you’ve got a side-hustle working for a social media platform. You have access to each user’s personal information based on their profile. In order to help advertisers get the most money out of their advertising packages, you tailor the ads a user will see based on personal details each user provides. 
 
*Task*: Write a function that uses personal details from a social media profile to display a custom advertisement. **You are free to use all, some, or none of the information given** to print text advertising anything that you want. The only guideline is that your text must start with `"Ad: "`. Descriptions of the variables are below.

- `name`: a string containing a user’s name. (e.g. Avatar Aang)
- `gender`: a string containing a user’s gender (e.g. demiboy)
- `age`: an integer containing a user’s age (e.g. 112)
- `hometown`: a string containing a user’s hometown (e.g. Southern Air Temple)
- `relationship`: a string containing a user’s relationship status (e.g. Crushing on Someone)
- `birthday`: a string containing a user’s birthday (e.g. August 21 12BG)
- `number_of_friends`: an integer containing the number of friends a user has on social media (e.g. 243)
- `political_affiliation`: a string containing a user’s political affiliation (e.g. Independent)
 
Using the examples above (i.e. Avatar Aang, demiboy, 112, etc.), your function might print:
```
Ad: Looking for cabbages? Cabbage Corp - Cabbages so good, they’re smashing.
```
### Reflection (highly recommended), suggested points: 20
Thinking back on the problems in this assignment, discuss ethical implications for these both the arbitrary boundaries decided by the assignment maker (i.e. base decisions in problems 1, 2, and 3) as well as decisions you made (i.e. problem 4 or any additional decisions you added to the problems 1, 2, or 3). Why did you make those decisions? What experiences or knowledge led to that choose? This assignment is a relatively small scale, but how does it relate to larger scale decisions made in development and the tech industry? 

Your response should be 250-500 words.
