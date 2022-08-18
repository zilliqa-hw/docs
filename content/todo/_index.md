---
title: TODO
geekdocCollapseSection: false
---

## TODO

### EKS

- The standard Helm charts could be organized out into a Terraform module for
DRY.

### Application CI

- The review-environment implemented. When a PR is created, a temporary
namespace should be created that where the application is deployed and after 
the merge, cleaned up.