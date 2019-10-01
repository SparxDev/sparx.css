# Sparx.CSS
CSS Framework with some cool features, yo!

> As of now (10/01/2019), this project is almost 3 years old, and I have stopped caring about it a long time ago. This has been so long ago, that the old documentation for this framework no longer exists. As I realized that the docs are missing, I could not just turn a blind eye; despite my negligence for this project, I did not want to have a framework with no proper documentation, and I could not bring it upon myself to just delete this framework either. And that is the reason as to why I wrote this not thorough, but adequate documentation.

### Screenshot
![Screenshot](screenshot.png)
# How to use
Add this stylesheet to your ``<head>`` tag in your HTML File:
```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/SparxDev/sparx.css/master/lib/sparx.css">
```

## Colors
These flat UI color-classes apply an background color to the element:
+ teal1
+ teal2
+ yellow
+ orange1
+ orange2
+ orange3
+ green1
+ green2
+ blue1
+ blue2
+ red1
+ red2
+ purple1
+ purple2
+ white
+ silver1
+ silver2
+ silver3
+ silver4
+ black
+ midnight-blue1
+ midnight-blue2

To use these classes as text-color, simply add an ``text-`` prefix to the class, e.g.: ``text-orange1``.

## Container
This class adds a padding to the element:
```
<div class="container">
  <p>I'm an Example!</p>
</div>
```

## Border
Applies a thin border to an element; the classes are: ``border``, ``border-top``, ``border-right``, ``border-bottom``, and ``border-left``.

## Shadows
Google-inspired drop-shadows, ranging from ``shadow1`` up to ``shadow5``.

## Roundness
The classes ``round-small``, ``round-medium``, ``round-large``, ``round-xlarge``, and ``round-xxlarge`` all add rounded corners to an element. The ``circle``-class turns the element into a circle (implying that the element's width and height are the same).

## Padding
Classes growing from 0 up to 128:
+ padding-0
+ padding-8
+ padding-12
+ padding-16
+ padding-24
+ padding-32
+ padding-48
+ padding-64
+ padding-128

## Margin
Classes growing from 0 up to 128:
+ margin-0
+ margin-8
+ margin-12
+ margin-16
+ margin-24
+ margin-32
+ margin-48
+ margin-64
+ padding-128

## Buttons
Usage:
```
<input class="btn" type="button" value="Input Button">
<a class="btn" href="#">Link Button</a>
<button class="btn">Button Button</button>
```

Colored buttons:
```
<button class="btn red1">Button Button</button>
```

Buttons with hover-effect:
```
<button class="btn red1 red1-hover">Button Button</button>
```

## Centering
Left:
```
<div class="left">
  <p>I'm on the left!</p>
</div>
```
Center:
```
<div class="center">
  <p>I'm in the middle!</p>
</div> 
```
**Text**-center:
```
<div class="text-center">
  <p>Only the text is in the middle!</p>
</div>
```
Right:
```
<div class="right">
  <p>I'm on the right!</p>
</div>
```

## Tables
```
<table class="table-striped table-bordered">
 <tr>
  <th>Username</th>
  <th>Email</th>
  <th>Friends</th>
 </tr>
 <tr>
  <td>RandomDude</td>
  <td>rndmdude@example.com</td>
  <td>13</td>
 </tr>
 <tr>
  <td>LOLdude24</td>
  <td>loldude24@example.com</td>
  <td>23</td>
 </tr>
</table>
```

## Progressbar
Usage:
```
<div class="progressbar">
 <div class="progress green1" style="width:10%;"></div>
</div>
```
Multiple bars combined:
```
<div class="progressbar">
 <div class="progress red1" style="width:75%;">
  <div class="progress blue1" style="width:25%;"></div>
 </div>
</div>
```

## Dropdowns
Usage:
```
<div class="dropdown">
 <button class="btn">Dropdown</button>
 <div class="dropdown-content shadow3">
  <a href="#">Link 1</a>
  <a href="#">Link 2</a>
  <a href="#">Link 3</a>
 </div>
</div>
```

## Navigation
Usage:
```
<div class="navbar">
 <a href="#" class="nav-item">Link 1</a>
 <a href="#" class="nav-item">Link 2</a>
 <a href="#" class="nav-item">Link 3</a>
 <a href="#" class="nav-item">Link 4</a>
</div>
```
