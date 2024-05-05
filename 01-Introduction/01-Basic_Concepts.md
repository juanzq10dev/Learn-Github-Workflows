# BASIC CONCEPTS
Github Actions Docs: https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions

## What are github actitons? 
- Continuos integration ad continous delivery platform. 
- Allows to automate build, test and deployment pipelines. 
- Github Actions work with yml files. 
- Each workflow must be in a directory named `.github/workflows` 

## Workflows
An automated proccess that runs one or more jobs. 

## Event
A specific activity that triggers a workflow. Example:
- `push`: triggers a workflow on every push

## Job
List of steps in a workflow executed on the same runner.

## Step 
A step is either a shell script that will be executed, or an action that will be run

## Action 
A custom application for the Github Acitons platform

## Runners
A server that runs the triggered workflow
