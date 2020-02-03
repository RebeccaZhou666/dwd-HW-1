# dwd-HW-1

<!-- Every README should start with an H1 -->
<!-- A one sentence description of the project or assignment -->
A horizontal parallax scrolling website using pure css.
Try [DEMO](https://rebeccazhou666-dwd-hw-1.glitch.me/) Here.


<!-- It is essential to describe how to set up your project -->
## Setup
No prerequisites. Just clone the repo and open it using localhost.

## Process & Documentation
1. Build a horizonal scrolling website. [Reference 1](https://www.youtube.com/watch?v=OeaHnxahf40)
  * The key point of creating a horizontal web is to create a horizontal content (define width) and rotate outer-div once and inner-div twice to achieve the vertical scrolling (I think the reference video is pretty clear).
2. Add parallax effect for divs. [Reference 2](https://medium.com/@dailyfire/pure-css-parallax-simple-tricks-da102d0ffdb9).
  * The underlying mechanism of achieving parallax effect is to use 3d-perspective.  
  * For parallax wrappers, define transform-style as preserved-3d, define perspectives and change display as flex. 
  * Define layers in parallax wrappers: position as absolute, adjust left and top distance accordingly.
  * By transforming layers (divs) in Z-axis and scale the speed according to the z-distance, 
3. Beautify it by adding photos (taken by myself) and design.
  * add fixed social media icons.
  * add github links in lower-right corner.
  * add cover.
  
## Difficulty 
The hardest part of parallax effect for me is to understand the positon and display attributes for wrappers and inner layers. 


## Further Improvements 
1. Using unordered lists instead of div for the contents.
2. Try different styles of parallax effects and animation when scrolling, like [this](https://www.defeatboco.com/)


## Built with

* [VS Code](https://code.visualstudio.com/)
* [Github](https://github.com)
* [Glitch](https://glitch.com/)

## Inspiration
* 30 beautiful parallax websites [link](https://www.awwwards.com/30-great-websites-with-parallax-scrolling.html).

## Acknowledgements

* [Horizontal scrolling tutorial](https://www.youtube.com/watch?v=OeaHnxahf40).
* [Pure css parallax tutorial](https://medium.com/@dailyfire/pure-css-parallax-simple-tricks-da102d0ffdb9) 

***


* Jingyi Zhou. Feb 1, 2020
