# Helm Chart Hooks
This repo is contains an example with `pre-delete` hooks, it meaning is when you want to delete helm chart,
`pre-delete` event triggerde pods with integrated this chart.

### Annotation of Hook
You can check the hooks notation in <b>templates</b> directory.

```
  annotations:
    "helm.sh/hook": "pre-delete"
```

Detailed documentation : <a href="https://helm.sh/docs/topics/charts_hooks/">Chart Hooks</a>