# Welcome to the SSF SMARTY project page.

The purpose of this web page is to showcase the research outputs of the project.
Additional information also available on the [Lund University research portal](https://portal.research.lu.se/sv/projects/s%C3%A4kra-mjukvaruuppdateringar-f%C3%B6r-den-smarta-staden).


## Software Defined Network Security

A secure software infrastructure connecting all components is a necessary backbone for delivering and deploying secure software updates to endpoints.
We address network infrastructure security on several levels, combining a diverse set of approaches and tools.


**Routing misconfigurations** commonly occur in complex heterogeneous networks, potentially leading to routing policy violations.
We used property-based testing to detect - before deployment - network routes that may violate routing policies in Software-Defined Networks.

**Software network components** deployed throughout the network fabric are valuable targets for adversaries that aim to take over the network infrastructure. We started off by improving the security of data collected and processed by Open vSwitch by decomposing and porting it to Intel SGX enclaves. Here we built on earlier experience in using confidential enclaves to protect the privacy of software patching recommendations.
It later became evident that firmware patches aimed at preventing speculative execution attacks, while necessary, induce a tangible performance overhead on common network switch operations. We subsequently addressed this by improving the IO performance of network components deployed in SGX enclaves This work was preseted at the [SPIN'21 Workshop on Secure Programmable Network Infrastructure](https://portal.research.lu.se/sv/publications/faster-enclave-transitions-for-io-intensive-network-applications)).

{% include vimeoPlayer.html id=651087489 %}

**Key distribution** can be made more efficient by leveraging the control and configuration messages exchanged between the components of SDN deployments. We used this insight to deploy ephemeral symmetric keys and reduce the computational cost of key negotiation between resource-constrained endpoints in Flowrider. We demonstrated our results at the [25th Conference on Innovation in Clouds, Internet and Networks](https://portal.research.lu.se/sv/publications/on-demand-key-distribution-for-cloud-networks)

{% include vimeoPlayer.html id=651095024 %}

We implemented the approach using Open vSwitch and a Ryu controller with endpoints deployed in Docker containers.

{% include vimeoPlayer.html id=651095395 %}

Our implementation showed that the Flowrider approach can reduce the computational cost of setting up a secure communication channel by an order of magnitude. Results were published in [SecureComm 2021](https://portal.research.lu.se/sv/publications/flowrider-fast-on-demand-key-provisioning-for-cloud-networks).
