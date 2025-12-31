# Networking--vpc
I will share all networking concelt with practical execution of practical hands-on

# 🔗 VPC Peering (AWS)

## What is VPC Peering?
**VPC Peering** is a networking connection between two VPCs that allows them to communicate **privately** using AWS internal network.

##  Features
- Private communication between VPCs
- Uses private IP addresses
- No internet gateway, NAT, or VPN required
- Low latency and high bandwidth
- Secure and reliable
---
 ## Rules & Constraints
1. CIDR blocks **must not overlap**
2. Peering is **not transitive**
3. Route tables must be updated
4. Security Groups and NACLs must allow traffic
 ---
  ## Types of VPC Peering
- Same account – same region
- Same account – different region
- Different AWS accounts
---

## VPC Peering vs Transit Gateway

| Feature | VPC Peering | Transit Gateway |
|-------|-------------|----------------|
| Transitive Routing |  No | Yes |
| Cost | Free (data transfer only) | Paid |
| Scalability | Limited | High |


