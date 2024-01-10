# Assignment 7 - Analyzing PCAP Files

## Overview
Two pcap files have been provided.  Open them in Wireshark and answer the following questions about each.  Provide your answers in a new file named `answers.txt` and submit it via git as you would any other assignment.  Your answers should be numbered according to the corresponding question number.

*NO LATE SUBMISSIONS WILL BE ACCEPTED*

## Questions

### Section 1 (HTTP)
Open `capture1.pcap` to answer the questions in this section. This file contains HTTP network traffic (among other protocols).

1. What is the new URL of the resource that was provided by the server?
2. What is the name and value of the extension header found in this message?
3. What is the value of the Date header found in this message?

### Section 2 (DNS)
In this section, you will generate a pcap file containing a DNS request and response (the method you choose to generate this traffic this is up to you). The generated pcap file MUST be submitted with this assignment.

Identfiy one DNS request and response from your pcap file that you will answer the following questions about. Identify your selected messages by providing the value found in the "time" column (within Wireshark) below:

4. What is the "time" value of the DNS request you will answer questions about?
5. Is the selected request a recursive request?
6. How many Questions does the query contain?
7. What is the "time" value of the DNS response to the request you referenced above?
8. How many Answer Resource Records does the response contain?
9. How many Authority Resource Records does the response contain?
10. How many Additional Information Resource Records does the reponse contain?
