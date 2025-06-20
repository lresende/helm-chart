# Jupyter Server Helm Chart Repository

Welcome to the Jupyter Server Helm Chart Repository!  
Here you can find packaged Helm charts for Jupyter Server related projects, such as [Jupyter Enterprise Gateway](https://github.com/jupyter-server/enterprise_gateway).

## Available Helm Chart Releases

| Chart Name           | Version | App Version | Description                                   | Chart Package Download |
|----------------------|---------|-------------|-----------------------------------------------|-----------------------|
| Enterprise Gateway   | 3.2.3   | 3.2.3       | A helm chart to deploy Jupyter Enterprise Gateway | [Download](https://lresende.github.io/helm-chart/jupyter_enterprise_gateway_helm-3.2.3.tgz) |

## How to Use

Add this repository to your Helm client:

```sh
helm repo add jupyter-server https://lresende.github.io/helm-chart/
helm repo update