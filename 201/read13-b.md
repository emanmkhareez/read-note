# Transforms.
that have different setting

2d: Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes

 3d:hree-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth.

. Each of these come with their own individual properties and values.

Transform Syntax.

div {

  -webkit-transform: scale(1.5);

     -moz-transform: scale(1.5);

       -o-transform: scale(1.5);

          transform: scale(1.5);}


  ### 2D Rotate

  The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.

  .box-1 {

  transform: rotate(20deg);

}

### 2D Scale:
allows you to change the appeared size of an element. 

The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

smaller

.box-1 {

  transform: scale(.75);
}

larger

.box-2 {

  transform: scale(1.25);
}


### 2D Translate.

e works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document
.
.box-1 {

  transform: translateX(-10px);
}

.box-2 {

  transform: translateY(25%);
}

.box-3 {

  transform: translate(-10px, 25%);

}

### 2D Skew

skew, is used to distort elements on the horizontal axis, vertical axis, or both.

The distance calculation of the skew value is measured in units of degrees. Length measurements, such as pixels or percentages,

.box-1 {

  transform: skewX(5deg);
}

.box-2 {
  transform: skewY(-20deg);
}

.box-3 {
  transform: skew(5deg, -20deg);
}
