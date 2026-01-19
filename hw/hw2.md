# Homework 2 - Instrumentation

**Due**: Friday, January 30th at 5 PM
**Group**: To be completed invididually
**Value**: 15 points (Homework)

Now that your GitHub repository has been set up, the next task is to conduct several performance tests using both of the Wi-Fi networks on campus (eduroam and nd-guest).  It is recommended that you do these tests in Fitzpatrick or Cushing Hall.

Your answers should be written up in Markdown format.  Extract a PDF of the rendered Markdown from your GitHub repository (Print as PDF when viewing your GitHub repository).

## Task 1 - Compare WiFi

As discussed in class on January 21st, WiFi or 802.11 can operate across a variety of channels in 2.4 GHz, 5 GHz, 6 GHz and channel widths (20, 40, 80, 160 MHz).

Depending upon the type of notebook that you have, try to discern the following aspects for both eduroam and nd-guest:

* What is the primary frequency that you are connecting to (2.4, 5, or 6)?
* What is the channel width?
* What is the transmission speed?
* What is the RSSI?
* What is the MAC address of the access point (BSSID)?
* What is your IP address?

Create a small table that compares and contrast these characteristics.  Are there any differences between eduroam and nd-guest?  Which one should be faster when we run a network performance test?
Include your guess in your Markdown file.

## Task Set 2 - Network Performance Test - Ookla vs. Cloudflare

Both Ookla and Cloudflare offer network performance testing through the website.  To start, try each of the tools once, either on eduroam or nd-guest.

Answer the following in your Markdown file:

* What are the two common high level aspects captured by each of the tools?
* What are two notable differences in terms of performance metrics gathered or reported by the tools?
* What is the IP address of the server used for testing?
* What do you get if you ping that server?
* How many hops away is that server if you run a traceroute?

## Task Set 3 - Compare Wi-Fi

Run a test using both Ookla and Cloudflare on eduroam and nd-guest.

Create a table that contains the following: Latency, Downlink Speed, Uplink Speed.

Note that for Cloudflare, you should choose an appropriate sub-test.

Which Wi-Fi network performed best with regards to each of the three attributes?  Why?  Were the results between Ookla and Cloudflare similar?  What was similar? What was different?

## Additional Enrichment

Repeat one of your better performing test setups (CloudFlare or Ookla, eduroam or nd-guest) from Task Set 3. Use tcpdump or Wireshark to capture packets and ideally to capture only the MAC / IP / TCP layers of information (typically the first 100 bytes).  If possible, use a filter to ensure that only packets for the test are captured.

Using Wireshark and its various capabilities, examine the latency as reported over the course of the connection.  Is it similar to what was reported by Ookla or Cloudflare?  How big was your capture file?

Use your phone and run either the Cloudflare or Ookla test.  Do you get similar performance to your laptop when connected to the same Wi-Fi SSID? Why is that?  Can you look at your phone settings to figure out if you are connected to the same access point?

**Note:** This additional enrichment is entirely optional and is not required to be completed.

## Submission

Finish up your Markdown file with the various answers and push it to your private repository.  Do a print / save as PDF and upload that PDF to Canvas.

**Grading:** Each task is worth 5 points.
