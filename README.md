# Cloud Custodian Cheat Sheet: Essential Commands for Managing Your Cloud Resources

## Introduction
Cloud Custodian is a powerful open-source tool that helps you manage and automate the governance of your cloud resources. With its extensive capabilities, it allows you to define policies to enforce security, compliance, and cost optimization across various cloud platforms. In this cheat sheet, we'll provide you with some essential Cloud Custodian commands to help you effectively manage your cloud resources.

1. **Install Cloud Custodian:**
```   
$ pip install c7n
```
2. **Check the Custodian Version:**
```
   $ custodian version
```
3. **Run Custodian Policy on Resources:**
```
   custodian run policy.yml -s /tmp
```
4. **Dry Run a Custodian Policy:**
```
$ custodian run --dryrun policy.yml
```
5. **List Affected Resources:**
```
$ custodian report --format grid policy.yml -s /tmp
```
6. **Complete List of Cloud Resources for Policy Execution**
```
custodian schema
```
7. **Available resources for a specific cloud provider**
```
custodian schema <cloud-provider>
```
8. **Available filters and actions for each resource**
```
custodian schema <cloud-provider>.<resource>
```
9. **Exploring Policy Settings for Each Resource**
```
custodian schema <cloud>.<resource>.<category>.<item>
```
10. **Get Help for a Specific Command:**
 ```
 $ custodian <command> --h
 ```
