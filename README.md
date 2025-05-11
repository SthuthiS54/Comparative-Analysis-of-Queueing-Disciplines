# Comparative Analysis of Queueing Disciplines

## Project Overview 
This project focuses on analyzing the performance of different queueing disciplines on a Raspberry Pi configured as a WiFi router using OpenWrt. The primary goal is to evaluate the efficiency of fq-codel and fq-pie in wireless networks by measuring latency, throughput, and queueing delay using Flent.

## Objectives
* Configure Raspberry Pi as a WiFi router using OpenWrt.
* Analyze the impact of fq-codel and fq-pie on network performance.
* Measure latency and throughput using Flent.
* Work on comparing the efficiency of queueing disciplines in wireless networks.

## Tools & Technologies
* OpenWrt – Custom Linux-based firmware for network devices.
* Flent (The Flexible Network Tester) – Tool for network performance testing.
* fq-codel & fq-pie – Queueing disciplines used for congestion control.
* Raspberry Pi – Used as a WiFi router for experimentation.

## Setup Instructions
* Flash OpenWrt onto the Raspberry Pi SD card.
* Boot Raspberry Pi and configure OpenWrt settings via SSH and the LuCI web interface.
* Set up WiFi and configure network settings.
* Install necessary packages for monitoring and analysis.
* Run network tests using Flent to analyze latency, throughput, and queueing delay.
* Compare fq-codel and fq-pie based on performance metrics.


