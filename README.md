# KubePlaybook, the K8s ansible executor.

**when Ansible meets kubernetes** 

_Less is more_ 


The **KubePlaybook** project is based on the awx-ressources-operator. However, instead of managing a separate AWX / AAP instance, it will perform all those actions in a k8s native way, expanding on operators and custom ressources. 

AWX / AAP are fairly opinionated tools. The goal of this exercice is to demonstrate that a declarative approach can be taken to reliably and efficiently build a similar infrastructure with low efforts thanks to K8S expandable capabilites through operators and CRD.

# Concept 

