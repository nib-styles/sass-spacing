# @nib-styles/sass-spacing

SASS mixins for margins and paddings. Plus a compiled set of responsive margin and padding classes for non-sass projects. 

## Installation

NPM:

    npm install --save @nib-styles/sass-spacing

Component:

    component install nib-styles/sass-spacing

## Usage

### Using the compiled classes

SCSS:

    @import "@nib-styles/sass-spacing/compiled";

HTML:

    <div g-md="p3 mb3">
      20px padding and 20px margin-bottom for >=md breakpoint
    </div>
    
    <div g-xs="p2" g-sm="p4" g-lg="p0">
      10px padding <sm, 40px padding <lg, 0px padding above
    </div>
    
    <div g-xs="px5 mb3" g-sm="p4">
      60px padding left/right and 20px margin bottom <sm, 20px padding above
    </div>

## Breakpoints

See [@nib-styles/sass-breakpoints](https://github.com/nib-styles/sass-breakpoints).
 
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
 - mx - margin-left & margin-right
 - my - margin-top & margin-bottom
 - mt - margin-top
 - mb - margin-bottom
 - ml - margin-left
 - mr - margin-right

## Padding Options
 
 - p - padding
 - px - padding-left & padding-right
 - py - padding-top & padding-bottom
 - pt - padding-top
 - pb - padding-bottom
 - pl - padding-left
 - pr - padding-right
