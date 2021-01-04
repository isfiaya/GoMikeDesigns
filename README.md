# GoMikeDesigns
*Optimize an Existing Website*

[hosted online on GitHub Pages](https://isfiaya.github.io/GoMikeDesigns/)

## Screenshot to the score of the report *before my optimization*


![report](/img/before-my-optimization.JPG)



## Screenshot to the score of the report *after my optimization*
![report](/img/after-my-optimization.JPG)


## What I did! 
### Keywords
- Remove the Keywords meta tag Google does not use any more
- Content and keywords are hidden in a div tags,should be removed 
### Text alternatives
- The website uses three separate images that present content.This content will not be accessible to people who use screen readers and other such technologies, these images must be removed and replaced with text.
- The text alternatives just contain keywords.The alternative text must describe the appearance and function of the image,therefore need to be replaced.
### CSS files
- The W3C HTML and CSS validator should not reveal any errors. 
- Remove unused CSS.
- The CSS files have not been minified,doing so will reduce the files sizes therefore improving load speeds.
### JavaScript files
- The JavaScript files have not been minified,doing so will reduce the files sizes therefore improving load speeds.
- Remove unused JavaScript.
- adding the JavaScript to the end,the main content will load first appearing to improve performance.
- Update JavaScript library (Jquery & Bootstrap) to prevent security vulnerabilities
### Colour
- Content displayed in some areas does not have sufficient contrast ratio.Colour must be changed
### Semantic Tags
- Codes is sectioned off using mostly div tags, semantic tags should be used instead.
### Meta Data
- The title and the description tags do not have any content,this content should be added.
### Responsiveness
- Parts of the website including the navigation of Page2 is not responsive. Rectifying this issue will make navigating the website easier 
### Images
- The sizes of the images are too large and they are compressed .This can be rectified without reducing the visual quality of the images too much.
- Make the images lazy loading .This can improve performance by reducing the amount of resources that need to be loaded and parsed on initial page load.
- Image formats like WebP often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. Convert image to WebP
### Fonts
- Ensure text remain during web font load
### Best Practice
- Vertically align the "+" symbol on the image grid , light-box caption, light-box close btn and the light-box next and prev btn 
- Add H2 to page Contact ( Message Us , Contact Us )
- Fix opacity scroll to Top and added to Home page 
### Links
- Remove the fake links that exist in the footer 
- Fix link ( Are you ready Contact me )
- Add links to the social media icons 
### Performance
- Eliminate render-blocking resources reduce the impact of these render-blocking URLs by inlining critical resources, deferring non-critical resources.
### Button toggle
- switch the three separate icons toggle by one icon this can reduce the length of code and performance of the website.