
# Testing Phase

"Click to return back to the [README.md](README.md)"

## Browser Testing

For each of my pages I will check them against the top 3 web browsers - Google chrome, Firefox and Microsoft Edge.
I initialy checked that all the elements were loading as they should on all 3 browsers.
Once I confirmed they were working as expected I then went into the devtools and changed the viewport width to check the layout and styles against different device sizes.

| Browser        | Screen Size | Image |
| :----:         |    :----:   | :----:|
| Chrome         | Desktop     | ![Class page Card section](documentation/testing/chrome_desktop.jpg) | 
| Firefox        | Desktop     | ![Class page Card section](documentation/testing/firefox_desktop.jpg)|
| Microsoft Edge | Desktop     | ![Class page Card section](documentation/testing/edge_desktop.jpg)   |
|                |             |                                                                      |
| Chrome         | Ipad        | ![Class page Card section](documentation/testing/chrome_ipad.jpg)    | 
| Firefox        | Ipad        | ![Class page Card section](documentation/testing/firefox_ipad.jpg)   |
| Microsoft Edge | Ipad        | ![Class page Card section](documentation/testing/edge_ipad.jpg)      |
|                |             |                                                                      | 
| Chrome         | Mobile      | ![Class page Card section](documentation/testing/chrome_iphone.jpg)  | 
| Firefox        | Mobile      | ![Class page Card section](documentation/testing/firefox_iphone.jpg) |
| Microsoft Edge | Mobile      | ![Class page Card section](documentation/testing/edge_iphone.jpg)    |


## Code Validation

### HTML testing

Once I had finished my website I ran each page throigh a HTML validator to ensure that the code was correct.

#### Home Page

![Home page HTML validator](documentation/testing/index.jpg)

#### Houses Page

![Houses page HTML validator](documentation/testing/houses.jpg)

#### Classes Page

![Classes page HTML validator](documentation/testing/classes.jpg)

#### Staff Page

![Staff page HTML validator](documentation/testing/staff.jpg)

### CSS Testing

I ran my CSS through a validator to ensure that it was correct. It passed the validation and came back with no errors.

![CSS validator](documentation/testing/css_validator.jpg)

## Acessability Testing

I ran each of my pages through an colour accessibility website found [Here](https://color.a11y.com/?wc3)
Because my pages have a dark background with coloured paragraphs I wanted to check that there were no contrast issues that could cause people to have dificulty reading the text.
All of my pages passed the validation checker.

#### Home Page

![Home page colour validator](documentation/testing/colour_validator.png)

#### Houses Page

![Houses page colour validator](documentation/testing/colour_validator.png)

#### Classes Page

![Classes page colour validator](documentation/testing/colour_validator.png)

#### Staff Page

![Staff page colour validator](documentation/testing/colour_validator.png)


## User stories testing
- As a user I want an informative website thats easy to read
![information](documentation/testing/about.jpg)
- As a user I want a website that teaches me more about the school and what it stands for
![about](documentation/testing/info.jpg)
- As a user I want a website that is easily navigated and intuitive
![Navigation](documentation/testing/navbar.png)
- As a user I want to see what the students might learn at the school
![Classes taught](documentation/testing/taught.jpg)

## Bugs

When I was testing my website I noticed that there was a problem with the bootstrap nav bar, when you went to smaller viewports it was collapsing but the hamburger menu wasnt working and when you clicked on it nothing happened. 

The first way I tried to fix it was to re put in the navbar template from bootstrap incase a change I had made had caused an issue, so I copied and pasted the code from bootstap and didnt change any of the classes or template text. I tried the different viewports again and the navbar hamburger menu still wanst working, this told me though that it wasnt an error with the HTML code.

Next I thought it might be an erorr with the CDN I had imported and this turned out to be correct, after trying a few recomended ones from Stack overflow and not having any luck I went back to the Bootstrap documentation and realised I had imported the wrong JavaScript file, I swapped out the one I already have with the new one and it fixed the issue.

