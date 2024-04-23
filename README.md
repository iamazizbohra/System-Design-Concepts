# System Design Concepts


### Scalability Lecture At Harvard CS75

[Watch Here](https://www.youtube.com/watch?v=-W9F__D3oY4)

### Scale From Zero To Millions Of Users

[Click Here](https://bytebytego.com/courses/system-design-interview/scale-from-zero-to-millions-of-users)


### How Web Works

[Click Here](https://github.com/vasanthk/how-web-works)

### What really happens when you navigate to a URL

[Click Here](https://igoro.com/archive/what-really-happens-when-you-navigate-to-a-url/)

---

### Scalability Basics

* What is Vertical Scaling?
* What is Horizontal Scaling?
* What is a Single Point of Failure (SPOF)?
* What is Resiliency? How do you make systems resilient?
* What is Redundancy? How do you introduce redundancy in systems?

    [Click Here](https://systemdesignprep.com/scalability)

### More on Scalability

* [Clones](https://web.archive.org/web/20220530193911/https://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
* [Databases](https://web.archive.org/web/20220602114024/https://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
* [Caches](https://web.archive.org/web/20220308125625/https://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
* [Asynchronism](https://web.archive.org/web/20220617032344/https://www.lecloud.net/post/9699762917/scalability-for-dummies-part-4-asynchronism)

---

### Load Balancing

* [Load Balancer](https://github.com/donnemartin/system-design-primer#load-balancer)

* Types of Load Balancers – Based on Functions
    * [Layer 4](https://www.nginx.com/resources/glossary/layer-4-load-balancing/)
    * [Layer 7](https://www.nginx.com/resources/glossary/layer-7-load-balancing/) 

* [Types of Load Balancers – Based on Configurations](https://www.appviewx.com/education-center/load-balancer-and-types/#types-of-load-balancers-based-on-configuration)
    * Hardware Load Balancers
    * Software Load Balancers

* [Load Balancer Configurations](https://kemptechnologies.com/white-papers/unfog-confusion-active-passive-activeactive-load-balancing)
    * Active-Active
    * Active-Passive

* [Load Balancing Algorithms](https://www.appviewx.com/education-center/load-balancer-and-types/#load-balancing-methods)

* [Session Persistence or Sticky Sessions](https://www.imperva.com/learn/availability/sticky-session-persistence-and-cookies/)
    * Duration-based session persistence
    * Application-controlled session persistence

* [Proxy vs Forward Proxy vs Reverse Proxy](https://www.youtube.com/watch?v=MiqrArNSxSM)

* [Load Balancer vs Reverse Proxy](https://www.nginx.com/resources/glossary/reverse-proxy-vs-load-balancer/)

* [Load Balancer vs API Gateway](https://blog.hubspot.com/website/api-gateway-vs-load-balancer)

---

### High level trade-offs

* [Performance vs scalability](https://github.com/donnemartin/system-design-primer#performance-vs-scalability)

* [Latency vs throughput](https://github.com/donnemartin/system-design-primer#latency-vs-throughput)

* [Availability vs consistency](https://github.com/donnemartin/system-design-primer#availability-vs-consistency)

* CAP Theorem
    * [Story](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
    * [Picture](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)
    * [Video](https://www.youtube.com/watch?v=k-Yaq8AHlFA)

---

### Consistency Patterns

* [Click Here](https://systemdesign.one/consistency-patterns/)
* [Click Here](https://github.com/donnemartin/system-design-primer#consistency-patterns)

---

### Availability Patterns

* [Video](https://www.youtube.com/watch?v=WC7kpQPGPp8)
* [Click Here](https://github.com/donnemartin/system-design-primer#availability-patterns)

---

### Availability in numbers

* [AWS](https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/availability.html)
* [Click Here](https://github.com/donnemartin/system-design-primer#availability-in-numbers)

---

### Domain name system

<img src="https://d1.awsstatic.com/Route53/how-route-53-routes-traffic.8d313c7da075c3c7303aaef32e89b5d0b7885e7c.png" height="auto" width="auto" >

[Video](https://www.youtube.com/watch?v=9f1AW2it2WY)

[Click Here](https://github.com/donnemartin/system-design-primer#domain-name-system)

[cloudflare](https://www.cloudflare.com/learning/dns/what-is-dns/)

[A Comprehensive Guide to How It Works](https://www.hostinger.in/tutorials/what-is-dns)

---

### Content delivery network

<img src="https://i.ytimg.com/vi/RI9np1LWzqw/hq720.jpg" height="auto" width="auto" >

[Video](https://www.youtube.com/watch?v=RI9np1LWzqw)

[Click Here](https://github.com/donnemartin/system-design-primer#content-delivery-network)

[What is CDN?](https://aws.amazon.com/what-is/cdn/)

---
