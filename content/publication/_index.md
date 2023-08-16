---
abstract: "In cellular networks, there is a growing adoption of virtualized
  radio access networks (vRANs), where operators are replacing the traditional
  specialized hardware for RAN processing with software running on commodity
  servers. Today’s vRAN deployments lack resilience, since there is no support
  for vRAN failover or upgrades without long service interruptions. Enabling
  these features for vRANs is challenging because of their strict real-time
  latency requirements and black-box nature. Slingshot is a new system that
  transparently provides resilience for the vRAN’s most performance-critical
  layer: the physical layer (PHY). We design new techniques for realtime
  workload migration with fast RAN protocol middleboxes, and realtime RAN
  failure detection. A key insight in our design is to view the transient
  disruptions from resilience events to RAN computation state and I/O similarly
  to regular wireless signal impairments, and leverage the inherent resilience
  of cellular networks to these events. Experiments with a state-of-the-art 5G
  vRAN testbed show that Slingshot handles PHY failover with no disruption to
  video conferencing, and under 110 ms of disruption to a TCP connection, and it
  also enables zero-downtime upgrades."
view: citation
title: "Resilient Baseband Processing in Virtualized RANs with Slingshot "
subtitle: ""
publication_types:
  - "1"
authors:
  - Nikita Lazarev
  - Tao Ji
  - Anuj Kalia
  - Daehyeok Kim
  - Ilias Marinos
  - Francis Y. Yan
  - Christina Delimitrou
  - Zhiru Zhang
  - Aditya Akella
banner:
  caption: ""
  image: ""
projects:
  - RAN
date: 2023-08-16T15:31:23.942Z
---
