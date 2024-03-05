The project started with [this code](  https://github.com/tombombadilom/helia-ipfs-cms-template) but as I'm studying other back-end hosting solutions, It will be for now structured in 4 different entities:

- The Front-End written in Typescript with React or maybe later in Svelte
- The Back-End, written in Typescript with express.js 
- The whole solution, which will load the Front and the Backend and use Docker or docker-compose to assemble the whole application.
- A Terraform folder to write the implementation of the solution for Kubernetes in an infrastructure-as-code way.

This way I think this project will be able to be used from:
- the desktop machine of a developer,
- a Raspberry Pi server aside,
- a bare metal self-hosted server,
- a Fleek.co IPFS Free plan hosting or similar solution,
- a cluster of Raspberry Pi using k3s 
- a cluster of Kubernetes using k8s.
