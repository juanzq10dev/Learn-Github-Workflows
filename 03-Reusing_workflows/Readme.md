# Reusing workflows

Github docs: https://docs.github.com/en/actions/using-workflows/reusing-workflows

This is a example of a reusable workflow to build a docker image on different repos

For this example assume each .yml file is on a different repo.

## Called workflow
Is on a repo with this structure: 

```
| .github 
    | workflows
        called_workflow.yml
```

## build_image_1.yml
Is on a repo with this structure. 

``` 
| .github
    | workflows
        build_image_1.yml
| src  
| app 
| docker 
    Dockerfile
.gitignore 
```

## build_image_2.yml
Is on a repo with this structure (Note that the dockerfile is on a different path). 

``` 
| .github
    | workflows
        build_image_2.yml
| src  
| app 
Dockerfile
.gitignore 
```
