# Cascading Style Sheets

## Basics
### Import
```
@import "other.css";
```
### Selector
```css
//select all
* {
  font-family: "Arial Black', sans-serif"
}

//select by id
#myId {

}

//div>span>a
div span a {

}

//div OR span OR a
div, span, a {

}
```
### Unit Types
- Pixels
- Points: 72 points = 1 inch
- Ems: current font size
- Percent: current font size is equal to 100%

## Box Model
- Margin: space outside the element
- Border
- Padding: space inside the element