---
title: "SurfStore"
description: "A distributed, fault-tolerant metadata store that uses the RAFT consensus algorithm"
dateString: Feb 2023-March 2023
draft: false
tags: ["Golang", "VS Code", "Parsing", "Framing", "RAFT","Distributed System"," Fault-tolerant","Data Consistency","Client-Server Interaction"]
weight: 201
cover:
  # image: "/projects/obsidian-publish-github-action/cover.jpg"
---


### Overview:
The Surfstore project is a distributed, fault-tolerant metadata store that utilizes the RAFT consensus algorithm to maintain consistency across replicas. The RAFTSurfstoreServer implemented communicates with other replicas via GRPC. The project also introduced a testing mechanism, ChaosMonkey, to simulate crashes and validate the server's resilience against failures.

### Key Implementations:

Distributed System Design: The Surfstore project demanded the creation of a fault-tolerant system where multiple RAFTSurfstoreServers interact. These servers are aware of other servers from the provided configuration file, and communication between them is maintained through GRPC calls.

RAFT Consensus Protocol: Implemented the RAFT protocol where a leader is elected via the SetLeader API call. This leader then communicates with other nodes using the AppendEntries() method to replicate log entries and serve as a heartbeat mechanism. The system ensures that even if a node crashes or there's a network partition, the cluster remains consistent.

ChaosMonkey Testing: Introduced a mechanism for simulating server crashes and failovers. This ensured that the server, even when receiving the Crash() API call, could handle requests and errors appropriately, either by blocking calls until restoration or returning an error message.

Persistent API Endpoints: The system supports a variety of API calls like getblock(), putblock(), hasblocks(), GetBlockStoreAddrs(), and more. These methods allow the client to interact with the system and retrieve or update data.

Heartbeat Mechanism: There's no automated heartbeat timer. Instead, heartbeats are triggered manually via the SendHeartbeat API. This ensures that a leader remains in its state until another leader takes over.

Clients Interaction: The client maintains a list of RAFT servers. If a client gets an error indicating that a server isn't the leader, it will attempt to communicate with the next server in the list.

State Management: Despite simulating crashes, the project does not involve persisting replicated logs on the filesystem. Instead, the focus is on keeping the current state in memory and ensuring it remains consistent across all nodes.

### Learnings from the Project:

Distributed Systems Complexity: Building a distributed system like Surfstore highlighted the complexities and challenges of maintaining consistency across replicas, especially when network partitions or node crashes occur.

RAFT Consensus Algorithm: Gained a deep understanding of the RAFT consensus protocol, learning how leaders are elected, how log replication happens, and how the system recovers from a leader crash.

Error Handling: Learned the importance of handling errors gracefully, especially in a distributed system. Whether it's a server crash or a non-leader node receiving a request, appropriate error messages help in maintaining system integrity.

Testing Distributed Systems: The ChaosMonkey mechanism taught the importance of rigorous testing in distributed environments. Simulating crashes and failovers is essential to validate the system's resilience.

Client-Server Interactions: Understanding the importance of designing robust client-server interactions, especially in a scenario where the client might be communicating with a non-leader node.

Performance Considerations: Learned to ensure that the system can handle a specific number of RPC calls per second without overwhelming the infrastructure or causing breakdowns.



Overall, the Surfstore project was a deep dive into the world of distributed systems, providing hands-on experience with the challenges and solutions in building fault-tolerant, consistent, and resilient systems.


[View the project here](https://github.com/mounikapadala11/SurfStore)


