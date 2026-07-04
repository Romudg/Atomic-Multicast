This repository offers the pseudocode for different solutions to implement Atomic Multicast.

The different files contain different 'levels' of the algoritm, from the vanilla version (Skeen's protocol), to 
the versions that are optimized for protocol and network topology.

In particular:

1) Vanilla_Atomic_Multicast.txt : Basic version of the algoritm
2) Fault_tolerant_atomic_multicast : Introduces groups and replicas, able to manage failures of nodes
3) Paxos.txt : Paxos implementation to Broadcast a message internally in a group
4) WBCast.txt : Implementation of the paper 'White-box-atomic-multicast'. Offers a great speed-up compared to previous versions.
5) RDMACast.txt : Implementation of the paper 'RAMCast'. The algoritm is optimized for RDMA protocol.
6) AM+RDMA+Topologia.txt : Implementation of the paper 'TRAM'. This algoritm introducess a tree structure that improves scalability potential for RDMA based Atomic Multicast.
