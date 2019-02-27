# Base Images

Red Hat is serious about security for Operators and using a Red Hat supported base image is required for inclusion in the OpenShift OperatorHub. RHEL and OpenShift have many security certifications, which require RHEL usage throughout the entire stack for compatibility. As a partner you have access to licenses for OpenShift and RHEL for testing.

Before 2019, redistributing a RHEL base container image broadly was not permitted by Red Hat’s subscription and trademark terms. The new Red Hat Universal Base Image \(UBI\) now delivers the power of RHEL to container images, enabling you to use any CI tool to build your Operator, publish your Operator images within any registry and rely on Red Hat support on container platforms supported by Red Hat, such as Red Hat OpenShift.

Community Operators may use any base image, but it is highly recommended to use the Red Hat Universal Base Image to provide industry-leading security maintenance.

In order for your operator to be Red Hat Certified \(described below\), the Operator and all of its associated images, must use a Red Hat supported based image \(UBI or otherwise\) and successfully pass Red Hat’s Container Certification workflow. Certified containers can optional be distributed from the Red Hat Connect container registry, which ensures that Red Hat (and you by extension) can comply with legal export compliance. Below is an example of an Operator that uses 4 total images:

![](../../.gitbook/assets/svhd_gvohzglhorjvg5btmq.png)

Each of the 4 containers shown above must also remain published and accessible forever, so that OpenShift clusters can continue to start these workloads as Kubernetes moves them around the cluster.

