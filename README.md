# folio-helm - Helm charts modules repository

## Introduction

FOLIO Helm charts modules repository.

Contains Helm sources and Helm packages repository.
Repository URL https://sul-dlss.github.io/folio-helm/
gh-pages branch is configured as GitHub pages.

## Creating Helm package from source

Build package with:
```
  helm package <MODULE_NAME> -d ./charts
```
Update repository index
```
  helm repo index . --url https://sul-dlss.github.io/folio-helm/
```

Commit and push changes to GitHub
