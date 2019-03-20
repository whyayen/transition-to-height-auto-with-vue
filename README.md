# Transition to height auto with Vue.js

This is a project for transition element which height is auto.

## Example
[Transition to height auto with Vue.js](https://markus.oberlehner.net/blog/transition-to-height-auto-with-vue/)

## Installation

#### NPM
```bash
npm install --save vue-transition-expand
```

## Import

#### Globally
```javascript
import TransitionExpand from 'vue-transition-expand'
import 'vue-transition-expand/dist/vue-transition-expand.css'

Vue.use(TransitionExpand)
```

#### SFC

```javascript
import {TransitionExpand} from 'vue-transition-expand'
import 'vue-transition-expand/dist/vue-transition-expand.css'

export default {
  name: 'HelloWorld',
  components: {
    TransitionExpand
  },
  data () {
    return {
      show: false,
      ...
    }
  },
  ...
}
```

## Example
```
<transition-expand>
      <div v-if="show" class="box">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </div>
      <button @click="show = !show">Click !</button>
</transition-expand>
```

## About

### Author

Markus Oberlehner  
Website: https://markus.oberlehner.net  
Twitter: https://twitter.com/MaOberlehner

### License

MIT
