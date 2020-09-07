Lab - Compliance Operator
=========================

This workshop provides an introduction to deploying a the [compliance-operator](https://github.com/openshift/compliance-operator) and using it to evaluate the state of compliance with the E8 benchmark.

Note that the `cluster-admin` role is required in order to install the operator

Installation
------------

* OLM installation steps

Create your first scan
----------------------

* browsing profiles
* browsing rules
* Creating ScanSettingBinding
* tracking scan progress
* Browsing results
    * check results are labeled
* Fetch raw results

Remediate
---------

 * edit one remediation, apply
 * pause the pool if applying multiple
 * apply a couple
 * unpause
 * show autoApply
 * rescan


Tailor the profile
------------------

 * create a TailoredProfile that disables some rules
 * run the scan again, show they they didn't run (or are not evaluated?)

Troubleshooting
---------------

 * add the debug flag
 * see that the pods are still around
 * oc log-ing the openscap container shows the logs (maybe combine with using a single rule only?)

 Creating custom rules (new content)
 -----------------------------------

* 