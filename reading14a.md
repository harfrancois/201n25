# 2D Transforms
- Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.

example: https://learn.shayhowe.com/advanced-html-css/css-transforms/

HTML
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
<figure class="box-3">Box 3</figure>

CSS
.box-1 {
  transform: scaleX(.5);
}
.box-2 {
  transform: scaleY(1.15);
}
.box-3 {
  transform: scale(.5, 1.15);
}

# 3D Transforms

With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ.

HTML
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
<figure class="box-3">Box 3</figure>

CSS
.box-1 {
  transform: perspective(200px) rotateX(45deg);
}
.box-2 {
  transform: perspective(200px) rotateY(45deg);
}
.box-3 {
  transform: perspective(200px) rotateZ(45deg);
}

Transitions & Animations
https://learn.shayhowe.com/advanced-html-css/transitions-animations/

With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

Styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay.

.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
# Great examples in animation

8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users

6 Buttons animated
https://codepen.io/retyui/pen/ByoaXV

CSS3 Animations: Keyframes
https://codepen.io/akshaychauhan/pen/oAfae

404
https://codepen.io/kieranfivestars/pen/MYdQxX

Pure CSS Bounce Animation
https://codepen.io/dp_lewis/pen/gCfBv