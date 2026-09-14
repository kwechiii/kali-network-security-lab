# Kali Linux Network Security Lab

## Overview

This home lab was created to practice foundational network security, Linux networking, and troubleshooting skills in an isolated virtual environment.

The lab focused on configuring and verifying network interfaces within Kali Linux and preparing the environment for network traffic monitoring with Wireshark.

## Lab Environment

- Kali Linux
- Oracle VirtualBox
- Wireshark
- Isolated virtual network
- IPv4 networking

## Objectives

- Configure a Kali Linux virtual machine for network security analysis
- Identify available Linux network interfaces
- Verify interface status and IPv4 addressing
- Prepare a network interface for packet capture
- Troubleshoot network-interface visibility between Linux and Wireshark

## Network Configuration

During the lab, the Kali Linux system contained multiple network interfaces.

The isolated lab interface was configured with:

- **Interface:** eth1
- **IPv4 Address:** 10.10.10.10/24
- **Network:** 10.10.10.0/24

The interface was verified as active from the Linux command line.

## Tools and Commands

Linux networking utilities were used to inspect and troubleshoot the environment.

Example:

```bash
ip addr
