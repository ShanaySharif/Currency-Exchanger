Currency Exchanger!! 

By: Shankaron Mohamed (Shanay)

## **Technologies Used**

-   RapidAPI integration
-   Asyncronous programming
-   JavaScript
-   CSS
-   HTML
-   VS Code
-   git
-   GitHub
-   Node Package Manager (npm)
-   JSON
-   Babel (v7.18.6)
-   EsLint v(8.18.0)
-   Jest (v24.9.0)
-   webpack (v5.0.0)
    -   webpack-cli (v5.0.0)
    -   webpack-dev-server (v4.0.0)
    -   clean-webpack-plugin (v3.0.0)
    -   dotenv-webpack (v2.0.0)
-   Loaders
    -   css-loader (v3.6.0)
    -   file-loader (v6.2.0)
    -   html-loader (v1.3.2)
    -   style-loader (v1.3.0)

## **Description**
In this project, I created a currency exchange application that allows users to enter in a amount in USD an returns the currency selected (South korean won, Japanese Yen, Euro, Kenyan Shiling and Dirham). The application determine the most recent exchange rate by making an API call.

## **Setup/Installation Requirements** 

###  (this serves as instructions for VS Code)

-   Clone this repository to your local machine.
-   Open VS Code.
-   Open the top level directory you just cloned.
-   In your terminal enter commands:
    -   `npm install`
    -   `npm run build`
-   Get API key
    -   Navigate to https://openweathermap.org/
    -   Sign up with the basic plan to get a free API key
    -   Navigate  to the 
    -   Copy your key under 
-   At the root directory, create a `.env` file and enter:
    -   
        make sure to remove the angle brackets as well as any whitespaces or extra punctuation.
-   Save and enter `npm run start` into terminal.
-

    That's it! Enjoy!

### Debugging

If the program does not run, try the following:

-   Check for error messages
    -   All errors will be routed to the DOM and read on the page.
    -   If 404 error:
        -   Check that the API_KEY variable in your .env file has no trailing whitespace or any punctuation. This includes no semicolon at the end of declaration.
        -   Check that your API key/access code from ---- is valid.
        -   Try generating the GET request in an API development/testing app or in your browser URL:<br>
       
-   Ensure dotenv is installed
    -   In your Terminal enter `npm install dotenv-webpack@2.0.0 --save-dev`

## **Known Bugs**


## **License**

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2023 Shanay Mohamed 