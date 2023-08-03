# CSS
## how to organize things 

1. Create root
    - color, size in em,

2. Utility Classes
    - primary color
    - secondart color
    - font size
    - font weight
    - padding
3. General Classes


## using var(--font-size, default)
var(--font-size, 1em)




## It will affect all the child element except first one
.flow > * + + {
    outline: 5px solid cyan;
}

*  or instead of > * + * {}     you can use 
:where(.flow > :not(:first-child)) {}
or
.flow > :not(:first-child)        it will override previous css

when using :where() it doesn' override previous css






