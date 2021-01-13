# Class 14

## Transforms



###  Transform Syntax#transform-syntax

      div {
     -webkit-transform: scale(1.5);
        -moz-transform: scale(1.5);
         -o-transform: scale(1.5);
            transform: scale(1.5);
     }


**property includes multiple vendor prefixes to gain the best support across all browsers*

### 2D Transforms

Two-dimensional transforms work on the x and y axes

1. 2D Rotate
2. 2D Scale
3. 2D Translate
4. 2D Skew


### CSS3 TRANSITIONS

1. Fade in

![img](https://th.bing.com/th/id/OIP.540FC_QTp3EUyQhkpbX3MAHaEo?pid=Api&rs=1)

2.  Change color

         .color:hover
        {
           background:#53a7ea;
         }




3. Grow & Shrink


use CSS3’s transform to enlarge.

4. Rotate elements

       .rotate:hover
       {
          -webkit-transform: rotateZ(-30deg);
           -ms-transform: rotateZ(-30deg);
            transform: rotateZ(-30deg);
        }
        
        
5. Square to circle
    
          .circle:hover
       {
          border-radius:50%;
           }
           
           
           
6.  3D shadow
      
      **adding a box shadow, and then moving the element on the x axis using the transform and translate properties**
      
 7.  Swing
      
      **animation simply moves the element left and right**
      
 8.  Inset border

