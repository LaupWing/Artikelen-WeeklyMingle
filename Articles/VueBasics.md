# Vue Basics
In this article you can find explanation of the basic synthaxes of Vue.js.

![vue.js](https://miro.medium.com/max/1200/1*-PlqbnwqjqJi_EVmrhmuDQ.jpeg)

## Template
In the template tag you can't only define your html elements but you can also assign events and statements to the elements in this part of the vue component.
```javascript 
<template>
  <div id="app"
    v-if=""
    v-show=""
    v-for=""
    v-else=""
    v-bind=""
  >
    
  </div>
</template>
```
### Vue Element Statements
In vue you can use statements in the html part. As you can see in the image above Vue statements are always written with a v dash in front of the statement you want to use.
Each statement is just like a javascript statement or operator.
* `v-if`: shows an element when the statement after the = is true
* `v-show`: shows an element when the statement after the = is true
* `v-if/v-show`: The diffrence between a v-if and a v-show is that v-if completly removes the element and a v-show just comment the html element out
* `v-else`: If the element above this element is flagged as false the v-else will show this element
* `v-for`: With v-for you can loop throught the data (data that is defined in the script part of a Vue component) and output each iteration as the elemenent that is tagged with the v-for statement. 

