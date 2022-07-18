# Testing

## HTML validator
### Home page
![Screenshot of HTML validation results for home page](readme-img/html-home.png)
- For error 1, I replaced the name attribute with an id attribute.
- For error 2, this was the only way I found in providing textual context to the background image as the image itself was within CSS. I removed this as the image is not providing any information to the user. 
- For error 3 and 4 I changed the buttons to links.

### Routes page
![Screenshot of HTML validation results for route page](readme-img/html-routes.png)
- For error 1, I replaced the name attribute with an id attribute.
- For error 2, this was the only way I found in providing textual context to the background image as the image itself was within CSS. I removed this as the image is not providing any information to the user. 
- For error 3-6, I removed the id attributes as they were not needed, as there was already a class attribute.

### Get in touch page
![Screenshot of HTML validation results for get in touch page](readme-img/html-touch.png)

- For error 1, I replaced the name attribute with an id attribute.
- For error 2, this was the only way I found in providing textual context to the background image as the image itself was within CSS. I removed this as the image is not providing any information to the user. 
- For error 3 and 4 I removed the br elements within the unordered list.

I corrected each error and re-checked the HTML through the validator, and it passed.

## CSS validator
I inputted code into the W3C validation service, initially this brought up two errors
- Text-shadow format was not correct, I decided the text shadow of the text over the hero image was not neccessary so removed that.
- Font weight value was incorrect, I had used 200px instead of 200.
- Once these errors were corrected no further errors were found.

![Screenshot of CSS validation results stating that no errors were found](readme-img/css-val.png)


## Performance testing
I utilised the [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) performance testing software.
- The results of the lighthouse testing can be seen below for each page. 
- On the first round of testing, the performace was quite low due to image size and bootstrap stylesheets slowing down the first paint of the page.
- I reduced the size of the images and used [Tinypng](https://tinypng.com/) to compress the images. As you can see below, the doing this increased the performance significantly. 
- The accessibility is good although not 100%, this wil be looked into in more detail in the next section.
- The search engine optimisation is good but slightly low due to the link to bring the user back up to the top of the page being unrawlable. 
### Home page
![Screenshot of Lighthouse testing for home page](readme-img/home1.png)
![Screenshot of Lighthouse testing for home page](readme-img/2home.png)


### Routes page
![Screenshot of Lighthouse testing for routes page](readme-img/routes1.png)
![Screenshot of Lighthouse testing for routes page](readme-img/2routes.png)


### Get in touch page
![Screenshot of Lighthouse testing for get in touch page](readme-img/touch1.png)
![Screenshot of Lighthouse testing for get in touch page](readme-img/2touch.png)


## Accessability testing
I utilised [Wave](https://wave.webaim.org/) which is a web accessibility evaluation tool.

- One error was detected, that an empty button was present. This was the collapsable hamburger navbar button, which was adapted from Bootstrap documentation. It works well so I decided to leave it as it is, however will consider that in future projects.
- The contrast ratio was good throughout and passed the tests for normal and large text, apart from the testimonial cards, so I made the background colour darker to increase readability, it then passed the tests.
- The social media links within the footer did not all have titles, this error was corrected.

## Responsiveness
Chrome tools throughout
Am i responsive?


## Manual testing
- different device sizes
- links
- browser compatibility

## Testing User Stories

## Known bugs
