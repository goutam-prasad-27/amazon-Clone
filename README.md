Here are the bulleted points explaining the **HTML** code:

**DOCTYPE**
* This line specifies the document type as HTML.

**HTML Tag**
* `<html>` tag is the root element of the HTML document.

**Head Section**
* `<head>` tag contains meta information about the document.
    * `<meta charset="UTF-8">`: Defines the character encoding as UTF-8.
    * `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport for mobile devices. 
    * `<title>Document</title>`: Defines the title of the webpage.
    * `<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">`: Links an external stylesheet from Font Awesome library.
    * `<link rel="stylesheet" href="style.css">`: Links an internal stylesheet named style.css.

**Body Section**
* `<body>` tag contains the visible content of the webpage.

**Header Section**
* `<header>` tag defines the header section of the webpage.
    * `<div class="navbar">`: Navigation bar container with a class named "navbar".
        * A row containing the logo, delivery location, search bar, sign-in & order options, and shopping cart. Each section is wrapped in a separate `<div>` tag with a class name for styling.
    * `<div class="panel">`: Panel section containing links.

**Hero Section**
* `<div class="heroSection">`: Hero section with a message about the Indian store.

**Main Section**
* `<main>` tag defines the main content of the webpage.
    * `<div class="shopSection">`: Shop section containing boxes for different categories.
        * Each box is wrapped in a `<div>` tag with a class name "box".
            * The box contains a title, an image, and a "See More" link.

**Footer Section**
* `<footer>` tag defines the footer section of the webpage.
    * It contains sections for "Back To Top", "Get to Know Us" (repeated four times), base logo, copyright information, and links to various pages.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Here are the **CSS** code explanations in bullet points:

**Global Styles**
* Sets default styles for all elements:
    * No margin and padding
    * Font family is Helvetica
    * Uses border-box model for box sizing
    * Removes underline from links

**Navbar**
* Defines styles for the navigation bar section
    * Height: 60px
    * Background color: #0f1111 (dark gray)
    * Text color: whitesmoke
    * Flexbox properties:
        * Display: flex
        * Align-items: center (vertically aligns items in the center)
        * Justify-content: space-evenly (distributes items evenly)

**Amazon Logo**
* Styles for the navigation bar logo section
    * Height: 50px
    * Width: 113px
    * Defines background image for the logo using url(amazon_logo.png)

**Border Class**
* This class is used to add a hover effect with a white smoke colored border

**Delivery Location Box**
* Styles for the delivery location section
    * Uses flexbox for layout
    * Align-items: center (vertically aligns items)

**Search Box**
* Styles for the search box section
    * Uses flexbox for layout
    * Justify-content: space-evenly (distributes items evenly)
    * Width: 620px
    * Height: 40px
    * Rounded corners with 5px radius
    * Orange border on hover

**Sign In & Cart Box**
* Styles for the text inside the sign in and cart section
    * Span elements have a font size of 0.7rem
    * navPara class defines font size of 0.85rem and bold text

**Panel Section**
* Styles for the panel section
    * Uses flexbox for layout
    * Align-items: center (vertically aligns items)
    * Justify-content: space-evenly (distributes items evenly)
    * Height: 40px
    * Background color: #222f3d (dark blue)
    * Text color: whitesmoke

**Hero Section**
* Styles for the Hero section
    * Height: 350px
    * Uses flexbox for layout
    * Align-items: flex-end (vertically aligns content to the bottom)
    * Justify-content: center (horizontally aligns content to the center)
    * Background image with url(hero_image.jpg) set as cover

**Shop Section**
* Styles for the shop section
    * Uses flexbox for layout
    * Flex-wrap: wrap allows elements to wrap to the next line if they don't fit
    * Justify-content: space-evenly (distributes items evenly)
    * Background color: #e2e7e6 (light gray)

**Box Styles**
* Styles for each product box
    * Height: 400px
    * Width: 23% of the parent container
    * Background color: whitesmoke
    * Padding: 20px 0px 15px (top, right/left, bottom)
    * Margin-top: 15px

**Footer**
* Styles for the footer section
    * Margin-top: 15px

**Foot Panel**
* Styles for the top section of the footer
    * Height: 50px
    * Background color: #37475a (dark blue)
    * Text color: whitesmoke
    * Uses flexbox for layout with center alignment

**Get to Know Us Section**
* Styles for the "Get to Know Us" section
    * Background color: #222f3d (dark blue)
    * Text color: whitesmoke
    * Height: 300px
    * Uses flexbox for layout with space-evenly distribution

**List Styles**
* Styles for unordered lists
    * Margin-top: 20px
    * Link colors set to #dddddd (light gray)

**Footer Logo**
* Styles for the footer logo section
    * Background color: #222f3d (dark blue)
    * Text color: whitesmoke
    * Defines a white smoke colored top border
    * Height: 70px
    * Uses flexbox for layout with center alignment

**Footer Logo Image**
* Styles for the logo image inside the footer
    * Background image with url(amazon_logo.png) set as cover
    * Height: 50px
    * Width: 1