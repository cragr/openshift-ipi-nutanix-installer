# OpenShift IPI on Nutanix Ansible Playbook

This repository contains Ansible playbooks for deploying OpenShift clusters using the Installer Provisioned Infrastructure (IPI) method on Nutanix platforms. These playbooks automate the process of setting up the necessary infrastructure on Nutanix and deploying OpenShift clusters, simplifying the creation and management of Kubernetes environments.

## Features

- Automated deployment of OpenShift clusters on Nutanix
- Configuration of Nutanix AHV settings for OpenShift
- Customization options for cluster size, network settings, and more

## Prerequisites

- Ansible installed on your machine
- Access to a Nutanix environment
- An OpenShift pull secret

## Quick Start

1. Clone this repository.
2. Configure your `hosts` file with the required settings.
3. Run the playbook using `ansible-playbook -i hosts install-cluster.yml`.

## Configuration

Please refer to the `hosts` file for an example configuration. Adjust the settings according to your Nutanix environment and OpenShift requirements.

## Contributing

We welcome contributions! If you would like to improve the playbooks, please submit a pull request or open an issue to discuss your ideas.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
