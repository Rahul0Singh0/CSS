# units in css
  CSS has several different units for expressing a length. Many CSS properties take "length" values, such as width, margin, padding, font-size, etc. Length is a number followed by a length unit, such as 10px, 2em, etc.
  Example:
    font-size: 60px;
    font-size: 25px;
    line-height: 50px;
  1. Absolute Lengths: these units are fixed and a length expressed in any of these will appear as exactly that size.
  example: pexel(px), inches(in), Points(pt)
  2. Relative Lengths: these units specify a length relative to another length property. Relative length units scale better between different rendering medium.
  example: em, rem(root), percentage(%)

### pixel : 
    px is an absolute unit of measurement in css, representing the smallest unit of screen space.
### percentage : 
    % are relative units based on the parent element's size of the containing block.

### Em(em) :
    em is a relative unit that is calculated based on the font size of the parent element.

### root Em (rem) :
    rem is also a relative unit like em, but it's based on the font size of the root(html)

## Interview Que.

## Q1. What is the main difference between em and rem units in CSS?

## Q2. How does using rem units in your CSS benefits a responsive web design?
       we know that rem is relative unit and it's measurement depends on root element

## Q3. Can you explain how the font-size property in em-units works when nested within parent elements with different font sizes?
.parent {font-size: 10px;}
li {font-size: 2.75em;}