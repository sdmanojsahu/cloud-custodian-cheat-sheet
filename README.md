# Cloud Custodian Cheat Sheet: Essential Commands for Managing Your Cloud Resources

## Introduction
Cloud Custodian is a powerful open-source tool that helps you manage and automate the governance of your cloud resources. With its extensive capabilities, it allows you to define policies to enforce security, compliance, and cost optimization across various cloud platforms. In this cheat sheet, we'll provide you with some essential Cloud Custodian commands to help you effectively manage your cloud resources.

1. **Install Cloud Custodian:**
   $ pip install c7n
2. **Check the Custodian Version:**
   $ custodian version
3. **Run Custodian Policy on Resources:**
   custodian run policy.yml -s /tmp
