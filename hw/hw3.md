# Homework 3 - Analysis

**Due**: Friday, February 13th (note the changed date to be later)
**Group**: To be completed invididually
**Value**: 25 points (Homework)

The purpose of this assignment is to round out your capabilities for the purpose of the course project where you are capturing packet traces and then analyzing those traces using appropriate tools.  You are welcome to use Python / *scapy* or any other appropriate tool.

## Task 1 - Grab Two Traces

Using your laptop, grab a trace via tcpdump or Wireshark of the CSE website (https://cse.nd.edu) using both *eduroam* as well as *nd-guest*.  Note that for the purpose of this trace, you will not need to put your Wi-Fi adapter into promiscuous mode as we are just interested in the data going to / from your laptop.

To the extent possible, try to minimize the amount of background traffic.

You do not need to put these traces in your GitHub repository.  If you would like to save on the size of the trace, you can set the snaplen to be sufficient only capture the Layer 2, Layer 3 (IPv4), and Layer 4 (TCP) headers.  You can include a `.gitignore` to prevent the pcap files from being included.

## Task 2 - Assess the Traces [10 pts]

Open up the traces inside of Wireshark.  Extract the following information and add it to a Markdown document for submission in a table.

* The IP address of the CSE machine (you might use nslookup if needed)
* Number of packets present in both the downstream and upstream directions (total)
* Number of unique IP addresses present and the volume and count of packets in both directions
* Number of unique TCP flows present and the volume and count of packets in both directions

Assess the two traces.

* Are there significantly different numbers of packets and a volume of data between the two traces?
* What is the primary flow in terms of data volumes?
* What is the likely hop count for the CSE machine?  Assume that TTL starts at a power of two.

## Task 3 - Parse the Trace [15 points]

Using *scapy* or an appropriate tool, evaluate the following aspects of the data:

* Compute the initial SYN and SYN-ACK RTT for all flows
* Compute all observed RTT packet pairs
   * Think about what might constitute a valid RTT.  In this case, RTT can only be computed from the perspective of client (data sent to server, server responds with an ACK).
* Report statistics on the observed packet pairs (count, mean, median)
* Plot the RTT over time as a graph for the connection with the largest number of valid pairs

Analyze and compare *eduroam* versus *nd-guest*.

* Which has the better RTT?
* Which seems to have more variance?
* Are these results surprising? Why?

## Submission

Finish up your Markdown file with the various answers and push it to your private repository. Do a print / save as PDF and upload that PDF to Canvas.

You should also include your code in your private repository.
