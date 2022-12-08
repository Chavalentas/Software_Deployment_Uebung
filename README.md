# Software_Deployment_Uebung

Aufgabe:
- Es soll eine containerized DevOps pipeline erstellt werden, welche eine Node.js application in AKS zur Verfügung stellt.

## Teilnehmer
- Dawid Styczynski
- Jonas Thrackl
- Štefan Chvála
- Tamara Radomir

## Link zur App 
* https://github.com/Chavalentas/Software_Deployment_Uebung_App

## Dokumentation


## Entscheidungen

-   Azure Container Registry wurde auf Grund der guten Anbindung an den AKS-Cluster gewählt.
-   Hier wurde die Basic Version gewählt, weil diese am kostengünstigsten ist.
-   Als Applikation wurde eine simple Hello World Applikation gewählt, da diese für den Zweck ausreichend ist.

## Screenshots

### Website
<p align="center">
<img src="./Images/website.png">
</p>

## Links

* [Build and deploy to Azure Kubernetes Service with Azure Pipelines](https://learn.microsoft.com/en-us/azure/aks/devops-pipeline?pivots=pipelines-yaml)