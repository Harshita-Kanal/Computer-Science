### System design basics
- Computational power: To run a service
- Reliability of a service can be taken care of by service providers
- Business Requirements: More users, buying bigger machines or more machines (Scalability)
- Buy bigger machine: **Vertical scaling**
- Buy more machines: **Horizontal scaling**

### Horizontal scaling
* Load balancing required
* Resilient
* Network calls
* Atomic operations are difficult
* Data consistency is an issue
* Scalable

### Vertical scaling
* Single point of failiure
* Inter process communication
* Consistent
* Hardware limit

### In reality
* Hybrid solution (Scalable, inter process communication, scales well when users increase)
