# what-l-learned-week-7

## calling function as a value

Function as values can be called within a function. ie:


```
const threeFuncs = function(thatFirstFunction, thatSecondFunction, thatThirdFunction) {
  return thatThirdFunction(thatSecondFunction(thatFirstFunction()));
}
```


## DOM manipulation

* how to use Query Selector all. - document.querySelectorAll('selector CSS-likeStyle') ; choose all selectors in that tag , class or id
* you can use loops to achieve results looping through querySelectorAll
* we can pass functions within function as values
* .addEventListener - is a method to call upon based on action in our case a mouse click or hover to achieve a result of CSS actions using DOM calls.

## Midterms

They are hard.
