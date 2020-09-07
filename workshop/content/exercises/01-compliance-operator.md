---
Title: Operator Introduction and Prerequisites
PrevPage: ../index
NextPage: 02-creating-the-cluster
---

The Compliance Operator lets administrators describe the desired compliance
state of a cluster and provides them with an overview of gaps and ways to
remediate them.

It assesses compliance of both the Kubernetes part of OpenShift as well
as the nodes running the cluster. Under the hood, the Compliance Operator
uses OpenSCAP, a NIST-certified tool, to scan and enforce security policies
provided by the content.

This workshop provides an introduction to deploying the
[compliance-operator](https://github.com/openshift/compliance-operator)
and using it to evaluate the state of compliance with the E8 benchmark.

Note that the `cluster-admin` role is required in order to install the operator
and the operator requires OpenShift 4.6 or newer.
