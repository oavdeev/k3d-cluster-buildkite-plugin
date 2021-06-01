# Kind cluster buildkite plugin [alpha]

This will set up and tear down a [kind](https://github.com/kubernetes-sigs/kind/)
cluster for a buildkite step.

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - oavdeev/kind-cluster-buildkite-plugin#v0.1:
```
