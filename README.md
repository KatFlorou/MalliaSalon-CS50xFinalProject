# MALLIA SALON
MALLIA SALON is a website for a hair salon.

### Description:
This website was created by Katerina Florou as a final project for CS50 2022.
It's ultimate purpose is to be used by the hair salon owner as the official website of the hair salon.
The design and the color palette (grey, black, white) was inspired by the salon's interior design and logo.

#### Languages used:
- HTML
- CSS
- JavaScript

The project consists of three code files:
1. index.html
2. style.css
3. index.js

#### index.html
This file contains the entire html code for the website.
Instead of having many different files for each subpage/section, I decided to go for a sigle page where each section covers the whole viewport. There is not a lot of information on each section so I thought that having only one page is easier and better in terms of memory needs. The file is separated in five sections:
-navbar
-introduction
-services
-team
-contact.

#### style.css
This file contains the entire css code for the website.
There is a lot of emphasis on the styles being responsive with the use of functions as
```
:root {
    font-size: clamp(14px, 1.5vw, 28px);
}
```
or preference of vh and vw as units.
There are two different styles for screens with the breakpoint set at 600px.

#### index.js
This file contains the entire JavaScript code for the website.
It contains functions to open and close the navbar dropdown menu on screens <= 600px and functions to open and close the modal on "open positions".
# Mallia-Salon
