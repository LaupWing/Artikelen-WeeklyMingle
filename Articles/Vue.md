# Why use VUE.js?
![vue.js](https://miro.medium.com/max/1200/1*-PlqbnwqjqJi_EVmrhmuDQ.jpeg)
## What is VUE.js
Vue.js is one of the biggest javascript frameworks until this date. The other big javascript frameworks are React and Angular. Among these frameworks Vue is by far the easiest to learn but also very powerful. The reason why people use framework is, is because it speeds up the building proces a lot.

## Why use VUE.js
But why should you learn Vue above the other frameworks? Short answer is: because Vue.js is a combination of all the good aspects of the most popular frameworks: Angular and React. If Angular and React had a child it will be called Vue.js (but with all the good aspects inherited).
![kind](https://www.healthyfood.com/wp-content/uploads/2017/01/Should-your-child-be-dairy-free-iStock_64414757-500x489.jpg)
Its also very easy to use, compared to Vue and Angular people usually recommend Vue.js as good introduction to frameworks if you have never used them before in your projects.

## How does vue work?
Vue works in components, just like all other frameworks, the big difference is that each Vue component are stored in their own file and all the styling and javascript will be contained within this file. This way it is very easy to keep your project organized. And that is also one of the big reasons why you should use Vue. Vue makes it very easy to keep your code organized and contained within one file! Vue has his own way of preventing styling and javascript code from collision with each other. A little example is that you can scope your styling, so that the styling will be only applied to that specific component/file.Each vue component had three main parts:Template,Script and Styling'

```javascript
    <template>
        <div class="">

        </div>
    </template>

    <script>
    export default {
        name: 'Article1',
        data(){
            return{
            }
        },
        methods:{
        }
    }
    </script>

    <style scoped>
    </style>
```
### 1. Template
The first part of a vue component is the html. All the elements within that component will be contained within this `template` tag. Within that template that you may only use one div/container. This is because a component needs a wrapper around it and it would be illogical to use 2 wrappers for one component. In this template you can also use your components as a basic html element. For example if you have a navigation component you will invoke this component as <navigation/>. It is easy like that! You can also have some expressions in this section of the Vue component, but more of that in the next article!
```javascript
    <template>
        <div class="body">
            <navigation/>
        </div>
    </template>
```