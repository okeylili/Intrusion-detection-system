# Network Intrusion Detection System (IDS) Using Cisco Packet Tracer

## Project Overview

This project demonstrates a simulated Network Intrusion Detection System (IDS) and Intrusion Prevention System (IPS) configuration using Cisco Packet Tracer. It focuses on network security, router configuration, traffic monitoring, and intrusion detection concepts.

The project was developed as part of a Computer Networks Laboratory (CNL) mini-project.

## Objectives

- Design and analyze a network topology using Cisco Packet Tracer.
- Configure router interfaces and IP addressing.
- Explore Cisco IOS IPS configuration and security monitoring.
- Enable security event reporting through Syslog and SDEE where supported.
- Verify network connectivity and IPS configuration using router CLI commands.
- Understand the role of intrusion detection and prevention in network security.

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS Command-Line Interface (CLI)
- Computer Networks
- Network Security
- Intrusion Detection and Prevention Systems (IDS/IPS)

## Network Configuration

The router configuration explored during development included the following interfaces:

| Interface | IP Address | Status |
|---|---|---|
| GigabitEthernet0/0 | 192.168.1.1 | Up |
| GigabitEthernet0/1 | 100.50.0.1 | Up |
| Serial0/0/0 | 10.10.10.1 | Up |

The project also explores IPS rule configuration, security event reporting, and signature status verification.

## Features

- Network topology simulation
- Router interface configuration
- IP address management
- IPS configuration and inspection
- Security event reporting configuration
- Network interface and configuration verification
- Practical demonstration of network security concepts

## How to Run the Project

1. Install Cisco Packet Tracer on your computer.
2. Clone or download this repository.
3. Open Cisco Packet Tracer.
4. Open the `IDS_CNL_Final_Prj.pkt` file.
5. Inspect the network topology and device connections.
6. Open the router CLI to examine the configuration.
7. Execute the supported verification commands.

## Verification Commands

Use the following commands in the router CLI, depending on the features supported by your simulated device:

```text
show ip interface brief
show running-config
show ip ips all
```

Use `?` in the CLI to view available commands if a command is unsupported.

## IDS vs IPS

**Intrusion Detection System (IDS):** Monitors network activity to identify suspicious traffic and generate alerts.

**Intrusion Prevention System (IPS):** Can detect suspicious traffic and take configured actions to block or prevent it.

This project explores these concepts in a simulated Cisco networking environment.

## Limitations

- Cisco Packet Tracer simulates networking behavior and does not provide the complete capabilities of production IDS/IPS systems.
- Available IPS commands and signature functionality depend on the simulated router model and Packet Tracer version.
- Detection capabilities depend on the features supported by the simulator.

## Future Enhancements

- Add more network devices and security scenarios.
- Configure additional supported IPS signatures.
- Integrate centralized logging where supported.
- Document test cases for normal and suspicious traffic.
- Compare the simulation with dedicated IDS tools such as Snort or Suricata in an isolated lab.

## Project File Structure

```text
IDS-Project/
├── IDS_CNL_Final_Prj.pkt
└── README.md
```

## Conclusion

This project provides practical exposure to network topology design, router configuration, and IDS/IPS concepts using Cisco Packet Tracer. It helps demonstrate the fundamentals of network security and the role of monitoring and prevention mechanisms in protecting network infrastructure.

## Disclaimer

This project is intended for educational purposes and authorized lab environments only.
