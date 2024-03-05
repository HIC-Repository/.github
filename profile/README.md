## Hi there 👋 welcome to the Helia IPFS Playground Repository
This project is seen as a gateway to the world of IPFS. It is aimed at everyone, especially those who are new to this ecosystem.

For a long time, IPFS was penalized by its high latency, but since the release of version 1.0 of the P2P lib, latency has improved considerably:
- 200 ms for the P2P lib in JavaScript 
- 175 ms for P2P lib in Go

It goes without saying that the transition from version 0.x to 1.x of the P2P lib for ecosystem applications will involve a major rewrite of the code, but from my point of view, this is the ideal time to test, experiment and why not contribute with my limited means.


🙋‍♀️ **Helia IPFS Playground Repository** intend to experiment and play with Helia and IPFS 
The project started with [this code](  https://github.com/tombombadilom/helia-ipfs-cms-template) but as I'm studying other back-end hosting solutions, 
It will be for now structured in 4 different entities:
- The [HIC Front-End](https://github.com/HIC-Repository/HIC-Front) written in Typescript with React or maybe later in Svelte or something more agnostic.
- The [HIC Back-End](https://github.com/HIC-Repository/Hic-Back), written in Typescript with Express.js.
- The [HIC Full-Stack](https://github.com/HIC-Repository/HIC-FullStack), which will load the Front and the Backend and use Docker or docker-compose to assemble the whole application.
- The [HIC SelfHosted](https://github.com/HIC-Repository/Hic-SelfHost), Intended to be hosted in a simple bare metal server , LXS , VPS , Raspberry pi server ...
- A [HIC Infrastructure](https://github.com/HIC-Repository/HIC-Infra) Terraform folder to write the implementation of the solution for Kubernetes in an infrastructure-as-code way.

This way I think this project will be able to be used from:
- the desktop machine of a developer,
- a Raspberry Pi server aside,
- a bare metal self-hosted server,
- a Fleek.co IPFS Free plan hosting or similar solution,
- a Cluster of Raspberry Pi using K3S 
- a Cluster of Kubernetes using K8S.
🌈 Contribution guidelines - how can the community get involved?

👩‍💻 Useful resources
- Lib P2P:
  - Blog
  - Github
  - Documentation
- Helia
  - Github
  - Documentation
- IPFS
  - Github
  - Documentation
  - Some main applications and libs
    - Kubo:
    - orbitDB:
    - Uplink :
    - IPFS Desktop:
