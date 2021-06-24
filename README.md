# Methods
## Method 1
If you mean in one document or code, use the <style></style> tag and put your css code inside the style tag. (Must put it in `<head></head>`)
For example: 
```<html>
<head>
<style>
.centertext{
font-family: Avenir, Optima;
text-align: center;
margin-left: auto;
margin-right: auto;
}
</style>
</head>
```
## Method 2
If, you want to separate the html part and the css part in different documents, make sure they are in the same folder. Then, use this in your html `<head>` tag:
`<link rel="stylesheet" href="style.css">`

Then edit the css file as usual as on codepen
*If you changed the css file name pls also change the "href" string from style.css to your css file name!*

