# Practice: Creating a Webpage building upon HTML basics and understanding how to use CSS

## Understanding selectors and properties to bring styling with colors, fonts, sizing, layouts, and much more...

### Practce understanding CSS Shorthands

-   [ ] Simple practice to gain a better understanding of the power of adding CSS Styling to a webpage and how it can make it uniquely beautiful
    -   [ ] CSS or Cascading Style Sheet, is a language that paints a website with colors, fonts, layouts, and animations.
    -   [ ] CSS is used to create stunning webpages.
    -   [ ] It can enhance the user experience, and can make a webpage unquie and stand out amongst the rest.
    -   [ ] It is absolutely beautiful to see a webpage come to life and become even more beautiful.

<hr>

-   [ ] Every rule begins with a selector then followed by curly brackets {}
    -   [ ] Inside the curly brackets, declarations are made of property:value pairs seperated by a colon.
    -   [ ] Each line will end with a semicolon ; .
    -   [ ] CSS files have as many rules as desired. Even most webpages commonly used could have several hundres of CSS rules for it.

<hr>

-   [ ] CSS Selectors are used to determine which CSS elements are styled
    -   [ ] The most common type of selectors is the following:
        -   [ ] Type Selectors:
            -   [ ] Selects all the matching elements on the webpage for styling
    -   [ ] HTML elements can be selected by their HTML attributes
        -   [ ] Selecing an element by "class" is done by using a period ".", and can be used to style multiple elements with a matching "class" attribute
        -   [ ] Selecting an element by "id" is done by using a hashtag "#", and is used to style a single element with a matching "id" attribute.
    -   [ ] Instead of selecting every element with a matching class only "div" elements that either have a class of "class-name" or an "id" of "id-name".
        -   [ ] This selection is known as "targeting"

<hr>

-   [ ] CSS Shorthands:
    -   [ ] There are properties in CSS that an be broken down into seperate more specific properties
    -   [ ] For instance, the "border" property is shorthand for three additional properties: width, style, and color:
        -   [ ] <img src="img/b-border-shorthand-breakdown.png" alt="Border syntax covering 3 additional properties" width="250">
        -   [ ] It can be expressed with the shorthand "border" property:
            -   [ ] <img src="img/c-border-syntax.png" alt="Shorthand for different border property syntax" width="250">
        -   Either of the above will render the same result:
            -   <img src="img/d-rendered-result.png" alt="Rendered result of either border properties" width="250">
    -   Different "font" properties can be written shorthand as well:
        -   <img src="img/e-different-font-properties-syntax.png" alt="Different font properties syntax" width="250">
        -   This would be the shorthand for this:
            -   <img src="img/f-shorthand-syntax-for-different-font-properties.png" alt="Shorthand syntax for different font properties">
            -   The shorthand "font" must at least have a value for the "font-family" and "font-size" properties.
            -   The "font-weight" must go before the "font-size" (i.e. 800 12px)

<hr>

-   [ ] The &lt;header&gt; element:
    -   [ ] Is used for the beginning of the webpage
    -   [ ] Houses the title of the webpage along with Logos
    -   [ ] The &lt;img&gt; element:
        -   [ ] Is used for all the images on the webpage

-   [ ] The &lt;nav&gt; element:
    -   [ ] This element tends to contain ordered lists, unordered lists, or even both types of lists
    -   [ ] Each &lt;li&gt; element will house an &lt;a&gt; elements with the #id-name of the desired section or part of the webpage it will be linked within the "href" attribute
        -   [ ] For instance:
            -   [ ] &lt;a href="#desired-section"&gt;🌸 Desired Section🌸&lt;/a&gt;
            -   [ ] <a href="#desired-section">🌸 Desired Section 🌸</a>
            -   [ ] When the user would click the 🌸 Desired Section 🌸 link they would then be navigated to that section of the webpage

-   [ ] The &lt;br&gt; element:
    -   [ ] Creates a new line in your code and forces whatever comes after to start on a new lin

-   [ ] The &lt;hr&gt; element:
    -   [ ] Adds a horizontal line or dividing line across the webpage
    -   [ ] Used to separate sections or different topics on a webpage

-   [ ] The &lt;main&gt; element:
    -   [ ] Is where the main information of the webpage will go
    -   [ ] The &lt;section&gt; element:
        -   [ ] This groups together pieces of similar information

-   [ ]  The &lt;footer&gt; element:
    -   [ ]  This element tends to finish off the webpage as it is located at the very bottom of the webpage and is the last set of items that will be seen
    -   [ ] For instance:
        -   [ ] A footnote on the webpage
        -   [ ] Links to different sections of the webpage
        -   [ ] A copyright symbol for copyright information
            -   [ ] & copy; -> is the symbol for copyright
        -   [ ] A link to external sources using the "href" attribute of the &lt;a&gt; element for the links in the list item to external sources
            -   [ ] &lt;a href="/privacy"&gt;Privacy&lt;/a&gt;
                -   [ ] Use the target attribute to open the link path in a new tab instead of the current page
                -   [ ] <a href="/privacy" target="_blank">Privacy</a>
                -   [ ] When the user clicks one of these external links, they would be redirected to a new page with the informat ion

<hr>

-   [ ] Encompass:
    -   [ ] HTML
    -   [ ] CSS
-   [ ] HTML:
    -   [ ] Will be the structure and skeleton of how the app will appear on the webpageWill be the structure and skeleton of how the app will appear on the webpage
-   [ ] CSS:
    -   [ ] Encompass the style of the app and give it some flair
