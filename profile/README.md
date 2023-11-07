
## Packages

| Name | Description |
| ---- | ----------- |
| [`torch-relay`](https://github.com/balbasty/torch-relay) | A stable API that works across PyTorch versions |
| [`jitfields`](https://github.com/balbasty/jitfields) | C++/CUDA utilities compiled just-in-time with pytorch bindings |
| [`nitorch-fastmath`](https://github.com/nitorch/nitorch-fastmath) | Math utilities |
| [`nitorch-interpol`](https://github.com/nitorch/nitorch-interpol) | Spline interpolation |
| [`nitorch-solvers`](https://github.com/nitorch/nitorch-solvers) | Quadratic solvers for dense vector fields |
| [`nitorch-io`](https://github.com/nitorch/nitorch-io) | A tensor-like class for on-disk data in different formats |
| [`nitorch-core`](https://github.com/nitorch/nitorch-core) | Miscelaneous low-level utilities |
| [`nitorch-plot`](https://github.com/nitorch/nitorch-plot) | Plotting utilities |
| [`nitorch-cli`](https://github.com/nitorch/nitorch-cli) | Command-line interface engine |
| [`nitorch-register`](https://github.com/nitorch/nitorch-register) | Image registration |
| [`nitorch-bayes`](https://github.com/nitorch/nitorch-bayes) | Bayesian modeling |
| [`nitorch-qmri`](https://github.com/nitorch/nitorch-qmri) | Quantitative MRI |
| [`nitorch-nn`](https://github.com/nitorch/nitorch-nn) | Neural networks |

## Dependency tree

| depend(ence→)(↓ee) | `jitfields` | `fastmath` | `interpol` | `solvers` | `io` | `core` | `plot` | `cli` | `register` | `bayes` | `qmri` | `nn` |
| ------------------ | ----------- | ---------- | ---------- | --------- | ---- | ------ | ------ | ----- | ---------- | ------- | ------ | ---- |
| `jitfields`        | ⌀ |   |   |   |   |   |   |   |   |   |   |   |
| `fastmath`         | ☑ | ⌀ |   |   |   |   |   |   |   |   |   |   |
| `interpol`         | ☑ |   | ⌀ |   |   |   |   |   |   |   |   |   |
| `solvers`          | ☑ |   |   | ⌀ |   |   |   |   |   |   |   |   |
| `io`               |   |   |   |   | ⌀ |   |   |   |   |   |   |   |
| `core`             | ⚀ | ☑ | ☑ |   |   | ⌀ |   |   |   |   |   |   |
| `plot`             | ⚀ | ☑ | ☑ |   |   | ☑ | ⌀ |   |   |   |   |   |
| `cli`              |   |   |   |   |   |   |   | ⌀ |   |   |   |   |
| `register`         | ⚀ |   | ☑ | ☑ | ☑ | ☑ |   |   | ⌀ |   |   |   |
| `bayes`            | ⚀ | ☑ |   |   |   | ☑ |   |   |   | ⌀ |   |   |
| `qmri`             |   |   |   |   |   |   |   |   |   |   | ⌀ |   |
| `nn`               | ⚀ | ☑ | ☑ |   | ☑ | ☑ |   |   | ☑ | ☑ |   | ⌀ |
