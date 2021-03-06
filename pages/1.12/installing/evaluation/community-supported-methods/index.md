---
layout: layout.pug
excerpt: Use CloudFormation, AzureRM or other Terraform templates to install DC/OS.
title: Other Installation methods
navigationTitle: Other Installation methods
menuWeight: 10
---

<p class="message--warning"><strong>DISCLAIMER: </strong>This is a <a href="https://github.com/dcos/terraform-dcos/tree/master/gcp">community driven project</a> and not officially supported by Mesosphere. These installation methods are recommended for demos and proofs of concept. Installing DC/OS cluster on AWS, Azure, GCE, Digital Ocean, or Packet through these methods are intended for reference only and are not recommended for production use.</p>

Any of the following methods can be used to install DC/OS:
- [Provision DC/OS manually on AWS](/1.12/installing/evaluation/community-supported-methods/aws/) (AWS): Install your DC/OS cluster on Amazon Web Services (AWS) by using the DC/OS templates on AWS CloudFormation. 
- [Provision DC/OS manually on Azure](/1.12/installing/evaluation/community-supported-methods/azure/): Install your DC/OS cluster on Azure by using the Azure Resource Manager templates.
- [Provision DC/OS on DigitalOcean](/1.12/installing/evaluation/community-supported-methods/digitalocean/): Install your DC/OS cluster on DigitalOcean by using Terraform templates that are configured to run Mesosphere DC/OS on DigitalOcean.
- [Provision DC/OS on Packet bare metal](/1.12/installing/evaluation/community-supported-methods/packet/): A bare metal environment is a computer system or network in which a virtual machine is installed directly on hardware rather than within the host operating system (OS). Install your DC/OS cluster on Packet bare metal using Terraform templates that are configured to run Mesosphere DC/OS on Packet.

You can use the [Mesosphere Universal Installer](/1.12/installing/evaluation/mesosphere-supported-methods) methods to install a fully functional cluster.

<p class="message--note"><strong>NOTE: </strong>Contact the <a href="https://groups.google.com/a/dcos.io/forum/#!forum/users">mailing list</a> or <a href="http://chat.dcos.io/?_ga=2.226911897.58407594.1533244861-1110201164.1520633201">Slack channel</a> for community support.</p>

