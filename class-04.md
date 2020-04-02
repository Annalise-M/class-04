### Class Notes - 04
html:
* Chapter 4: Ch.4 “Links” (pp.74-93)
* Chapter 15: “Layout” (pp.358-404)

js:
* Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
* Article: “6 Reasons for Pair Programming”

### Links
    writing links | pg. 77
    linking to other sites | pg. 79
    linking to other pages on the same site | pg. 80
    directory structure | pg. 81
    relative urls | pg. 83
    email links | pg. 85
        mailto:
    opening links in a new window | pg. 86
        target
    linking to a specific part of the SAME page | pg. 87
    linking to a specific part of ANOTHER page | pg. 88

### Layout
* controlling the positino of elements
* creating site layouts
* designing for different sized screens

key concepts in positioning elements:

    building blocks | pg. 361
    containing elements | pg. 362
    controlling the position of elements | pg. 363
    normal flow | pg. 365
        position:static
    relative positioning | pg. 366
        position:relative
    absolute positioning | pg. 367
        position:absolute
    fixed positioning | pg. 368
        position:fixed
    overlapping elements | pg. 369
        z-index
    floating elements | pg. 370
        float
    using float to place elements side by side | pg. 371
    clearing floats | pg. 372
        clear
    parents of floated elements: problem | pg. 373
    parents of floated elements: solution | pg. 374
    creating multi-column layouts with floats | pg. 375
        width:
        float:
        margin:
    screen sizes | pg. 377
    screen resolution | pg. 378
    page sizes | pg. 379
    fixed width layouts | pg. 381; 383, 384
    liquid layouts | pg. 382; 385, 386
    layout grids | pg. 387
    css frameworks | pg. 391
        - using the 960.GS grid | pg. 392
        - a grid based layout using 960.GS | pg. 393
    multiple style sheets | pg. 395
        @import
    multiple style sheets | pg. 396
        link
    
### Functions, Methods, and Objects
    basic functions | pg. 89
    declaring a function | pg. 90
    calling a function | pg. 91
    declaring functions that need info | pg. 92
        function getArea(width, height) {
            return width * height;
        }
    calling function that need info | pg. 93
        arguments as values ex. 
        getArea(3,5)
        arguments as variables ex.
        wallWidth = 3;
        wallHeight = 5;
        getArea(wallWidth, wallHeight);
    getting a single value out of a function | pg. 94
        function calculateArea(width, height) {
            var area = width * height;
            return area;
        }
        var wallOne = calculateArea(3,5);
        var wallTwo = calculateArea(8,5);
    getting multiple values out f a function | pg. 95
        function getSize(width, height, depth) {
            var area = width * height;
            var volume = width * height * depth;
            var sizes = [area, volume];
            return sizes;
        }
        var areaOne = getSize (3, 2, 3)[0];
        var volumeOne = getSize (3, 2, 3)[1];
    anonymous functions & function expressions | pg.96  
    immediately invoked function expressions | pg. 97
    variable scope | pg. 98
    how memory variables work | pg. 99
    




