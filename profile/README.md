# Veecle

Veecle | All Cars. One Software. Our mission is to bridge the gap between existing supplier components and smart apps running on top through unified software. We provide a platform to tackle next-gen automotive connected & security demands. 

Veecle has 3 different product lines: 

- **NoS**: a 100% Rust heap-free, asynchronous and type-safe runtime for automotive. NoS acts as the gateway that allows Nteract to communicate with the vehicle in a secure and safe way.  This unit is secure by design, updatable over-the-air, and fully testable over virtual pipelines. Designed for rapid and agile development 

- **Nteract:** a 100% Rust Android Automotive & Linux compatible HAL providing secure & safe APIs to communicate to any vehicle. Nteract acts as the security gateway between the non-secure, connected "Android & Linux" world and the in-vehicle highly secure domain. This allows for zero-cost secure integration of HMI and applications 

- **Veecle Studio & Cloud Services** consist of a set of tools that can be used to deploy, test, monitor and manage our instances. At its core, this is a set of secure APIs that allows interconnecting visual tools for development, deployment, data visualisation, data storage and fleet management
        
## What is published 

- [TC37x-demo](https://github.com/veecle/tc37x-demo): demo code to run a 100% Rust basic CAN driver on AURIX™ TC375 LK
- [Tricore-probe](https://github.com/veecle/tricore-probe): a Rust probe for AURIX™ (currently works on Windows and Linux)  

## Upcoming
**Stay tuned! Our first release is coming soon!**

Dependency-free libraries for:
    - Asynchronous execution: embedded code is heavily event and I/O driven. Veecle async library massively reduces the complexity of code that relies on multitasking
    - Type-state API: most embedded execution work in a state-machine fashion. Veecle type-state library enforces execution order and rules at compile type
    - Type-safe processing: embedded data are transmitted via binary protocols. Veecle encoder library provides type-safe, memory-safe, and allocation-free binary encoders and decoders 

## Learn more
Are you interested in Veecle? \
Visit us at www.veecle.io or write us at info@veecle.io