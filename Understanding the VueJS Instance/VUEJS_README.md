- Vue.js instanace is like a middle man between Business logic and DOM
- el, data, methods, computed, watchers are properties in Vue.js Instance


## Multiple Vue Instances:

- Multiple instances cannot share scope of another instance you can't access
  property of another instance into previous one.

- Considered instance as a container they both are seperate and hav individual 
  all properties.
  
```js
 <div id="app1"></div>

     const app = new Vue({
            el:"#app1",
            data:{
            }
        });

<div id="app2"></div>
        const app = new Vue({
            el:"#app2",
            data:{
            }
        });

```