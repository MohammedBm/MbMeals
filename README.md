# MbMeals
This project is based of Udacity React Nanodegree program.

In this application you can use MbMeals to plan your meals and the recipes for them as well. Using Edamam recipe search to get the meal and the recipes.

### To use the application
currently there is no life version of this application so you will need to install locally.

First you will need to clone the application into your machine
```shell
 git clone https://github.com/MohammedBm/MbMeals.git
```
To install the packages needed for this project you can use
```shell
npm install #or you can use `yarn install` if you use yarn
```
After that you will need to sing-up on Edamam to get your api key
<a href='https://developer.edamam.com/edamam-recipe-api'>Edmam</a>, After you finish signing up for Edmam you can create a file called `.env` by using this command

```shell
touch .env
```
Now open the .env file you created and add this to it
```text
REACT_APP_API_ID='api_id'
REACT_APP_APP_KEY='api_key	'
```
You will need to add your api id and api key inside quotation marks.
Finally you can run this command to start the application
```shell
npm start #or `yarn start` if you use yarn
```

Thank you for checking out my application!!
