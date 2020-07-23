Necessidade: Importar uma bibliteca do Vue no Nuxt
Exemplo:

```js
// /plugins/vue-tooltip.js
import Vue from 'vue'
import VTooltip from 'v-tooltip'

Vue.use(VTooltip)
```

````js
// no nuxt.config.js
export default {
  plugins: ['@/plugins/vue-tooltip.js']
}
```