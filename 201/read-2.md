# read 2
## HTML pages are text documents.
 ## tag: is defined as a set of characters commonly constituting a formatted command for a Web page. At the core of HTML, tags provide the directions or recipes for the visual content that one sees on the Web.
 # semantic Markup.
 ## The reason for using these elements is .
  other programs, such as screen readers or search engines, can use this extra information
  For example, the voice of a screen reader may add emphasis to the words inside the  em  tag element.
  # semantic tag
  
  ## The  strong tag is used to define text with strong importance. The content inside is typically displayed in bold.
  ## The  em tag is used to define emphasized text. The content inside is typically displayed in italic.

  ![strong & em](https://i.ytimg.com/vi/plxdX4wOtBY/maxresdefault.jpg).

  ## the blockquote tag specifies a section that is quoted from another source.Browsers usually indent blockquote elements (look at example below to see how to remove the indentation).
## The q element is used for shorter quotes that sit within a paragraph.
## The abbr tag defines an abbreviation or an acronym, like "HTML". /
 the cite tag defines the title of a creative work (e.g. a book, a poem)
![img code ](201/img2.png).
# css (	Cascading Style Sheet)
This part is interested to make the web page more coordinated .

## BLOCK & INLINE ELEMENTS
1-block element : that started on a new line example h1,div.
2-inline element :flow within the text do not start in new line.

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts:**a selector** and a **declaration**.
### selectors are patterns used to select the element(s) you want to style.
### declarations separated by semicolons. Each declaration includes a CSS property name and a value, separated by a colon.
## example:

![selctor & declaration](https://www.w3schools.com/css/selector.gif)
# how css work
1- external page that embedded in html file using link tag.

![external css](https://learnitanytime.com/wp-content/uploads/2014/05/External-link-CSS-300x152.jpg)

2-internal inside the page.

![internal css](https://codebridgeplus.com/wp-content/uploads/InternalCSSInternalstylingisdefinedinthe_head_sectionofanHTMLpageusinga_style_element..jpg)

3-inline inside the element.

![inline css](https://kloudrac.com/wp-content/uploads/2018/09/Screenshot_7-1.png)

# color
Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
1- write the name of color .
# h1 {
# color: DarkCyan;}
2-RGB :RGB color values are supported in all browsers,An RGB color value is specified with: rgb(red, green, blue).


![rgb values](https://creativepro.com/wp-content/uploads/2015/09/CSS-code-mixed-color-models.jpg)

3-hex codes:Simply type the 6 digit color code in the box above and hit enter.
![hex codes](https://wilkesley.org/~ian/xah/emacs/i/emacs_hexcode_highlight_32718.png)

4-Saturation: is the intensity of a hue from gray tone (no saturation) to pure, vivid color (high saturation).


5- Hue: refers to the origin of the colors we can see. Primary and Secondary colors (Yellow, Orange, Red, Violet, Blue, and Green) are considered hues; however, tertiary colors (mixed colors where neither color is dominant) would also be considered hues.


6-Brightness: is the relative lightness or darkness of a particular color, from black (no brightness) to white (full brightness). Brightness is also called Lightness in some contexts, in particular in SQL queries.

![color](https://i.stack.imgur.com/xjgXX.jpg)
# javascript 
using this to make the website interactive with user (dynamic)
write this in two way 
1-internal :inside the html page
![internal](https://www.codegrepper.com/codeimages/insert-image-into-html-javascript.png)
2- external :write this in another file 
![external](https://i.stack.imgur.com/iF82j.jpg)
# what the loop in the javascript
for loop:loops through a block of code a number of times and this limited time.
The while loop: loops through a block of code as long as a specified condition is true.
# if statment & switch
tow check anything using javascript use the if statement for example two check if the student pass in the exam or fail write this statement
var stuGrade =59
if (stu>50 ){
document.write("this stu is pass")
} else {
document.write("this stu is fial")
}
The switch statement is used to perform different actions based on different conditions.
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
This is how it works:

The switch expression is evaluated once.
The value of the expression is compared with the values of each case.
If there is a match, the associated block of code is executed.
If there is no match, the default code block is executed.
# TYPE COERCION
JavaScript can convert data
types behind the scenes to
complete an operation. This is
known as type coercion. For
example, a string 'l ' could be
converted to a number 1 in the
following expression:(' 1' > 0).
As a result, the above expression
would evaluate to true. 
javascript not require defined the data type
# Logical operators(||, &&,! )
this operators 
this operator processed from left to right
example 
if(x==0&&y==1){
code.....}
if x==0 equle true ...>go to rigtht side if y==1 equl  true the end result equl true execute the condition

if x==0 equle false  ...>Get out of the condition
if x==0 equle true ...>go to rigtht side if y==1 equl  false the end result equl false  Get out of the condition
[Logical operators](https://cnx.org/resources/0d6b87c996be8ae6d0efc70c073db6c59a8ce817/scr0360-02.jpg)





