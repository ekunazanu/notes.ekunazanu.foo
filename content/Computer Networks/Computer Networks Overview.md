A collection of interconnected computers that share resources and information with each other. The computers in a network are usually referred to as hosts. Modern computer networks use packet switching — information is exchanged in the form of small 'packets' of data, with each packet having some specific header metadata and the main payload data.

## Network Topology

The computers in a network can be arranged using different physical topologies, depending on the needs. The network can be thought of as a [graph](Mathematics/Graph%20Theory.md) with the computers as nodes and connections as edges.

* **Point to Point** — Two nodes are connected by a single edge. Very simple to set up, but its simplicity is also restrictive.
* **Bus** — All nodes are connected to a single cable, called the backbone of the network.
* **Star** — All nodes are connected to a central 'hub'.  Used for Local Area Networks (LANs). A failure in the central hub can bring the network down.
* **Ring** — Each node is connected to exactly two other nodes such that the network forms a ring. A failure in any node can bring the network down.
* **Mesh** — Each node is directly linked to multiple other nodes.
	* **Fully Connected** — Every node is connected to every other node in the network.
* **Hybrid** — A network that combines multiple of the above topologies.
	* **Tree** — A combination of star networks that are interconnected via bus networks.

## The Layered Model

The networking stack is conceptually divided into several layers to provide abstraction from the hardware, and lower levels. The number of layers depends on the classification. Broadly, two models are popular — the OSI Model and the TCP/IP Model.

The OSI Model has seven layers:

* **Application Layer** — Includes protocols for user facing applications such as file transfer, access, mail, etc.
* **Presentation Layer** — Includes protocols for encoding, decoding, encryption, compression, etc of data to and fro the application layer.
* **Session Layer** — Includes protocols to create abstractions for creating (and terminating) connections in the form of sessions — full duplex, half duplex connections etc — for the higher layers.
* **Transport Layer** — Includes protocols to ensure 'proper' transmission of data, by having checks for error correction, deduplication, reordering of packets etc.
* **Network Layer** — Includes protocols for addressing hosts and for routing of packets across wide area networks.
* **Data Link Layer** — Includes protocols for addressing hosts in a local network and sending frames (packets) to the addressed hosts.
* **Physical Layer** — Includes protocols for the physical electrical or optical communications to transmit data.

The TCP/IP Model has four layers:

* **Application Layer** — 
* **Transport Layer** — 
* **Internet Layer** — 
* **Link Layer** — 

## Application Layer

### Hyper Text Transfer Protocol

#### Transport Layer Security Protocol

### Simple Mail Transfer Protocol

### Internet Message Access Protocol

### Secure Shell Protocol

### Border Gateway Protocol

## Transport Layer

### User Datagram Protocol

### Transmission Control Protocol

## Internet Layer

### Internet Protocol

#### IPv4

#### IPv6

## Link Layer

### Address Resolution Protocol