



1. The build should trigger as soon as anyone in the dev team checks in code to master branch.

Login to https://dev.azure.com/ 
Create Pipeline 




```yaml
# specific branch build with batching
trigger:
  batch: true
  branches:
    include:
    - master
```




