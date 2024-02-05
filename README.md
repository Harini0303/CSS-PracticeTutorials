# CSS - Cascading Style Sheets

• CSS Selectors <br>
• Reset CSS & Applying styles using CSS <br>
• CSS Backgrounds <br>
• Box Model <br>
• Borders  <br>
• Fonts  <br>
• Links  <br>
• Margins  <br>
• Paddings  <br>
• Colors  <br>

<hr>
<h2>BACK GROUND PROPERTY</h2>

1.backgroun color : color name, hexadecimal, RGB, HSL

2.background-image : url(" location___     " )

3.background-reapt : no-reapt (the image will not be repted)-no repaet/repeat-default

4.background-attachment : (by default it may be scroll) fixed/scroll-default

5.background-position : let, right ,centre, lef top, lef bottom, right top, right buttom

all these 5 we can apply all these 5 in single line that is shothrend property.

6.background : color url repeat attachment position

<hr>

<h2>BORDERS</h2>

1.border-style : dotted, dashed, solid, double, groove, ridge, inset, outset, none(default)

2.border-width : px/percentage

3.border-color : name of any colors

4.border-radius : px (rounded edges)


This border style accept 4 values

<ul>
  <li>border-top-style : dased</li>
  <li>border-right-style : double</li>
  <li>border-top-style : solid</li>
  <li>border-top-style : dotted</li>
</ul>

groove, ridge, inset, outset --- these are 3D representation

also all in one property

background-style : double dased solid dotted
<pre>
1 value -all the 4 sides will that 
2 value -top and bottom , left and right
3 value -top,left and right,bottom
4 value - background-style:double dased solid dotted
  
</pre>

<hr>

<h2>FONT</h2>

<ul>
<li>font-style</li>
<li>font-weight</li>
<li>font-size</li>
<li>font-family</li>
</ul>

<b>1. font-style:</b> has 3 values
<ul>
<li>normal</li>
<li>italic</li>
<li>oblique(simlar to italic)</li> 
</ul>

<b>2. font-weight:</b> 2 values
<ul>
<li>normal</li>
<li>bold</li>
</ul>

<b>3. font-size :</b> px / pm

<b>4. font-family</b>
there no of font family
    arial, courier, serif, sans-serf
    eg: times  new roman

Shorthand property for font

<pre>
p{
font-style:italic;
font-weight:bold;
font-size:50px;
font-family:arial;
}

p{
font: italic bold 30px arial, courier, serief;
}
</pre>
<hr>
<h2>LINKS</h2>

1) a:link - unvisted link 

2) a:visited  - visted link

3) a:hover - moving cursor towards the link

4) a:active - clicks on the link

<hr>

<h2>SELECTORS </h2>

1.Tag name

2.ID Based(#)

3.class based (.)

4.universal selector(*)

5.grouping selector

<hr>

<h2>MARGINS</h2>

with respect to browser (margin)

1.margin-top

2.margin-right

3.margin-bottom

4.margin-left

<pre>
1 value - all sides
2 values-top and bottom ,left and right
3 values-top,left and right,bottom
4 values-each sides</pre>

there is also a shortand property all in one by margin : 40px 10px 30px 20px;

<hr>

<h2>PADDING</h2>

padding is with respect to borders

1.padding-top

2.padding-right

3.padding-bottom

4.padding-left





