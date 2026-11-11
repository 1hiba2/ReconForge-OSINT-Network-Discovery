# PM5: Network Discovery with Zenmap

## Objective
Perform host discovery and document network configuration within a VirtualBox lab environment.

## Tools
- Kali Linux
- Zenmap
- Nmap
- VirtualBox

## Activities
- Identified the virtual network's IP configuration.
- Performed host discovery using Zenmap.
- Investigated an initial scan reporting 256 hosts.
- Verified connectivity to the virtual gateway.
- Identified available IP and MAC addresses.
- Performed a focused two-host discovery scan.
- Exported a network topology diagram.

## Results
The focused scan confirmed two responding addresses:

| Device | IP Address |
|---|---|
| Virtual gateway | 10.0.0.1 |
| Kali Linux VM | 10.0.0.2 |

The initial scan reported 256 hosts as active, but this result was not independently verified and should not be interpreted as 256 confirmed devices.

## Evidence
This folder contains network configuration screenshots, scan outputs, MAC address evidence, and a topology PDF.
