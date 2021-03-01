---
layout: default
---

# Intro to Web Development

## What is HTML?

HTML stands for HyperText Markup Language, and is the language used to make webpages.

## CodePen

You'll be using a website called CodePen to write HTML. It should look like this

<p class="codepen" data-height="512" data-theme-id="dark" data-default-tab="html,result" data-user="southbendcodeschool" data-slug-hash="WNoXdNx" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Web Dev Intro">
  <span>See the Pen <a href="https://codepen.io/southbendcodeschool/pen/WNoXdNx">
  Web Dev Intro</a> by alex (<a href="https://codepen.io/southbendcodeschool">@southbendcodeschool</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<br>
The code that you can see on the left in CodePen is HTML.

On the right of CodePen you can see the webpage that the HTML code made.

HTML uses tags to build websites.

The example tag: `<p>` stands for paragraph. Can you spot more tags in the code above?

* `<h1> </h1>`
* `<h2> </h2>`
* `<iframe> </iframe>`
* `<img>`
* `<html> </html>`
* `<head> </head>`
* `<body> </body>`

You may have noticed that HTML tags normally come in pairs like `<p>` and `</p>`

The first tag in a pair is the start tag, the second tag is the end tag.

## Start Coding

<input type="checkbox" class="checkbox"> Open the [starter project](https://codepen.io/southbendcodeschool/pen/WNoXdNx)! (right click to open in a new tab)

Note that if you refresh the Codepen site, any changes you made will be lost.

### HTML

Header tags (ex. h1, h2, h3, etc.) change text.

Header tags look like this:

`<h1>`
`<h2>`

<input type="checkbox" class="checkbox"> Find the `<h1>` tag that says `<h1>INSERT WEBSITE'S TITLE HERE</h1>` in CodePen.

<img style="height: auto; max-width: 75%;" src="{{ site.baseurl }}/assets/img/header.png">

<input type="checkbox" class="checkbox"> Replace ONLY the words "INSERT WEBSITE'S TITLE HERE" with the title of your webpage.
For example:
`<h1> Golden Retrievers </h1>`

<input type="checkbox" class="checkbox"> Keep going to change the other headers (`<h1>` and `<h2>`) and paragraphs (`<p>`)in the website.

<input type="checkbox" class="checkbox"> The paragraph tags currently are filled with a text filler called "lorem ipsum". Replace this with your own text about the topic of your webpage!

<input type="checkbox" class="checkbox"> Scroll through your webpage and double check that you successfully updated all of the text!

### Images

Let's swap out the cat images for some other images.

<input type="checkbox" class="checkbox"> Find the first `img` tag and remove the link inside the `src=""`. You will replace this with a new link.

<img style="height: auto; max-width: 75%;" src="{{ site.baseurl }}/assets/img/replaceimage.png">

<input type="checkbox" class="checkbox"> Go to Google images and search for images that relate to your webpage topic.

<input type="checkbox" class="checkbox"> Once you find a picture on Google, right click on the image and select “Copy image address” from the drop down menu.

<img style="height: auto; max-width: 75%;" src="{{ site.baseurl }}/assets/img/copyimageaddress.png">

<input type="checkbox" class="checkbox"> Return to your code and paste the copied image address into your code.

### CSS

CSS stands for Cascading Stylesheet.

With CSS you can change a website's background-images, types of fonts, text colors, and background-colors to style the page.

We will be editing an external style sheet. Click on the CSS tab in Codepen to see the CSS code.

CSS is separated by selectors, like `body`, `section`, `p`, etc...

<input type="checkbox" class="checkbox"> Find the body selector, and try changing the background color of the page by adding the line: `background-color: red;`

<img style="height: auto; max-width: 50%;" src="{{ site.baseurl }}/assets/img/bodycssbackground.png">

### Text Colors

The property that changes text-color is color.

For example, `color:white;` means that your text-color is white.

<input type="checkbox" class="checkbox"> Try changing the text color of the body.

<img style="height: auto; max-width: 50%;" src="{{ site.baseurl }}/assets/img/bodycss.png">

<input type="checkbox" class="checkbox"> Adjust the colors for the other selectors in your CSS file.

<input type="checkbox" class="checkbox"> Visit [this site](colors.commutercreative.com) for access to more colors.

<input type="checkbox" class="checkbox"> Change all of the different text colors on your page!

### Maps

<input type="checkbox" class="checkbox"> Click back to the HTML tab on Codepen.

<input type="checkbox" class="checkbox"> Visit Google Maps and type into the search bar any place in the world where you would like to visit!

<input type="checkbox" class="checkbox"> Click on the drop down menu.

<img style="height: auto; max-width: 50%;" src="{{ site.baseurl }}/assets/img/mapsmenu.png">

<input type="checkbox" class="checkbox"> Select “Share or embed map”.

<img style="height: auto; max-width: 40%;" src="{{ site.baseurl }}/assets/img/shareorembed.png">

<input type="checkbox" class="checkbox"> Click Embed map.

<img style="height: auto; max-width: 30%;" src="{{ site.baseurl }}/assets/img/selectembed.png">

<input type="checkbox" class="checkbox"> Click "Copy HTML".

<img style="height: auto; max-width: 75%;" src="{{ site.baseurl }}/assets/img/embedmap.png">

<input type="checkbox" class="checkbox"> Find the `<iframe>` tag for the Google Map in your HTML code.

<img style="height: auto; max-width: 75%;" src="{{ site.baseurl }}/assets/img/iframe.png">

<input type="checkbox" class="checkbox"> Replace all of the iframe code on your website with the new code that you just copied from Google Maps.

<input type="checkbox" class="checkbox"> Change the `<h2>` from iframe example to the name of the location you chose.

<img style="height: auto; max-width: 75%;" src="{{ site.baseurl }}/assets/img/iframereplace.png">

### Links

If you'd like to link to other pages, you can use the `<a>` tag in order to do so.

<input type="checkbox" class="checkbox"> Scroll down in the HTML until you see the section for links.

<input type="checkbox" class="checkbox"> Swap out the links by changing the text inside `href=""` to the link of your choice, and the text of the link by changing the text between the `<a>` and `</a>` tags.

<img style="height: auto; max-width: 85%;" src="{{ site.baseurl }}/assets/img/linkhref.png">


## Extras

### Gradients

Did you notice the cool color changing pattern on the links section? That's called a gradient!

<input type="checkbox" class="checkbox"> Head over to the CSS file and scroll to find the `#links` selector. See the `background-image` property? See the word "gradient"?

<img style="height: auto; max-width: 90%;" src="{{ site.baseurl }}/assets/img/linkscss.png">

<input type="checkbox" class="checkbox"> This is what creates our gradient, with a degree for rotation, and three colors throughout the gradient. Try changing these colors!

You can use words like "red", "blue", or "green" instead of the hex codes for colors, or you can find new hex codes.

<img style="height: auto; max-width: 90%;" src="{{ site.baseurl }}/assets/img/linkscolors.png">

<input type="checkbox" class="checkbox"> To find the hex code for a color, try Google's [color picker](https://www.google.com/search?q=color+picker).

You can also adjust the percentages on the gradient, and add more colors with more percentages.

<input type="checkbox" class="checkbox"> Try adding a gradient to another section of your website!

### JS

You may have noticed a third tab with some other code inside it. This is a programming language called JavaScript. JavaScript is used to make websites interactive.

<input type="checkbox" class="checkbox"> Try filling out the form and submitting it. See the pop up alert?

<input type="checkbox" class="checkbox"> Click over to the JS tab, and try changing the text of the alert by adjusting what's in the `var greeting`. Only change what's between the quotation marks.

<img style="height: auto; max-width: 100%;" src="{{ site.baseurl }}/assets/img/greeting.png">

<input type="checkbox" class="checkbox"> Can you add another field to the form? Copy one that already exists and change the id and placeholder. Then copy the corresponding line in JS and add the new variable to your alert message! 
