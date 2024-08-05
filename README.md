# Add new manifest

```bash
helm lint source/manifest_name/*
helm package source/manifest_name/* 
helm repo index --url https://puhhh.github.io/pages-helm-repo/ .
```