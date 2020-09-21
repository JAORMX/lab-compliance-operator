---
Title: Operator Introduction
PrevPage: ../index
NextPage: 02-installation
---

Compliance Operator
===================

The Compliance Operator lets administrators describe the desired compliance
state of a cluster and provides them with an overview of gaps and ways to
remediate them.

It assesses compliance of both the Kubernetes part of OpenShift as well
as the nodes running the cluster. Under the hood, the Compliance Operator
uses OpenSCAP, a NIST-certified tool, to scan and enforce security policies
provided by the content.

It also provides the means to continuously evaluate your cluster. Thus
making sure that the cluster will stay in compliance, and you'll always
have recent scan results to show to your auditor.

[Let's install the operator!](02-installation.md)