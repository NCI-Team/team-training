# Goals

- The trainee understand the concept of Network Load Balancer (NLB).
- The trainee will understand when and how to use ECMP NLB.
- The trainee will understand when and how to use PBR NLB.

## Tasks

- Read the `NLB Rational` under the Architectures in the team's Mkdocs.
- What are the main differences between ECMP-based and PBR-based load balancing in ACI?
- How does ACI implement ECMP load balancing, and what are its key requirements?
- What are the advantages and limitations of using PBR for load balancing compared to ECMP?
- How does ACI handle health monitoring in PBR-based load balancing?
- What are the configuration requirements for implementing ECMP load balancing in ACI?
- How does ACI handle node failures in both ECMP and PBR load balancing scenarios?

## Lab

- Follow the runbook of `Configuring A ECMP Network Load Balancer` and create a NLB that will on the 2 Pre-Prod servers we have in the ACI Pre-Prod.

- After Verifying that the NLB is indeed working, delete the steps you created.

- Follow the runbook of `Configuring A PBR Network Load Balancer` and create a NLB that will on the 2 Pre-Prod servers we have in the ACI Pre-Prod.
