<!-- CCS -->
  -cascading style sheet
-There are 3 away to apply in css
   -Inline(same line ma css use garne.)
   -internal(same file ma head tag ma css dine)
   -external(another file ma css lakhane and link with link tag in head tag in html file.)

   <!-- Selector -->

   1.Universal selector
     -* used to select all the document of a page.
   2.Element selector
    -It is a tag selector tag are used to select 
     -Eg. div, h1, p

   3.class selector
    - dot is used to select , we give same class name for different tag 
   4.Id selector
      -It used only one name in entire page.
   5.Group selector
     -multiple element select at on one time 
       Eg. div,v1,P{

       }
    6.descet selector
           div p {
             color: red;
              }      
         


<!-- Unit System -->
  -There are two types of unit system
   1.Absolute
     -not depend on others
      Eg.px,cm ,inch
         -96px = 1 inch

    2.Relative 
      - depend on parent 
      Eg. % ,vw,vh,em,rem,     

     --em---
       -related to font size   
        -eg, if parent font size is 20px then child has 2em means  
          20*2=40px

      --rem---
        -takes the root ko  relative apply hunx. html is root tag of html.
         -By default font size of html is 16px, 1rem=16px

     ---vw--   
       -view port  width   
           -100vw=100%

        --view port height (vh) ---



 

<!-- Color System -->
  -There are 5 ways to give color properties in css
    1.name
       -eg.red.
    2.rgb(red green blue)  range(0-255)
    3.rgba(red green blue with oppacity)  a=0-1
    4.hashcode(0-f)
       -Eg. #345533

    5.hsl(hue saturation lightness)   
       -eg.hsl(0,30%,40%)
            -hue ma degree and baki 2 wata ma % dine..
