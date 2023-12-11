# Chrisma-Console-Finances

## About the Project

This project has been completed to write and execute JavaScript code for the datatset provided.

The starter code was edited and JavaScript code has been written on the index.js file.

The dataset consists of a nested array of data, including a number and a date in each nested array. I first went about visually analysing the dataset to observe the common pattern of data entered in the dataset and then read on a few documents on how financial data is usually presented. A general knowledge on Microsoft Excel came in handy to get a basic understanding of the dataset.

The total number of months was calculated by using the length() function.

Accessing the second data inside the nested array was new and I read up about it and found that it can be accessed with square brackets similar to indexing of the array. The total was then added up using a 'for loop'.

I created another 'for loop' to calculate the average change and declared variables for the greatest increase/decrease and their corresponding dates. The loop was set up to iterate through all the values in the profits/losses and substract from the previous one. The average was then compared to the variables set for greatest increase and greatest decrease and when true, the value and date were logged in the console.

The average value was rounded up using the Math.floor() function. The local edits were pushed to github through git bash using git commands. The page was deployed through gitHub pages and a screenshot was taken. 


## Built with

This repository has been built using 

-HTML
-JavaScript
-Git 
-Github 


## Resources:

-https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
-https://www.freecodecamp.org/news/how-to-add-numbers-in-javascript-arrays/
-https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor
-https://www.freshbooks.com/hub/reports/profit-and-loss-report


### Installation

This webpage can be rendered by visiting the url : https://chrisma89.github.io/Console-Finances/
The code can be viewed at github: https://github.com/chrisma89/Console-Finances

### Usage

The JavaScript code written could be used to analyse similar datasets and the for loops could be used as inspiration for analysing interesting trends in other dataset. The current code for the dataset provided will give a good understanding of its profits/losses over the given period. 

The screenshot of the webpage is below : ![webpagescreenshot](./Screenshot%20of%20Console.png)

### Credits

The starter code including the dataset was provided by the bootcampspot through edx and skills for life. 
The pseudocode was provided to the classs by Laura Cole, our instructor. Many Thanks Laura. 
The readme file was written with some inspiration from https://github.com/othneildrew/Best-README-Template/blob/master/README.md



### Licence
The standard MIT Licence is in use for this repository.








