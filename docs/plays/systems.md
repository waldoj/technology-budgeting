### Fund systems, not monoliths

Don’t replace the old legacy system with a new legacy system. Insist on loosely coupled systems that are built incrementally. That way, they’ll never need to be replaced wholesale — they’ll just replace individual components as the need arises.

#### Checklist

- [ ] Each contract will be written to deliver value to end users — they’re not for "maintaining servers" or "setting up a database," but for "adding a web-based permit application system" or "simplifying the intake process"
- [ ] There will be no single "enterprise architect," because the architecture will emerge iteratively throughout the agile process
- [ ] If the project is large enough that it will include multiple scrum teams working simultaneously, there is no expectation that all members of all teams will ever be in meetings together
- [ ] The RFP will specify the use of service-oriented architecture for each component

#### Key questions

- Is there a single point of failure that can bring the whole system down? (If so, that’s probably monolith, not a system.)
- If one vendor’s contract needs to be terminated for non-performance, can the others continue to work without interruption?
