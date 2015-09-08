# @nib-styles/sass-spacing

SASS mixins for margin and padding. Plus a compiled set of responsive margin and padding classes.

## Installation

NPM:

    npm install --save @nib-styles/sass-spacing

Component:

    component install nib-styles/sass-spacing

## Usage

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

See [sass-spacing](https://github.com/digitaledgeit/sass-spacing) for more in-depth usage information.

## Sizes

 - 0 - 0
 - 1 - 5px
 - 2 - 10px
 - 3 - 20px
 - 4 - 40px
 - 5 - 60px
 - 6 - 80px

## Breakpoints

See the [@nib-styles/sass-breakpoints](https://github.com/nib-styles/sass-breakpoints) package for a list of available breakpoints.
 