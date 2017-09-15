# css-lite-utils
Set of CSS utility classes for repeatedly writing basic styles.

Inspired by [Medium_CSS_Style_Guide](https://gist.github.com/cuibonobo/16f555c0047ab80044cf).

# Getting Started
#### Use `LESS` version
```
npm install --save css-lite-utils
```

**_your-main.less_**
```
@import "<PROJECT-ROOT>/node_modules/css-lite-utils/lib/main.less"
```
#### Use compiled CSS file
Copy `dist/css-lite-utils.min.css` to your static asset folder.

**_your.html_**
```
<link href='<PATH>/css-lite-utils.min.css' rel='stylesheet' type='text/css'> 
```

# Classes

#### position
- `.u-positionRelative`
- `.u-positionAbsolute`

#### display
- `.u-displayNone`
- `.u-displayBlock`
- `.u-displayInlineBlock`
- `.u-displayInline`
- `.u-displayListItem`
- `.u-displayTable`
- `.u-displayTableRow`
- `.u-displayTableCell`

#### text-align
- `.u-textAlignLeft`
- `.u-textAlignRight`
- `.u-textAlignCenter`

#### vertical-align
- `.u-verticalAlignBaseline`
- `.u-verticalAlignBottom`
- `.u-verticalAlignMiddle`
- `.u-verticalAlignTop`

#### float
- `.u-floatLeft`
- `.u-floatRight`

#### margin
Size is 0px - 50px incrementing up by 5px
- `.u-margin0`, `.u-margin5`, ... , `.u-margin45`, `.u-margin50`
- `.u-marginTop0`, `.u-marginTop5`, ... , `.u-marginTop45`, `.u-marginTop50`
- `.u-marginBottom0`, `.u-marginBottom5`, ... , `.u-marginBottom45`, `.u-marginBottom50`
- `.u-marginLeft0`, `.u-marginLeft5`, ... , `.u-marginLeft45`, `.u-marginLeft50`
- `.u-marginRight0`, `.u-marginRight5`, ... , `.u-marginRight45`, `.u-marginRight50`

#### padding
Size is 0px - 50px incrementing up by 5px
- `.u-padding0`, `.u-padding5`, ... , `.u-padding45`, `.u-padding50`
- `.u-paddingTop0`, `.u-paddingTop5`, ... , `.u-paddingTop45`, `.u-paddingTop50`
- `.u-paddingBottom0`, `.u-paddingBottom5`, ... , `.u-paddingBottom45`, `.u-paddingBottom50`
- `.u-paddingLeft0`, `.u-paddingLeft5`, ... , `.u-paddingLeft45`, `.u-paddingLeft50`
- `.u-paddingRight0`, `.u-paddingRight5`, ... , `.u-paddingRight45`, `.u-paddingRight50`

#### width & height
Size is 5% - 100% incrementing up by 5%
##### width
- `.u-width5Perc`, `.u-width10Perc`, ... , `.u-width95Perc`, `.u-width100Perc`
- `.u-maxWidth5Perc`, `.u-maxWidth10Perc`, ... , `.u-maxWidth95Perc`, `.u-maxWidth100Perc`
- `.u-minWidth5Perc`, `.u-minWidth10Perc`, ... , `.u-minWidth95Perc`, `.u-minWidth100Perc`
##### height
- `.u-height5Perc`, `.u-height10Perc`, ... , `.u-height95Perc`, `.u-height100Perc`
- `.u-maxHeight5Perc`, `.u-maxHeight10Perc`, ... , `.u-maxHeight95Perc`, `.u-maxHeight100Perc`
- `.u-minHeight5Perc`, `.u-minHeight10Perc`, ... , `.u-minHeight95Perc`, `.u-minHeight100Perc`

#### font
Size is 4px - 40px incrementing up by 4px
- `.u-fontSize4`, `.u-fontSize8`, ... , `.u-fontSize36`, `.u-fontSize40`
- `.u-fontWeightBold`

#### responsive show-hide
##### Screen types
- Mobile: `max-width: 767px`
- Tablet: `min-width: 768px` and `max-width: 991px`
- Computer: `min-width: 992px`
##### Classes
- `.u-computerOnly`: Only displayed on computer
- `.u-tabletOnly`: Only displayed on tablet
- `.u-mobileOnly`: Only displayed on mobile

##### Combination:
- `.u-computerOnly.u-tabletOnly`: only displayed on computer and tablet
- And so on with `.u-computerOnly.u-mobileOnly`, `.u-tabletOnly.u-mobileOnly`, ...

#### Misc classes
Some common classes
- `.u-clearBoth`
- `.u-cursorPointer`
- `.u-textTransformUppercase`
- `.u-textTransformLowercase`
