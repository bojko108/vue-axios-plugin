# Vuejs plugin for emitting events

# Installation

```
yarn add bojko108/vue-axios-plugin
```

# How to use

Add it to Vue:
```js
import Vue from 'vue';
import AxiosPlugin from 'vue-axios-plugin';

Vue.use(AxiosPlugin);
```

And in your components:
```js
export default {
  name: "MyComponent"
  created() {
    // make HTTP requests using:
    this.$axios...
  }
}
```

## License

vue-axios-plugin is [MIT](https://github.com/bojko108/vue-axios-plugin/tree/master/LICENSE) License @ bojko108
