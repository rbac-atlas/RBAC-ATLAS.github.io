# RBAC ATLAS

## A Curated Index of RBAC Policies in K8s

RBAC Atlas is a curated database of identities and the Role Based Access Control (RBAC) policies associated with them in popular Kubernetes open-source projects. Each entry includes security annotations that highlight granted permissions, potential risks, and possible abuse scenarios.

## Why is RBAC important?

RBAC is the final layer of defense in Kubernetes security. If workloads are compromised and an identity is stolen, a misconfigured or overly permissive RBAC policy (common with Operators) can enable attackers to move laterally within your cluster, potentially leading to a complete Kubernetes cluster takeover.

## About

RBAC Atlas is a collaborative project created by [Lenin Alevski](https://www.linkedin.com/in/alevsk/), and contributions of additional RBAC rules are welcome.
