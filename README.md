## Contents:
1. [Overview](#overview)
2. [Prerequisites](#prerequisites)


****
## Overview

This repository contains a sample Node-Red Red Hat certified Operator that helps you understand how to prepare your Operator bundle for onboarding to IBM Cloud. 
 

## Prerequisites

Make sure that you complete the following prerequisites before you begin:

1. Verify that you're using a Pay-As-You-Go or Subscription account. See [Viewing your account type](https://cloud.ibm.com/docs/account?topic=account-account_settings#view-acct-type) for more details.
1. Use the [latest supported Operator-SDK version](https://docs.openshift.com/container-platform/4.5/operators/operator_sdk/osdk-getting-started.html) to create your Operator. 
1. [Create your Red Hat OpenShift cluster](https://cloud.ibm.com/docs/openshift?topic=openshift-getting-started). 
1. [Upload your Operator bundle and application images to IBM Cloud Container Registry](https://cloud.ibm.com/docs/Registry?topic=Registry-getting-started).
1. Verify that you're assigned the correct roles. For more information, see [Assigning access to account management services](https://cloud.ibm.com/docs/account?topic=account-account-services&interface=ui) and [Managing access to resources](https://cloud.ibm.com/docs/account?topic=account-assign-access-resources&interface=ui).
   * Administrator on all account management services and all IAM services
   * Editor on the catalog management service
   * Editor on the IBM Cloud Container Registry service
   * Administrator on the Red Hat OpenShift cluster
   * Editor on the software instance service

Make sure that you use the same account to access IBM Cloud Container Registry and to create the Red Hat OpenShift cluster.

|Profile|ID|
|NIST|SC|
|NIST|AC|
