# Code Institute Milestone Project 1
## Testing Phase
### Manual Testing
#### HTML testing
Once I had finished my website I ran each page throigh a HTML validator to ensure that the code was correct.

Home Page
- For the hompage I had an issue where I had put an anchor tag inside a button to link to another page, the validator told me this was invalid code so to fix it I removed the button element which surounded the anchor tag and insted styled the anchor tag to look like a button.
- I had a missing closing div in one of my sections so I added the closing tag to remove this error.
- My page was missing hte !DOCTYPE tag at the top of my page so I also added this.

Hogwarts Staff Page
- I had used an ID on two paragraph elements on the page so to fix this issue I changed the ID for a class of the same name so it can be used in multiple places. 

#### CSS Testing
I ran my CSS through a validator to ensure that it was correct. It passed the validation and came back with no errors.

#### Acessability Testing
I ran each of my pages through an colour accessibility website found [Here](https://color.a11y.com/?wc3)
Because my pages have a dark background with coloured paragraphs I wanted to check that there were no contrast issues that could cause people to have dificulty reading the text.
All of my pages passed the validation checker.

#### Browser Testing
For each of my pages I will check them against the top 3 web browsers - Google chrome, Firefox and Microsoft Edge.
I initialy checked that all the elements were loading as they should on all 3 browsers.
Once I confirmed they were working as expected I then went into the devtools and changed the viewport width to check the layout and styles against different device sizes.


## Bugs
When I was testing my website I noticed that there was a problem with the bootstrap nav bar, when you went to smaller viewports it was collapsing but the hamburger menu wasnt working and when you clicked on it nothing happened. 

The first way I tried to fix it was to re put in the navbar template from bootstrap incase a change I had made had caused an issue, so I copied and pasted the code from bootstap and didnt change any of the classes or template text. I tried the different viewports again and the navbar hamburger menu still wanst working, this told me though that it wasnt an error with the HTML code.

Next I thought it might be an erorr with the CDN I had imported and this turned out to be correct, after trying a few recomended ones from Stack overflow and not having any luck I went back to the Bootstrap documentation and realised I had imported the wrong JavaScript file, I swapped out the one I already have with the new one and it fixed the issue.
