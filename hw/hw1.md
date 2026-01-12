# Homework 1 - Getting Set

**Due**: Friday, January 23rd at 5 PM
**Group**: To be completed invididually
**Value**: 5 points (Homework)

The purpose of this homework is to get your GitHub repository set up and shared for the purposes of the class.

## Task Set 1 - GitHub

1. Create a GitHub account if you do not have one already
2. Create a repository named cse60774-sp26-XXXX where XXXX a reasonable personal identifier (e.g. Notre Dame short form netid - e.g. username when logging into the CSE student machines).  The repository should be private.
3. Clone the repository for local editing.
4. Fill in the README.md file in your repository with approrpiate information (name, e-mail).  Push the update to GitHub.
5. Share collaborative access with Prof. Striegel (adstriegel).

## Task Set 2 (Optional)

It may be advantageous to complete these tasks earlier rather than later to help have a successful course project. Note that there is not a specific submission or deliverable for this second task set.

### Task Set 2a - Wireshark / scapy

[Wireshark](https://www.wireshark.org) is a packet capture tool that is effectively a GUI for processing files captured by _libpcap_ and _tcpdump_. [scapy](https://scapy.net) is a Python-based tool for processing pcap files and / or interacting with raw sockets (think Layer 2 - one step below TCP/IP).

For this task, complete the following:

1. Use your laptop to capture packets via Wireshark while connected to the Notre Dame guest WiFi network in either the Huddle (student union) or DeBartolo.  A capture of even a second or two is just fine.
2. Capture packets using _tcpdump_ via the command line (also a short capture)
3. Write code using scapy to count the numer of unique MAC addresses and unique IP addresses detected as part of the two captures
4. Confirm whether or not your device supports packet capture using monitor mode

**Note:** Do not include the respective packet captures in your private repository.

### Task Set 2b - Network Simulation via ns3

If you are thinking that you may want to do a simulation-based project for the course project, it is recommended that you try to get ns3 working. [ns3](https://www.nsnam.org) is a network simulator used by the academic research community.  ns3 involves a healthy amount of C++ programming but has an extensive set of examples.

You are encouraged (but not required) as part of this first homework to try to get ns3 running on your local machine.

**Note:** Do not include the ns3 repository in your private repository.

## Submission

In Canvas, submit the short form of the your final commit hash where you modified the README.md file.  Submit the URL of your repository and the commit hash.
