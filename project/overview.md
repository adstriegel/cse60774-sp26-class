# CSE 60774 - Course Project

The goal of the course project is to create a conference-level research paper by the end of the class exploring a networking-centric or networking-adjacent project idea.  The project may be done individually or in a group of two.  The final deliverable will be a project presentation (10-15 minutes) and a research paper (5-8 pages).

## Key Dates

As described in the syllabus, the following dates are noted for deliverables.

| Date | Item | Description |
|---|---|---|
| 02-20-26 F | Proposal | A one or two paragraph abstract identifying the topic and group composition |
| 04-01-26 W | Interim Results | In-class presentation for interim results on the project |
| 04-29-26 W | Final Presentation | Final presentations - in class |
| 05-04-26 M | Final Paper | Final paper due date (may be submitted earlier) |

An optional interim draft of the final paper may be submitted by April 10th for feedback that will be returned in one week.

## Project Ideas

As described above, the idea is to create a conference-level (think shorter conferences such as IEEE ICC or Globecom) paper focusing either on a networking-centric (protcols, performance evaluation) or networking-adjacent (networking performance is a notable contributor) topic.  The following are provided as potential ideas for papers though you are welcome to explore topics and consult with Prof. Striegel as appropriate:

* **Prevalence of L4S in the wild:** Conduct various surveys and packet captures across campus as well as nearby locations (Eddy Street, your apartment, etc.) to study the extent to which ECN and L4S are being used.  Note that you will need to focus on non-802.1X networks.  Your focus will be on gathering a large set of traces, scrubbing out the data payloads to focus only on the IP and TCP headers.

* **Prevalence of 6 GHz WiFi in the wild:** Working with Prof. Striegel, set up various WiFi capture gear that can operate in monitor mode to determine the extent of WiFi 6E offerings both on campus as well as nearby areas.  The idea will be to construct an autonomous rig or set of software that could be carried in a backpack or carried in a cart / wagon that can capture WiFi beacons to determine 6 GHz Wi-Fi prevalence.

* **Short video service encodings:** Create or build upon existing tools that allow for the capture of metadata associated with short video (TikTok, YouTube Shorts, Instagram Reels) to capture information about codecs, bitrates, chunk sizes, chunk durations for popular videos and how to autonomously capture top video attributes over an extended monitoring period.

* **Generative AI Interactions:** Conduct a series of captures of web interactions with Chat GPT or similar GenAI tools to study if the interaction patterns and cadence of timing or data sizes can be predictive of whether a GenAI tool is being used in contrast to other web traffic or user traffic patterns.

* **Mystery Bathroom Bandit:** As many of you might have seen by various signs across the bathrooms in Cushing and Fitzpatrick, there have been issues with toilets / urinals having inappropriate materials added causing plumbing issues. Design a system that can capture WiFi scans while preserving privacy, allowing for time correlations of consistent usage of said facilities leveraging various cryptographic aspects.

* **GPU Clustering:** Examine various open source or freely available solutions for GPU clustering and the underlying network impact of various choices.  Explore through simulation how different approaches to transfers (TCP variants, UDP-centric approaches) impact the network performance.

There are also various other ideas that you are welcome to stop by to chat with Prof. Striegel that are a bit more research-oriented.
