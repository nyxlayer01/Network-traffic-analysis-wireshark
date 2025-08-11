# Capture and Analyze Network Traffic Using Wireshark.

## Description
This repository involves packet capture and protocol analysis using Wireshark on Linux.  
The goal was to capture live network packets, apply protocol filters, and identify multiple protocols in the captured traffic.

## Task Objectives
1. Install Wireshark.
2. Capture live traffic on the active network interface.
3. Generate traffic by visiting a website.
4. Apply protocol filters (dns, tcp, http).
5. Identify at least three different protocols.
6. Save the capture as a .pcap file.
7. Summarize findings in a separate report.

## Deliverables in This Repository
- `capture.pcap` – Packet capture file from Wireshark.
- `report.txt` – Summary of protocols identified and observations.
- `README.md` – Task description and repository contents.

## How to View the Capture
1. Download `capture.pcap` from this repository.
2. Open it in Wireshark.
3. Apply filters such as:
   - `dns`
   - `tcp`
   - `http`
4. View **Statistics → Protocol Hierarchy** for a breakdown of protocols.

## Notes
- Website used to generate traffic: https://www.wikipedia.org
- Protocols identified: DNS, TCP, HTTP
