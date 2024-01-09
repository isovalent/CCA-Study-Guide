# CIlium Certified Associate Study Guide

![](files/ogimage.jpeg)
The aim of this study guide is to help the Cilium community prepare for the [Cilium Certified Associate(CCA)](https://training.linuxfoundation.org/certification/cilium-certified-associate-cca/) Exam 🐝

### Architecture
- [Cilium - Rethinking Linux Networking and Security for the Age of Microservices](https://cilium.io/blog/2018/04/24/cilium-security-for-age-of-microservices/)
- [Cilium 1.0: Bringing the BPF Revolution to Kubernetes Networking and Security](https://cilium.io/blog/2018/04/24/cilium-10/)
- [Cilium Technical Deep Dive: Under the Hood - Talk](https://www.youtube.com/watch?v=UZg_2SXDKis)
- [Cilium's BPF kernel datapath revamped - Talk](https://www.youtube.com/watch?v=u0PGas8D24w)
- [Cilium eBPF Datapath - Cilium Docs](https://docs.cilium.io/en/stable/network/ebpf/)
- [IP Address Management (IPAM) - Cilium Docs](https://docs.cilium.io/en/stable/network/concepts/ipam/)
- [Cilium Component Overview - Cilium Docs](https://docs.cilium.io/en/stable/overview/component-overview/)
- [Cilium LoadBalancer IPAM and BGP Service Advertisement](https://isovalent.com/labs/lb-ipam-bgp-service/)

## eBPF
- [Why is the kernel community replacing iptables with BPF?](https://cilium.io/blog/2018/04/17/why-is-the-kernel-community-replacing-iptables/)
- [eBPF - The Future of Networking & Security](https://cilium.io/blog/2020/11/10/ebpf-future-of-networking/)
- [What is eBPF?](https://ebpf.io/what-is-ebpf/)
- [Getting started with eBPF](https://isovalent.com/labs/getting-started-with-ebpf/)

### Installation and Configuration
- [Cilium Quick Installation](https://docs.cilium.io/en/latest/gettingstarted/k8s-install-default/#k8s-install-quick)
- [eCHO episode 1: Introduction to Cilium](https://www.youtube.com/watch?v=80OYrzS1dCA&list=PLDg_GiBbAx-mY3VFLPbLHcxo6wUjejAOC&index=114)
- [Getting Started with Cilium](https://isovalent.com/labs/getting-started-with-cilium/)
- [Tutorial: Tips and Tricks to install Cilium](https://isovalent.com/blog/post/tutorial-tips-and-tricks-to-install-cilium/)

### Network Observability
- [eCHO episode 2: Introduction to Hubble](https://www.youtube.com/live/hD2iJUyIXQw?si=WqWaY7_jN2B-sRz5)
- [Setting up Hubble Observability](https://docs.cilium.io/en/latest/gettingstarted/hubble_setup/#hubble-setup)
- [Layer 7 Protocol Visibility](https://docs.cilium.io/en/stable/observability/visibility/)
- [Back to Basics – L7 Flow Visibility](https://isovalent.com/videos/back-to-basics-l7-flow-visibility/)
- [Cilium IPv6 Networking and Observability - Lab](https://isovalent.com/labs/ipv6-networking-and-observability/)

### Network Policy
- [Identity Based - Cilium Docs](https://docs.cilium.io/en/stable/security/network/identity/)
- [Zero Trust Security with Cilium](https://isovalent.com/blog/post/zero-trust-security-with-cilium/)
- [Network Policy - Cilium Docs](https://docs.cilium.io/en/latest/security/policy/)
- [Policy Enforcement Mode - Cilium Docs](https://docs.cilium.io/en/latest/security/policy/intro/)
- [Why is Kubernetes Network Policy important?](https://youtu.be/5sc4R-wk7uo)
- [Birth of Kubernetes Network Policy](https://youtu.be/x69ofJYr71g)
- [NetworkPolicy Tutorial](https://github.com/networkpolicy/tutorial)

### Service Mesh
- [How eBPF will solve Service Mesh – Goodbye Sidecars](https://isovalent.com/blog/post/2021-12-08-ebpf-servicemesh/)
- [Cilium Service Mesh](https://cilium.io/use-cases/service-mesh/)
- [Service Mesh Architectures Explained - Sidecar and Beyond](https://youtu.be/j7JKkbAiWuI?si=6jWl3GQ6CjVLHBFJ)
- [Cilium Service Mesh – Everything You Need to Know](https://isovalent.com/blog/post/cilium-service-mesh/)
- [Cilium Ingress Controller - Lab](https://isovalent.com/labs/cilium-ingress-controller/)
- [Cilium Transparent Encryption with IPSec and WireGuard - Lab](https://isovalent.com/labs/cilium-transparent-encryption-with-ipsec-and-wireguard/)
- [Gateway API support - Cilium Docs](https://docs.cilium.io/en/stable/network/servicemesh/gateway-api/gateway-api/)
- [Cilium Gateway API](https://isovalent.com/labs/gateway-api/)
- [Advanced Gateway API Use Cases - Lab](https://isovalent.com/labs/advanced-gateway-api-use-cases/)
- [Ingress Controllers or the Kubernetes Gateway API? Which Is Right for You?](https://thenewstack.io/ingress-controllers-or-the-kubernetes-gateway-api-which-is-right-for-you/)
- [A Deep Dive into Cilium Gateway API: The Future of Ingress Traffic Routing](https://isovalent.com/blog/post/cilium-gateway-api/)
- [Cilium Gateway API - Youtube Playlist](https://youtube.com/playlist?list=PLngi_1qThAPCiulGkrufXeN_ibmKZDCia&si=Hijz5I83OuM0Yonr)

### Cluster Mesh
- [Cilium Cluster Mesh - Lab](https://isovalent.com/labs/cilium-cluster-mesh/)
- [Connecting Klusters on the Edge with Deep Dive into Cilium Cluster Mesh - Talk](https://www.youtube.com/watch?v=UcsEVnFtrLY)
- [An Introduction to Cilium Cluster Mesh](https://www.youtube.com/watch?v=4bJkk7ghx7A)
- [eCHO episode 41: Cilium Cluster Mesh](https://www.youtube.com/watch?v=VBOONHW65NU)
- [eCHO Episode 94: Cluster API and Cilium Cluster Mesh](https://m.youtube.com/watch?v=HVqQhMRpUR4&pp=ygUKI2Fic29saXRlbQ%3D%3D)


### BGP and External Networking
- [Cilium BGP Control Plane](https://docs.cilium.io/en/stable/network/bgp-control-plane/)
- [BGP on Cilium - Lab](https://isovalent.com/labs/bgp-on-cilium/)
- [Advanced BGP Features - Lab](https://isovalent.com/labs/advanced-bgp-features/)
- [BGP with Cilium](https://nicovibert.com/2022/07/21/bgp-with-cilium/)
- [Connecting your Kubernetes island to your network with Cilium BGP](https://isovalent.com/blog/post/connecting-your-kubernetes-island-to-your-network-with-cilium-bgp/)
