
#  **Evolux Lab**

A compact toolkit for evolutionary QUEUE networks in browsers.

---

###  install

```bash
npm i evolux-lab
```

### usage

```js
import { evolve } from "evolux-lab"

const optimal = evolve({
  population: 100,
  fitness: f => 1 - Math.abs(f.target - f.output),
})
console.log(optimal)
```

### features

* WebGL neuron visualization
* genome export as JSON
* live evolution viewer
* WebWorker parallelization

Open experimentation, documented mistakes.
Docs → [evolux-lab.dev/docs](https://evolux-lab.dev/docs)

# PR Merge: 2025-10-26 14:08:29

# PR Merge: 2025-10-26 14:08:47
