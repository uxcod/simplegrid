# simplegrid
LESS simple grid optmised for PHP compilation (no js)

###  Usage:

__Columns with Gutters__

.col(1/3, @gutter: 2, @cycle: 3)


__Columns without Gutter__

.span(1/2, @gutter: 0)


```css
.grid {
    margin-bottom: 20px;
}
.grid > .col-1-1 {
    .col(1);
}
.grid > .col-1-2 {
    .col(1/2);
}
...
```
