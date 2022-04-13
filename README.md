https://gabrieltanner.org/blog/collecting-prometheus-metrics-in-golang

Use this for generating load:

```
hey -z 5m -q 5 -m GET -H "Accept: text/html" http://127.0.0.1:9000
```# go-prom
