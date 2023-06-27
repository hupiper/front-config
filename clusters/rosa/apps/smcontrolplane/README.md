# OpenShift ServiceMesh - Control Plane

Installs the Control Plane component of OpenShift ServiceMesh.

## Prerequisites

First, install the following operators in your cluster:

- [Openshift Elasticsearch Operator](../../elasticsearch-operator)
- [Red Hat Openshift Jaeger Operator](../../jaeger-operator)
- [Kiali Operator](../../kaili-operator)
- [OpenShift ServiceMesh Operator](../operator)

Review the [Service Mesh Install](https://docs.openshift.com/container-platform/4.13/service_mesh/v2x/installing-ossm.html) documentation on ROSA for information on installation prerequisites.