# Ditshupo-Environmental-Engineering-network
 
This project presents the design, implementation, and simulation of a
computer network for Ditshupo Environmental Engineering. The objective
is to develop a reliable, scalable, and secure network infrastructure
that satisfies the company's operational and communication
requirements.
 
Ditshupo Environmental Engineering is a substantial environmental
engineering consultancy based in Kimberley, Northern Cape, serving
mining, municipal, and industrial clients across the Northern Cape
region. They handle mine rehabilitation, large-scale water quality
monitoring, environmental impact assessments (EIA), soil and
groundwater remediation, and ongoing compliance monitoring contracts.
 
The design of the network is as follows: the network is a hierarchical
star network whose edge router performs NAT for internet-bound
traffic, while the core switch handles inter-VLAN routing between
segmented departments. The network serves approximately 420 staff
across a main office and two satellite sites, using the address block
172.30.44.0/23.
 
## Repository Structure
 
- `/packet-tracer/` — Cisco Packet Tracer project file(s)
- `/docs/` — design documentation, build log, reference list
- `/screenshots/` — Logical and physical topology screenshots and
  screenshots of tests, including testing end-to-end connectivity and
  troubleshooting
## Which file to open
 
The repo has one file per build stage, with `/03-full-build.pkt/` being the final working file.
 
## Packet Tracer version
 
Built and tested on Packet Tracer 9.0.1. Open with the same version or
newer where possible.
 
## Quick orientation
 
- **Design:** extended star, one core multilayer switch, eight access
  switches, one edge router doing NAT, one internet-simulating ISP
  router, plus a partially-working VPN concentrator for field staff.
- **Addressing block:** `172.30.44.0/23`, ten VLANs. Full addressing plan found in  `/docs/CLIENT_DESIGN_REVIEW.docx/`.
- **Status:** core network (VLANs, routing, DHCP, ACLs, NAT, wireless
  Guest Wi-Fi) is fully built and verified.
  
## Assigned feature and testing evidence
 
The main feature for this network is NAT (PAT/overload)
on the edge router. Implementation details and testing evidence are in
`docs/Milestone_2_Deliverable.docx`.
