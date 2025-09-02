# Deploy EVE-NG to Google Cloud using IaC

## Features

- Deploys an EVE-NG (Community Edition) VM instance in Google Cloud that mostly follows the steps outlined in the [official documentation](https://www.eve-ng.net/index.php/documentation/community-cookbook/).
- Automatically downloads lab images from a Google Cloud bucket and fixes permissions.
- Easily tears down the entire VM with a single command so that it costs virtually nothing when not in use.
- Integrates with the [No-IP](https://www.noip.com/) API to update the DDNS entry on boot.
- Automatically creates a secure admin password for the web GUI.
- **TODO** Automatically download and backup lab configuration files.

## Install

- TODO
