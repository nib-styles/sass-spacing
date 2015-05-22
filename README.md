# sass-spacing
SASS mixins for margins and paddings. Plus a compiled set of responsive margin and padding classes for non-sass projects. 

To be used in conjunction with [digitaledgeit/css-grid](http://github.com/digitaledgeit/css-grid)

## Usage

     <div g-md="p3 mb3"> <!-- 20px padding and 20px margin-bottom for >=569px -->
       <div g-xs="p2" g-sm="p4" g-lg="p0">10px padding up to 568px, 40px padding up to 1003px, 0 padding above</div>
       <div g-xs="px5 mb3" g-sm="p4">60px padding left/right and 20px margin bottom up to 568px, 20px padding above</div>
     </div>

## Breakpoints
Breakpoints are referenced with the prefix `g-` in html.

 - xs - target devices >=0px
 - sm - target devices >=569px
 - md - target devices >=769px
 - lg - target devices >=1004px
 
## Default Pixel Sizes

 - 0 - 0
 - 1 - 5px
 - 2 - 10px
 - 3 - 20px
 - 4 - 40px
 - 5 - 60px
 - 6 - 80px
 
## Margin Options

 - m - margin
 - mx - margin left & right
 - my - margin top & bottom
 - mt - margin top
 - mb - margin bottom
 - ml - margin left
 - mr - margin-right

 
 ## Padding Options

 - p - padding
 - px - padding left & right
 - py - padding top & bottom
 - pt - padding top
 - pb - padding bottom
 - pl - padding left
 - pr - padding right
