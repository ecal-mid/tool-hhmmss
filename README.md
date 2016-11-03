# HHMMSS
An editable clock for time-based parametric projects


## How to use it ?
* Download the "js" and "css" folder and put them in your project folder

* Add `<link rel="stylesheet" type="text/css" href="css/hhmmss.css" />` in your `<head>`

* Add `<script src="js/hhmmss.js"></script>` before `</body>` (or wherever you prefer)

* Add a `<script></script>` right after the previous line

* Declare a new variable `hhmmss` and assign `new HHMMSS()`

* If you want to, you can change the clock's appearance by adding an object as a parameter of the `HHMMSS()` function. The different options are listed below

* Get the clock time in your code using `hhmmss.getH()`, `hhmmss.getM()`, `hhmmss.getS()` and `hhmmss.getMillis()`

* Check the "index.html" example file if you need any help


## Controls
* Moving the mouse will reveal the clock

* Clicking on either the hours, minutes or seconds will put them in "edit" mode. If you click outside the selected number or if you press enter, it will validate the current value (if not empty)

* Drag-and-dropping from left to right (and vice-versa) on a number will increment or decrement it

* Double-clicking will reset the clock to current time


## Options
* `type` : `"horizontal"` (default) or `"vertical"`

* `horizontalAlign` : `"left"`, `"hcenter"` (default) or `"right"`

* `verticalAlign` : `"top"`, `"vcenter"` (default) or `"bottom"`

* `size` : `"small"`, `"medium"` (default) or `"big"`

* `invert` : `false` or `true` (default)


## Aknowledgment
This script was coded for a course taught by Angelo Benedetto at ECAL/University of Art and Design Lausanne. The typeface used is "Michroma" by Vernon Adams (https://fonts.google.com/specimen/Michroma) and it has been slightly modified by Tancrède Ottiger (http://t--o.ch) to make tabular figures.
