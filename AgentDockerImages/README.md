# Agent Docker Images

# Each ADO `job` runs on an `agent`.

A catch-all agent capable of building any Viz-Tech project is provided as well as
granular framework specific images.

By providing a base image w/ application frameworks compilers already installed,
we can ensure that ALL vizient software is being build with the same version of software.
No one gets left behing and errors are caught up front.

### Package Build & Deploy Tools, Dependencies, and Agent Software:

- Consult full stack guild for this list.
- angular, node, dotnet, pulumi, java

### Create a docker file for each agent type or configuration

- We should have a catch all agent as well as granular framework specific agents.


### Build Docker Images

- This should be an automated step executed via a pipeline. We can parameterize the framework versions.

### Test Docker Images

### Push Docker Images to a Registry

- Tag your image with the appropriate registry path, name and version.

### Update Kubernetes Configuration

- In the k8s deployment configuration, speficy the Docker image you've created. (this is part of the later steps, `k8s Deployments` and `User Agent Pool In Piplines`)
