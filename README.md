# Ditshupo-Environmental-Engineering-network
This project presents the design, implementation, and simulation of a computer network for Ditshupo Environmental Engineering. The objective is to develop a reliable, scalable, and secure network infrastructure that satisfies the company's operational and communication requirements.

Ditshupo Environmental Engineering is a substantial environmental engineering consultancy based in Kimberley, Northern Cape, serving mining, municipal, and industrial clients across the Northern Cape region. They handle mine rehabilitation, large-scale water quality monitoring, environmental impact assessments (EIA), soil and groundwater remediation, and ongoing compliance monitoring contracts.

The design of the project is as follows: the network is a hierarchical star network whose edge router performs NAT for internet-bound traffic, while the core switch handles inter-VLAN routing between segmented departments.  The network serves approximately 420 staff across a main office and two satellite sites, using the address block 172.30.44.0/23.

## Repository Structure
- `/packet-tracer/` — Cisco Packet Tracer project file(s)
- `/docs/` — design documentation, build log, reference list
- `/screenshots/` — Logical and physical topology screenshots and screenshots of tests, including testing end-to-end connectivity and troubleshooting
