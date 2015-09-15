# Routing Algorithms
- **Default Router** is the router the host is connected to.
  - Also known as **First-Hop Router**.
  - **Source Router** is the default router of the source host.
  - **Destination Router** is the default router of the destination host.
- A routing algorithms purpose is to find a *good* path from the source router to the destination
router.
  - *good* path usually means least cost.
    - Complicated by policy.
- **Global Routing Algorithm** computes the least-cost path using global info about the networl.
  - Calculation can be run on one site or replicated.
  - In practice known as **link-state algorithms**.
- **Decentralized Routing Algorithm** is when the least cost path is calculated in an iterative and
distributed manner.
