# Bootstrap Responsive Design Guide
Options for structuring your web pages, including global styles, required scaffolding, grid system

## 1. Definition
* Design software: Adobe Photoshop, Adobe Illustrator
* Design document unit: pixel
-Color mode: RGB
-Adobe Photoshop document:
  * Resolution: 72 pixels / inch
* Page container:
  * Dimension: Follow the breakpoints
  * Padding/Gutter left: 15 pixels
  * Padding/Gutter right: 15 pixels
* Content container:
  * Fit in defined 12 columns in each breakpoints
  * The width dimension should be fit in a number of columns

## 2. Responsive breakpoints
In responsive design, we split screen size into 5 groups. When design the web pages, the web page’s contents have to place in a container that has a limitation of width based on each screen size.
The design file has to cover whole page’s content including:
* Background image
* Background color
* Carousel/Image slider

The design document has to cover at least the ceil of device width breakpoints. This will define in each device breakpoint.
If the design is different between portrait and landscape, it has to designed by two separate document.

### 2.1	Extra small devices
Apply for cell phone and device less than 544 pixels on both landscape and portrait mode.
Design document dimension
* Width: 320 pixels
* Height: unlimited

Recommend design document:
* Width:  480 pixels

### 2.2	Small device
Apply for landscape cell phones, phablets that have screen size large than 544 pixels and less than 768 pixels
Page container dimension:
* Max width: 640 pixels
* Height: unlimited

Recommend design document:
* Width:  760 pixels

### 2.3	Medium device:
Apply for tablets that have screen size between 768 pixels and 992 pixels
Page container dimension:
* Width: 750 pixels
* Height: unlimited

Recommend design document:
* width:  1366 pixels

### 2.4	Large device:
Apply for desktops that have screen size between 992 pixels and 1199 pixels
Page container dimension:
* Width: 970 pixels
* Height: unlimited
Recommend design document:
* Width:  1366 pixels

### 2.5	Extra Large device:
Apply for large desktops that have screen size large than 1200 pixels
Page container dimension:
* Width: 1170 pixels
* Height: unlimited
Recommend design document:
* Width:  1600 pixels
