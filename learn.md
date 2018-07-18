---
title: Learning Lab
layout: default
---
## Learn You Networking!
Learning materials from various community network projects.

[TOmesh](https://tomesh.net/):
* [Building the Peer-to-Peer Internet Workshop](https://github.com/tomeshnet/p2p-internet-workshop#building-the-peer-to-peer-internet)
* [Various documentation](https://github.com/tomeshnet/documents/tree/master/technical)

[Sudo Mesh](https://sudomesh.org):
* [Node Whisperer's Program](https://github.com/sudomesh/node-whisperer-program) - Node whisperers explain how (exit/home) nodes work and keep them from misbehaving by troubleshooting, preparing bug fixes, applying patches, implementing new features and upgrading software. To become a node whisperer, you should be able to show someone how to build your own internet by configuring one, (ideally two) home node(s) (https://peoplesopen.net/walkthrough ) to use a custom, self-created exitnode (https://github.com/sudomesh/exitnode ). This also includes showing how babeld and tunneldigger work together by using (and improving!) https://github.com/sudomesh/babeld-lab and https://github.com/sudomesh/tunneldigger-lab on the home and exit nodes using tools like ip route , ip addr, tcpdump .
* [Network Lab](https://github.com/sudomesh/network-lab) - This script creates a set of network namespaces, linked by virtual eth connections. It is entirely driven by a JSON network graph configuration format. Additionally, it uses the tc netem traffic shaper to simulate various kinds of faulty connections, packet loss, and latency on the links. This tool was created to experiment with and test routing protocols, but it could have many other uses.
* [Babel Lab](https://github.com/sudomesh/babeld-lab) - The purpose of this project is to set up a virtual babel mesh for educational and testing purposes.
* [Tunneldigger Lab](https://github.com/sudomesh/tunneldigger-lab) - Experiments on digging VPN tunnels.
* [People's Open Network Operator's Manual](https://github.com/sudomesh/babeld-lab/blob/master/operator_manual.md) - This manual should help operators to: get started with sudo mesh (network) design; test newly built node firmware; create and maintain home, extender and exit nodes; and train new operators.
* [Sudo Mesh Services Setup Guide](https://github.com/sudomesh/babeld-lab/blob/master/services_guide.md) - This guide is intended to help mesh node operators to: decide what service might work well on a mesh network; implement their service; make their service accessible on the mesh (and the Internet?); maintain their service; teach others to set up services
* [People's Open Net Installer (PONI) Program](https://github.com/sudomesh/mounting/blob/master/PONIprogram.md) - People's Open Node Installers, affectionately known as PONIs, are individuals capable of facilitating the installation of a mesh node for the People's Open Network.To become a "certified" PONI, one must complete the following tasks in the order shown,; Participate in a Node Mount Training and Safety Explanation Session; Contribute to at least one node mount (ideally two, or as many as you need to feel comfortable, this really depends or your experience); Facilitate at least one node mount; Share what you've learned with another provisional PONI in training.
