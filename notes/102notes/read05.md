# Notes

## Summary

CSS is for stylizing how HTML elements look within the browser viewport. CSS doesn't change the content, but just changes it's visual appearance to make it more presentable. This is usefull for things like accessibility, which remains unchanged with the addition of CSS to the webpage. Having them separate is important in that regard, and for Search Engine Optomization.

## Q&A

1. The purpose of CSS is to allow the website creator to stylize the webpage for their intended purpose. To make it look different or distinct from another webpage. Webpages are all different and have different needs, so having the tool (CSS) to change the format and look of a page is vitally important.

2. CSS can be inserted into a project via an External link, the HTML will contain a filepath to the .css file and then the browser will interpret them together.

-CSS can be internal to the .html file but separated from the HTML body itself to keep it easier to read, no external filepath link is neccesary. Though this can make the .html file massive and unwieldly is the project is of any significant size.

-CSS can be in-line within the .html file. As you write your html elements in the body, divs and p can have CSS in the same written line defining its color or presentation. This may be appropriate for small single page websites but can quickly become a nightmare to edit or make changes to if the project scales larger.

3. to make a p element red you can use 

>`p {
>    color: red;
>}`
