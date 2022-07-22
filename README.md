# UFOs


## Overview of the analysis

We build a table using data stored in a JavaScript array.And then we add filters of that table which lets users refine their research on more than one level. For location based data for example, a user can opt to view results located in certain countries, or even cities. Our table will be inserted into, and visually displayed by an HTML page. We use basic HTML, Bootstrap, anf CSS to build and style the entire page. We also include an attention grabbing header, article summary, and brief article.

## Results

When you visit the webpage file:///Users/daniellamuhire/Documents/Class%20Folder/UFOs/index.html, you will land on the following:

<img width="1440" alt="Screen Shot 2022-07-21 at 7 55 56 PM" src="https://user-images.githubusercontent.com/77806210/180346115-e9dc0af0-f121-4098-9500-0f079ec443d7.png">

To the left side of the webpage, we can see "Filter Search" section:

<img width="464" alt="Screen Shot 2022-07-21 at 8 02 24 PM" src="https://user-images.githubusercontent.com/77806210/180346890-3610d50c-c63f-416d-aea9-19c809357d7a.png">


From here, we can refine our research on more than one level. 
Let's refine our research to display the results from one state, ca for example

<img width="1440" alt="Screen Shot 2022-07-21 at 8 11 02 PM" src="https://user-images.githubusercontent.com/77806210/180347842-9e0b395a-0e94-4457-9186-6de0b169124c.png">

We can add more filters to our research. Let's add shape to our research. The table will only display results with triangle as shape and ca as state

<img width="1440" alt="Screen Shot 2022-07-21 at 8 11 21 PM" src="https://user-images.githubusercontent.com/77806210/180348069-9fd4440c-a5e4-4bd8-b1d6-a16b304a59da.png">

If we filter an element that is not contain in our data, there is nothing displayed in our table

<img width="1440" alt="Screen Shot 2022-07-21 at 8 17 10 PM" src="https://user-images.githubusercontent.com/77806210/180348456-489c68d2-c1e3-4713-b453-267bf5d79d59.png">

## Summary 

### Drawbacks

The search field is case-sensitive. If we don't enter the same exact element contained in our data, the table will not be updated. For example, if  we enter a city by tping it with capital letters, the table won't be updated.

###Recommendations
By adding the following we can improve the user's experience:

- Add a search button. In fact, when the user enters information to filter the table, there is nothing that tells the user to press Enter. It will improve user'experience to add a search button. 
- Instead of displaying nothing when user tries to filter on information that is not in the data, display a message that tells users that the information entered wasn't found. 
