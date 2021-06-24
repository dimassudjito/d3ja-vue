# d3ja-vue

d3ja-vue is a vue component library for data visualization based on [D3.js](https://www.npmjs.com/package/d3).
For now, most of the components are adaptation of Mike Bostock's D3 demonstration in [Observable notes](https://observablehq.com/@mbostock).

---

# Installing

```
npm i d3ja-vue
```

In your vue file, import the desired component:

```
import { TreeOfLife } from 'd3ja-vue'
```

and registered it as a component:

```
components: {
    TreeOfLife
}
```

---

# TreeOfLife

| Props | Description                                     |
| ----- | ----------------------------------------------- |
| tree  | a string of newick format to represent the tree |
