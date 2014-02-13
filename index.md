---
layout: default
---


Enmasse is a toolbox to develop large-scale multi-agent systems for both real-time and simulation environments. Enmasse is written in JavaScript and runs on node.js and in the browser. Enmasse makes it easy to set up a scalable agent platform or a simulation platform, and comes with tools to build advanced, logical agents.

The Enmasse project is open source and is being developed by [Almende](http://almende.com), a research company specialized in information, communication, and software agent technologies.


## Philosophy

Enmasse is set up as a set of independent modules, which can be put together like lego bricks according to your needs. Enmasse doesn't dictate how to model your agents, and doesn't dictate any architecture or platform for your application. It gives you all freedom to choose an architecture and environment best suited for your application. Enmasse enriches your agents with advanced communication and reasoning capabilities, and facilitates deploying your application in a scalable, decentralized way.


## Application areas

- Real-time multi-agent systems
- Large-scale multi-agent simulations
- Distributed applications
- Peer-to-peer communication networks


## Modules

Enmasse will contain the following components, which can be used independently of each other:

- An actor module. An actor can send and receive messages to other actors.
- A (scalable) peer-to-peer infrastructure to host agents (or more general: remote objects). Offers load balancing, migration, routing of communication, etc.
- A (distributed) communication module: send and receive messages between remote peers. Broadcast messages. Publish and subscribe messages.
- A conversation module, [babble](https://github.com/enmasseio/babble): Dynamic communication flows between message based actors.
- A JSON-RPC module: enable communication between multiple multi-agent systems via JSON-RPC.
- A reasoning engine (knowledge base): agents can store facts and relations between facts, and infer new truths from this knowledge.
- A simulation module: run a simulation with agents in discrete time steps.
- A management module: a web interface enabling real time logging, debugging, and management of agents.


## Roadmap

Currently, the functionality of the various modules and the interaction between them is being defined. Each module should serve one clear purpose and should be be complementary to the other modules. The modules both have to be independent from each other and work seamlessly together.

The next phase will be implementing prototypes for each of the modules, and testing them in practice to validate their usability. They should really make your live easier.

Once the prototypes have been proven to work, they will be developed into mature modules.
