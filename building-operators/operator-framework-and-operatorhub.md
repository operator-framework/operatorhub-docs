# Using-Operator-Framework

## Using the Operator Framework

The Operator Framework is a family of tools and capabilities to deliver on the customer experience described above. It’s not just about writing code. Testing, delivery, and updating Operators are just as important. The Framework components consists of open source tools to tackle these problems:

* [**Operator SDK**](https://github.com/operator-framework/operator-sdk) - build, test and package Operators
* [**Operator Lifecycle Manager**](https://github.com/operator-framework/operator-lifecycle-manager) - controls the install/upgrade/RBAC of Operators on a cluster
* [**Operator Metering**](https://github.com/operator-framework/operator-metering) - collecting operational metrics about Operators on the cluster for Day 2 management and aggregating usage metrics

In addition to the Operator Framework, OperatorHub provides an interface for discovering, installing, and managing Operators. There are two flavors of OperatorHub as follows:

* OperatorHub.io - [OperatorHub.io](https://operatorhub.io/) is a community registry designed to make it easy for Kubernetes owners to find Operator based services. It does not include OpenShift certified Operators.
* OpenShift OperatorHub - A registry of Operators embedded within every OpenShift 4 cluster. This registry includes all community Operators that have been tested with OCP from [OperatorHub.io](https://operatorhub.io/) as well as all OpenShift certified Operators.

As an partner, you can work with Red Hat to ensure that the same set of images are used to publish to both [OperatorHub.io](https://operatorhub.io/) and OpenShift OperatorHub. It is just that the submission process for each is different, as described later in this document.

All these tools/components are designed to be composable, so you can use any that are useful to you.

