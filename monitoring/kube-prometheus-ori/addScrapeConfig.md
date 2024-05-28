```
k create secret generic additional-scrape-configs --from-file=prometheus-additional.yml --dry-run=client -oyaml > additional-scrape-configs.yaml
```

```
k apply additional-scrape-configs.yaml
```