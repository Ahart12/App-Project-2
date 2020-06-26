# Project Overview

## Project Links

- [add your github repo link](https://github.com/Ahart12/App-Project-2[])
- [add your deployment link]()

## Project Description

A alcohol cocktail app that gives user different cocktail ideas and details to make.

## API


Api Link:
[Link](https://www.thecocktaildb.com/api/json/v1/1/filter.php?a=Alcoholic)
```
{
            "strDrink": "A Furlong Too Late",
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/ssxvww1472669166.jpg",
            "idDrink": "17831"
        },
        {
            "strDrink": "A Gilligan's Island",
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/wysqut1461867176.jpg",
            "idDrink": "16943"
        },
        {
            "strDrink": "A midsummernight dream",
            "strDrinkThumb": "https://www.thecocktaildb.com/images/media/drink/ysqvqp1461867292.jpg",
            "idDrink": "15675"
        },
     
```


## Wireframes



- [add link to your wireframes](https://res.cloudinary.com/dz449ufvx/image/upload/v1593160330/react%20wireframe/IMG_0992_llxdpq.jpg)
- [add link to your react architecture](https://res.cloudinary.com/dz449ufvx/image/upload/v1593160360/react%20wireframe/IMG_0994_qqtb7h.jpg)


### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP EXAMPLE
- Use external api
- Set and style Title and Disclaimer Pages 
- Nav bar that routes to corresponding pages
- Drinks List that routes user to cocktail details
- Render data on page 
- About page

#### PostMVP EXAMPLE

- Add Contact form
- Add Favorites component

## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| Title | Single page that gives the title and image. | 
| Disclaimer | Single page that gives drink responsively message | 
| Home| Main page that contains switch routes, title, and random cocktail images | 
| About | Renders about page details|
| Drinks | Renders cocktail drink title list |
| Drink Details | Renders information about selected cocktail |


Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe. Also, put a gif at the top of your Readme before you pitch, and you'll get a panda prize.

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Create title page | H | 3hrs| 3.5hrs | -- |
| Create disclaimer page | H | 3hrs| -- | -- |
| Set home page | H | 2hrs | -- | -- |
| Make nav bar | H | 1hr | -- | -- |
| Load Images | H | 2hrs | -- | -- |
| Create grid for images | H | 1.5 | -- | -- |
| Make Api Call | H | 2hr | -- | -- |
| Setup Routes | H | 2hrs | -- | -- |
| Load Drinks List and About pages | H | 3hrs | -- | -- |
| Add Content for about page | H | 1.5 | -- | -- |
| Style css for Drinks page and drink details | H | 2hrs | -- | -- |
| Refine Design of all css | H | 3hrs | -- | -- |
| Total | H | 26hrs| 0hrs | 0hrs |

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project such as Axios, ReactStrap, D3, etc. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
