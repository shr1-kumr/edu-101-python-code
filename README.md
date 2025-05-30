# Code Repository for Temporal 101 (Python)
This repository provides code used for exercises and demonstrations
included in the Python version of the 
[Temporal 101](https://learn.temporal.io/courses/temporal_101) 
training course.

It's important to remember that the example code used in this course was designed to support learning a specific aspect of Temporal, not to serve as a ready-to-use template for implementing a production system.

For the exercises, make sure to run `temporal server start-dev --ui-port 8080 --db-filename clusterdata.db` in one terminal to start the Temporal server. For more details on this command, please refer to the `Setting up a Local Development Environment` chapter in the course. Note: If you're using the Codespaces environment to run this exercise, you can skip this step.

## Hands-On Exercises

Directory Name                | Exercise
:---------------------------- | :----------------------------
`exercises/hello-workflow`    | [Exercise 1](exercises/hello-workflow/README.md)
`exercises/hello-web-ui`      | [Exercise 2](exercises/hello-web-ui/README.md)
`exercises/farewell-workflow` | [Exercise 3](exercises/farewell-workflow/README.md)
`exercises/finale-workflow`   | [Exercise 4](exercises/finale-workflow/README.md)


## Instructor-Led Demonstrations
Directory Name                         | Description
:------------------------------------- | :----------------------------------------------------------------------------------
`demos/service-workflow`                | [Shows a Workflow that uses a microservice](demos/service-workflow)



## Examples for Self-Study
Directory Name                         | Description
:------------------------------------- | :----------------------------------------------------------------------------------
`samples/greeting`                     | [The Python function with business logic for first Workflow](samples/greeting)
`samples/retry-policy`                 | [Example of a Workflow that has a custom Retry Policy](samples/retry-policy)


## Reference
The following links provide additional information that you may find helpful as you work through this course.
* [General Temporal Documentation](https://docs.temporal.io/)
* [Temporal Python SDK Documentation](https://python.temporal.io/)
* [Python Language Documentation](https://docs.python.org/3/)


## Exercise Environment for this Course
You can launch an exercise environment for this course using GitHub Codespaces by 
following [this](codespaces.md) walkthrough.

Alternatively, you can follow 
[these instructions](https://learn.temporal.io/getting_started/python/dev_environment/) to 
set up your own Temporal Cluster with Docker Compose, which you can use as an 
exercise environment.
