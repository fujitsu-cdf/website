
---
title: "Welcome to Tekton"
linkTitle: "Documentation"
weight: 20
menu:
  main:
    weight: 20
---

Tekton is an open-source cloud native CI/CD (Continuous Integration and
Delivery/Deployment) solution. It allows developers to build, test, and
deploy across destinations using a Kubernetes cluster of their own.

The Tekton project, at this moment, consists of 4 components:

* [Pipelines](/docs/pipelines): Basic building blocks (tasks and pipelines) of a CI/CD workflow
* [Triggers](/docs/triggers): Event triggers for a CI/CD workflow
* [CLI](/docs/cli): Command-line interface for CI/CD workflow management
* [Dashboard](/docs/dashboard): General-purpose, web-based UI for Pipelines

Pipelines, of all the components, provides the core functionality of
Tekton and sets the foundation for the other components.   
Installation of Triggers, CLI, and Dashboard is optional; you may set them up in conjunction
with Pipelines to create the CI/CD workflow that works best for your team
and project.

![Pipeline](/docs/concepts/concept-tasks-pipelines.png)


{{% alert title="Note" color="success" %}}

Tekton provides a number of interactive tutorials at [tekton.dev/try](/try)
for developers to get hands-on experience with the project.

{{% /alert %}}
