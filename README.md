Lab - Compliance Operator
=========================

This workshop provides an introduction to deploying a the
[compliance-operator](https://github.com/openshift/compliance-operator)
and using it to evaluate the state of compliance with a benchmark.

Agenda
------

The agenda for the workshop looks as follows:

### Creating your first scan

* Browsing profiles
* Browsing rules
* Creating ScanSettingBinding
* Tracking scan progress
* Browsing results
* Fetching raw results

### Remediate

 * Edit one remediation, apply
 * Apply a couple of remediations
 * Auto-applying remediations

### Tailoring profiles

 * Basic tailoring - disabling rules

### Troubleshooting

 * General tips
 * Useful labels
 * Troubleshooting OpenSCAP

What to expect?
---------------

A cluster will be provided for you as well as a link to download the relevant CLI client.

Prerequisites
-------------

### Kubernetes/OpenShift

Basic knowledge of Kubernetes or OpenShift is required for this lab. The
resources in [learn.openshift.com](https://learn.openshift.com/) are quite
useful. We would recommend starting with the labs in the
[Using OpenShift](https://learn.openshift.com/using-the-cluster/) section.

### OpenScap/Content writing
While it is not mandatory that you have knowledge of using OpenSCAP or writing
content, it would surely help you understand the bigger picture.

There is a [self-paced lab](https://github.com/RedHatDemos/SecurityDemos/tree/master/2019Labs/CustomSecurityContent/documentation)
that you can follow to learn about OpenSCAP and how to write content. We highly
recommend it.

Ready?
======

[Start the lab](workshop/content/index.md)