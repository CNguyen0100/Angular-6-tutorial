# Class Bindings
3 ways
a. The standard property Bindings
b. The special class Bindings
c. The ngClass directive

## a.
```html
<div [class]="expr"></div>
```

This binding evaluates the expression and uses the result to replace any existing class membership

## b.
```html
<div [class.myClass]="expr"></div>
```
This bindings evaluates the expression and uses the result to set the element's membership of myClass

## c.
<div [ngClass]="map"></div>

This binding sets class membershipof multiple classes using the data in a map object
