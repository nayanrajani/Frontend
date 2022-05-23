- CSS
    - CSS or Cascading Style Sheets is the language used to style the frontend of any website. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

    - FREE CONTENT
        - READ [W3Schools — Learn CSS](https://www.w3schools.com/css/)

        - READ [Web.dev by Google — Learn CSS](https://web.dev/learn/css/)

        - READ [freeCodeCamp — Responsive Web Design](https://www.freecodecamp.org/learn/responsive-web-design/)

        - READ [Learn to Code HTML & CSS](https://learn.shayhowe.com/html-css/building-your-first-web-page/)

        - COURSE [CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI)

        - COURSE [HTML and CSS Tutorial](https://www.youtube.com/watch?v=D-h8L5hgW-w)

        - COURSE [CSS Masterclass - Tutorial & Course for Beginners](https://www.youtube.com/watch?v=FqmB-Zj2-PA)

        - COURSE [Learn CSS | Codecademy](https://www.codecademy.com/learn/learn-css)

        - COURSE [Learn Intermediate CSS | Codecademy](https://www.codecademy.com/learn/learn-intermediate-css)

- CSS Introduction
    - CSS is the language we use to style a Web page.

- What is CSS?
    - CSS stands for Cascading Style Sheets
    - CSS describes how HTML elements are to be displayed on screen, paper, or in other media
    - CSS saves a lot of work. It can control the layout of multiple web pages all at once
    - External stylesheets are stored in CSS files
    - CSS Demo - One HTML Page - Multiple Styles!
    - Here we will show one HTML page displayed with four different stylesheets. Click on the "Stylesheet 1", "Stylesheet 2", "Stylesheet 3", "Stylesheet 4" links below to see the different styles:


- Why Use CSS?
    - CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

- CSS Example
    body {
    background-color: lightblue;
    }

    h1 {
    color: white;
    text-align: center;
    }

    p {
    font-family: verdana;
    font-size: 20px;
    }

- CSS Solved a Big Problem
    - HTML was NEVER intended to contain tags for formatting a web page!
    - HTML was created to describe the content of a web page, like:
        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>

    - When tags like <font>, and color attributes were added to the HTML 3.2 specification, it started - a nightmare for web developers. Development of large websites, where fonts and color information - were added to every single page, became a long and expensive process.
    - To solve this problem, the World Wide Web Consortium (W3C) created CSS.
    - CSS removed the style formatting from the HTML page!
    - If you don't know what HTML is, we suggest that you read our HTML Tutorial.
    - CSS Saves a Lot of Work!
    - The style definitions are normally saved in external .css files.
    - With an external stylesheet file, you can change the look of an entire website by changing just one file!

- CSS Syntax
    - A CSS rule consists of a selector and a declaration block.

- CSS Syntax

<img width="461" alt="image" src="https://user-images.githubusercontent.com/57224583/169799535-53f53a68-25d3-47e6-9a0f-8482072ac15c.png">

- CSS selector

    - The selector points to the HTML element you want to style.

    - The declaration block contains one or more declarations separated by semicolons.

    - Each declaration includes a CSS property name and a value, separated by a colon.

    - Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

    - Example
        - In this example all <p> elements will be center-aligned, with a red text color:

        p {
        color: red;
        text-align: center;
        }
    
    - Example Explained
        - p is a selector in CSS (it points to the HTML element you want to style: <p>).
        - color is a property, and red is the property value
        - text-align is a property, and center is the property value
        - You will learn much more about CSS selectors and CSS properties in the next chapters!

- CSS Selectors
    - A CSS selector selects the HTML element(s) you want to style.

    - CSS selectors are used to "find" (or select) the HTML elements you want to style.

    - We can divide CSS selectors into five categories:

        - Simple selectors (select elements based on name, id, class)
        - Combinator selectors (select elements based on a specific relationship between them)
        - Pseudo-class selectors (select elements based on a certain state)
        - Pseudo-elements selectors (select and style a part of an element)
        - Attribute selectors (select elements based on an attribute or attribute value)

- How To Add CSS
    - When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.

    - Three Ways to Insert CSS
        - There are three ways of inserting a style sheet:

            - External CSS
            - Internal CSS
            - Inline CSS

            - External CSS
                - With an external style sheet, you can change the look of an entire website by changing just one file!

                - Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

                - Example
                    - External styles are defined within the <link> element, inside the <head> section of an HTML page:

                        <!DOCTYPE html>
                        <html>
                        <head>
                        <link rel="stylesheet" href="mystyle.css">
                        </head>
                        <body>

                        <h1>This is a heading</h1>
                        <p>This is a paragraph.</p>

                        </body>
                        </html>

                    - An external style sheet can be written in any text editor, and must be saved with a .css extension.

                    - The external .css file should not contain any HTML tags.

                    - Here is how the "mystyle.css" file looks:

                        "mystyle.css"
                        body {
                        background-color: lightblue;
                        }

                        h1 {
                        color: navy;
                        margin-left: 20px;
                        }

                    - Note: Do not add a space between the property value and the unit:
                    Incorrect (space): margin-left: 20 px;
                    Correct (nospace): margin-left: 20px;

            - Internal CSS
                - An internal style sheet may be used if one single HTML page has a unique style.

                - The internal style is defined inside the <style> element, inside the head section.

                - Example
                    - Internal styles are defined within the <style> element, inside the <head> section of an HTML page:

                        <!DOCTYPE html>
                        <html>
                        <head>
                        <style>
                        body {
                        background-color: linen;
                        }

                        h1 {
                        color: maroon;
                        margin-left: 40px;
                        }
                        </style>
                        </head>
                        <body>

                        <h1>This is a heading</h1>
                        <p>This is a paragraph.</p>

                        </body>
                        </html>

            - Inline CSS
                - An inline style may be used to apply a unique style for a single element.

                - To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

                - Example
                    - Inline styles are defined within the "style" attribute of the relevant element:

                        <!DOCTYPE html>
                        <html>
                        <body>

                        <h1 style="color:blue;text-align:center;">This is a heading</h1>
                        <p style="color:red;">This is a paragraph.</p>

                        </body>
                        </html>
                - Tip: An inline style loses many of the advantages of a style sheet (by mixing content with presentation). Use this method sparingly.

    - Multiple Style Sheets
        - If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used. 

        - Assume that an external style sheet has the following style for the <h1> element:

            h1 {
            color: navy;
            }
            Then, assume that an internal style sheet also has the following style for the <h1> element:

            h1 {
            color: orange;   
            }
        - Example
            - If the internal style is defined after the link to the external style sheet, the <h1> elements will be "orange":

                <head>
                <link rel="stylesheet" type="text/css" href="mystyle.css">
                <style>
                h1 {
                color: orange;
                }
                </style>
                </head>
                Example
                However, if the internal style is defined before the link to the external style sheet, the <h1> elements will be "navy": 

                <head>
                <style>
                h1 {
                color: orange;
                }
                </style>
                <link rel="stylesheet" type="text/css" href="mystyle.css">
                </head>
    - Cascading Order
        - What style will be used when there is more than one style specified for an HTML element?

        - All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

            - Inline style (inside an HTML element)
            - External and internal style sheets (in the head section)
            - Browser default

        - So, an inline style has the highest priority, and will override external and internal styles and browser defaults.

- CSS Comments
    - HTML <!-- Comment  -->
    - CSS /* Comment */

- CSS Color
    - Colors
        - Color Names
        - Background-Color
        - Text-Color
        - Border Color
        - Color Values

    - RGB Color
        - An RGB color value represents RED, GREEN, and BLUE light sources.

        - RGB Value
            - In CSS, a color can be specified as an RGB value, using this formula:

                - rgb(red, green, blue)

                    - Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

                    - For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

                    - To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

                    - To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

        - RGBA Value
            - RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.

            - An RGBA color value is specified with:

            - rgba(red, green, blue, alpha)

                - The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all).

    - HEX Color
        - A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal integers specify the components of the color.

        - HEX Value
            - In CSS, a color can be specified using a hexadecimal value in the form:

                - #rrggbb

            - Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

            - For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

            - To display black, set all values to 00, like this: #000000.

            - To display white, set all values to ff, like this: #ffffff. 
        
        - 3 Digit HEX Value
            - Sometimes you will see a 3-digit hex code in the CSS source.

            - The 3-digit hex code is a shorthand for some 6-digit hex codes.

            - The 3-digit hex code has the following form:

                - #rgb

            - Where r, g, and b represents the red, green, and blue components with values between 0 and f.

            - The 3-digit hex code can only be used when both the values (RR, GG, and BB) are the same for each components. So, if we have #ff00cc, it can be written like this: #f0c.

    - HSL Value
        - In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form:

            - hsl(hue, saturation, lightness)

        - HUE
            - Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

            - Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

            - Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white

        - Saturation
            - Saturation can be described as the intensity of a color.

            - 100% is pure color, no shades of gray

            - 50% is 50% gray, but you can still see the color.

            - 0% is completely gray, you can no longer see the color.

        - Lightness
            - The lightness of a color can be described as how much light you want to give the color, where 0% means no light (black), 50% means 50% light (neither dark nor light) 100% means full lightness (white).

        - Shades of Gray
            - Shades of gray are often defined by setting the hue and saturation to 0, and adjust the lightness from 0% to 100% to get darker/lighter shades:

        - HSLA Value
            - HSLA color values are an extension of HSL color values with an alpha channel - which specifies the opacity for a color.

            - An HSLA color value is specified with:

                - hsla(hue, saturation, lightness, alpha)

            - The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all):