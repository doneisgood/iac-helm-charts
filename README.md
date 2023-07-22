> _Let's Make Safe Digital World!_
> 
> _CYBNITY open source cybersecurity platform help you to govern the cyber defense of your digital assets for operate them with complete serenity._
## PURPOSE
Welcome on the Infrastructure-As-Code (IaC) project of CYBNITY that automate the provisioning and the installation of a full CYBNITY Defense Platform on cloud environments based on Kubernetes.
### The Mission
In a GitOps approach, we develop automation mechanisms ensuring the packaging, the configuration management, and the installation of CYBNITY systems in a reusable way, repeatable and customizable approach simplifying delivery into multiple target environment types (e.g common development, test, QA, staging, pre production, production).
### The main beneficiaries
This project is supporting the CYBNITY technology actors (e.g applicative developers, AppOps, DevOps, infrastructure teams) that package and deploy the CYBNITY open source defense platform versions.
### The project key artifacts
This project manage and provide Helm charts artifacts supporting the configuration management (repeatable application installation) of CYBNITY systems (e.g dockerized application components delivered by the Foundation project) and their provisioning management (K8S resources: networking, load balancing, db, users, permissions...) as Infrastructure-As-Code (IaC) which allow to automate installation on multiples Kubernetes clusters (orchestration managed environments).
# USAGE
[Helm](https://helm.sh) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh.docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```shell
  helm repo add cybnity https://github.com/cybnity/iac-helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve the lates versions of the packages.

You can then run `helm search repo cybnity` to see the charts.

To install a chart:
```shell
  helm install <chart-name> cybnity/<chart-name>
```

To uninstall a chart:
```shell
  helm delete <chart-name>
```
