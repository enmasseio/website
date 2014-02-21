---
layout: default
---


Enmasse is a toolbox to develop large-scale multi-agent systems for both real-time and simulation environments. Enmasse is written in JavaScript and runs on node.js and in the browser. It provides tooling to:

- set up a scalable multi-agent system
- build advanced logical agents

Enmasse is open source and is being developed by [Almende](http://almende.com), a research company specialized in information, communication, and software agent technologies.


## Philosophy

Enmasse consists of a set of independent modules, which can be put together like lego bricks, depending on your needs. Enmasse doesn't dictate how to model your agents or your application. It gives you all freedom to choose an architecture and environment best suited for your application. Enmasse enriches your application with actors, advanced communication and reasoning capabilities, and facilitaties to deploy your application in a scalable, decentralized way.


## Application areas

- Real-time multi-agent systems
- Large-scale multi-agent simulations
- Peer-to-peer communication networks
- Distributed applications
- Semantic agents


## Modules

Enmasse will contain the following components:

- Logical agents
  - An actor module. An actor can send and receive messages to/from other actors.<br>
    Github: [enmasseio/simple-actors](https://github.com/enmasseio/simple-actors)
  - A conversation module. Advanced, dynamic communication flows between message based actors.<br>
    Github: [enmasseio/babble](https://github.com/enmasseio/babble)
  - A knowledge base. Store facts and relations between these facts, and infer new truths from this knowledge.
  - A reasoning/decision engine. Determine the best actions to take in order to reach a given goal.
- Communication
  - A distributed, peer-to-peer messaging module. Send messages between peers in a distributed network. Broadcast messages via publish/subscribe.<br>
    Github: [enmasseio/distribus](https://github.com/enmasseio/distribus)
  - A distributed, peer-to-peer network with remote objects (such as agents). Creates a proxy for remote objects, layered on top of the a messaging infrastructure.<br>
    Github: [enmasseio/remoteobjects](https://github.com/enmasseio/remoteobjects)
  - A JSON-RPC module. Expose your remote objects via a JSON-RPC API, enabling intercommunication between applications.
- Environment
  - A load-balancing module. Does do load-balancing, migration, auto-repair, and fault-tolerance of remote objects in a distributed network.
  - A management module. A web interface enabling real time logging, debugging, and management of agents.
- Simulation
  - A discrete time module. Agents synchronize their actions against a discrete, artificial simulation time, giving deterministic results.
  - A physics engine. Agents know from each other where they are in a simulated physical environment, and can reckon with each other.


## Source code

The source code of all Enmasse modules are available on Github. Each module comes with its own documentation and examples.

[https://github.com/enmasseio/](https://github.com/enmasseio/)


## Roadmap

Currently, the functionality of the various modules and the interaction between them is being defined. Each module should serve one clear purpose and should be be complementary to the other modules. The modules should be independent from each other and work seamlessly together.

The next phase will be implementing prototypes for each of the modules, and testing them in practice to validate their usability. They should really make your live easier.

Once the prototypes have been proven to work, they will be developed into mature modules.
