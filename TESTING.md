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