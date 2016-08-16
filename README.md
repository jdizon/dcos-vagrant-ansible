DC/OS Vagrant
==================

Quickly provision a [DC/OS](https://github.com/dcos/dcos) cluster on a local machine for development, testing, or demonstration.

Deploying DC/OS Vagrant involves creating a local cluster of VirtualBox VMs using the [dcos-vagrant-box](https://github.com/dcos/dcos-vagrant-box) base image and then installing [DC/OS](https://dcos.io/).

This fork of DC/OS Vagrant uses Ansible for node provisioning.

### Issue Tracking

- Issue tracking for **dcos-vagrant-ansible** is in Github.
- Issue tracking for **DC/OS** itself are in [DC/OS JIRA](https://dcosjira.atlassian.net/projects/VAGRANT/).

### Limitations

- DC/OS Vagrant Ansible only supports the [custom advanced installation](https://dcos.io/docs/latest/administration/installing/custom/advanced/) of DC/OS (not the CLI or GUI install methods).
- Debugging Ansible failures can be a bit complicated due to buffering of the logs.
- [DC/OS Vagrant](https://github.com/dcos/dcos-vagrant/) is the local deployment method officially supported by Mesosphere. This Ansible version is provided AS IS.

# Where Do I Start?

- [Deploy](/docs/deploy.md)
- [Configure](/docs/configure.md)
- [Upgrade](/docs/upgrade.md)
- [DC/OS Vagrant Examples](https://github.com/dcos/dcos-vagrant/tree/master/examples)

# DC/OS Vagrant Documentation

- [Audience and Goals](/docs/audience-and-goals.md)
- [Network Topology](/docs/network-topology.md)
- [Alternate Install Methods](/docs/alternate-install-methods.md)
- [DC/OS Install Process](/docs/dcos-install-process.md)
- [Install Ruby](/docs/install-ruby.md)
- [Repo Structure](/docs/repo-structure.md)
- [DC/OS CLI](/docs/dcos-cli.md)
- [Troubleshooting](/docs/troubleshooting.md)
- [VirtualBox Guest Additions](/docs/virtualbox-guest-additions.md)


# How Do I...?

- Learn More - https://dcos.io/
- Find the Docs - https://dcos.io/docs/
- Get Help - http://chat.dcos.io/
- Join the Discussion - https://groups.google.com/a/dcos.io/d/forum/users/
- Report a DC/OS Vagrant Issue - https://dcosjira.atlassian.net/projects/VAGRANT/
- Report a DC/OS Issue - https://dcosjira.atlassian.net/projects/DCOS/
- Contribute - https://dcos.io/contribute/


# License

Copyright 2016 Mesosphere, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this repository except in compliance with the License.

The contents of this repository are solely licensed under the terms described in the [LICENSE file](/LICENSE) included in this repository.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
