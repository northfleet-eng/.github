# Northfleet

**The sovereign supply chain for Canada's classified Kubernetes.**

A Canadian-incorporated Kubernetes supply chain vendor. Northfleet supplies the bundle protocol, attestation chain, and tamper-evident audit trail that cleared engineering teams apply to their Protected B and Secret Kubernetes clusters on Canadian-jurisdictional infrastructure. The customer brings the cluster; Northfleet supplies the trust path between build and apply. Northfleet holds no customer data and no customer signing keys, and the architecture assumes the vendor can be compromised or compelled: compelling Northfleet does not produce a silent backdoor.

[northfleetsecurity.ca](https://northfleetsecurity.ca) · [Field notes](https://northfleetsecurity.ca/field-notes) · [Contact](https://northfleetsecurity.ca/contact)

## Public repositories

One open specification and two open-source utilities that contribute to the shared procurement vocabulary for Canadian defence engineering teams. Each is released under the Apache License 2.0; Government of Canada text reproduced in the utilities keeps its own terms, stated in each repository.

- **[bundle-format](https://github.com/northfleet-eng/bundle-format)**: the open specification for the Northfleet bundle format, published so that anyone who receives a bundle can verify it with stock tooling, without installing or trusting Northfleet software.
- **[itsg33-kubernetes-protected-b-mapping](https://github.com/northfleet-eng/itsg33-kubernetes-protected-b-mapping)**: the Government of Canada Protected B / Medium control profile (CCCS ITSP.10.033-01, successor to ITSG-33 Annex 4A Profile 1) mapped to Kubernetes mechanisms, bucketed by admin-implemented, workload-implemented, and external. Markdown and CSV, the catalogue, profile and mapping in OSCAL, and automated policy checks for eight controls, published as OSCAL assessment results.
- **[cpcsc-l1-self-assessment](https://github.com/northfleet-eng/cpcsc-l1-self-assessment)**: a self-assessment template for Level 1 of the Canadian Program for Cyber Security Certification, with the 13 controls and 71 determination statements from PSPC's Level 1 criteria in Markdown and CSV.

The two utilities are public framework content with a community usability layer. Neither encodes Northfleet implementation specifics.

## For defence primes, federal departments, and allied buyers

If you are evaluating sovereign infrastructure for classified workloads, the conversation is open at [northfleetsecurity.ca](https://northfleetsecurity.ca). A briefing follows first contact.
